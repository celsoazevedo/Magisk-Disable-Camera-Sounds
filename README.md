# Disable Camera Sounds
This module "disables" the camera shutter and video recording sounds by replacing the following .ogg with muted files.

/system/media/audio/camera_click.ogg
/system/media/audio/camera_focus.ogg
/system/media/audio/VideoRecord.ogg
/system/media/audio/VideoStop.ogg

The default camera app still plays the file (a ~1sec file with no sound), but we can't hear the sound.

## Please follow the law:
It's not legal to disable the camera shutter sound in some countries. If you live in one of those countries, don't use this module.

## Compatibility:
It should work on all phones running CyanogenMod, LineageOS, and most stock ROMs with Magisk 16 (or newer) installed.

## Limitations:
Only works on apps using the default sounds (most default camera apps). Doesn't mute 3rd party camera apps that use their own sounds.
Android uses the same sounds for other tasks. For example, "camera_click.ogg" is also used for screenshots. This means that you'll stop hearing the screenshot sound.

## Download:
https://www.celsoazevedo.com/files/android/magisk-disable-camera-sounds/