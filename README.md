# IconLiberator

## A bash script to restore macOS application icons trapped in the "squircle jail"

With the latest version of macOS, 26 Tahoe, Apple introduced a new icon format, that now must fit into the predefined _squircle_ shape. Icons that fail to fit within the squircle are shrunk and placed above an ugly grey background.

However, many application icons are _creative_ and do not fit well into this format. Examples include Audio Hijack, BBEdit, Alfred, Amphetamine, VLC, NValt, Gemini 2, HandBrake and Keyboard Maestro. The Tahoe transformation makes these icons unattractive and often barely visible.

Users of these applications are faced with a choice: either wait for the developers to update their applications with new Tahoe-compatible icons, or restore the appearance of the original icons, as seen in Sequoia or older versions of macOS.

IconLiberator is a small Bash script that does that. To use it open the Terminal and run:

```
./icon_liberator.sh -f applist.txt
```

where the file `applist.txt` contains the list of applications that should be updated.

