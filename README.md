# FoldAnim

Play animations on the external screen of a Galaxy Fold while using the main screen.  
**Root required**

---

## Overview
FoldAnim keeps the small outer display active even when the device is unfolded.  
It lets you play animations on the cover screen while using the main one.  
The app monitors the fold state and will stop the animation when folded and restart it when unfolded.  

---

### I only tested it on the first gen Galaxy Fold (SM-F900) with Android 12 stock OneUI ROM.
It should work on a GSI ROM too but I haven't tested this yet.

### I DO NOT recommend trying it on another Fold model as it can potentially break the display configuration file.
If anyone has a newer Fold and wants to be a tester for the new version please hit me on Telegram @S7ruc7ureV01d

---

## How it works
- Modifies `/vendor/etc/displayconfig` to enable the small screen when open  
- Plays animations on the external screen  
- Monitors hinge state to start/stop playback  

---

## Requirements
- Root access  
- First Gen Galaxy Fold (SM-F900)  

---

## Installation
1. Install the APK
2. Open the app and grant root permissions when prompted  
3. Tap "Enable dual display". Wait for your Fold to reboot
4. Open FoldAnim and select an animation you want to play
5. Press "Play Animation"

---

## Known issues
1. You must set the FoldAnim's battery usage to unrestricted, otherwise it may be put to sleep
2. Opening the app from recent apps instead of the launcher icon causes the animation to appear on the wrong screen
3. If you click Clear All in recents FoldAnim will be closed and the animation will freeze. To prevent that tap the icon in the task switcher and select "Keep Open"

---

## Disclaimer
This app modifies system configuration files. Use FoldAnim at your own risk.  
I’m not responsible for any damage or issues caused by using FoldAnim.

---
