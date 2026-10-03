# CBF Late Cutoff

Experimental fork of [Click Between Frames](https://github.com/theyareonit/Click-Between-Frames) 1.5.0 (MIT, by theyareonit/syzzi)
that brings back the old **Late Input Cutoff** option. Windows, GD 2.2081, Geode 5.3.0+.

It is a full copy of CBF, so it **cannot run together with the original CBF** - disable/uninstall the original while using this one.

## What the option does
Right before physics is calculated, the mod delivers click / gameplay-key messages that are already waiting in the OS queue
and uses the current time as the frame boundary, so those inputs are applied in this frame instead of the next one.
Only left mouse button and Space/W/Up/A/D/Left/Right are touched.

## Settings
- Late Input Cutoff (default on)
- Late Cutoff: Keyboard (default on)
