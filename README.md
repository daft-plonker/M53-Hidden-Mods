![m53banner](https://i.imgur.com/6s6Q0A8.png)
# M53-Hidden-Mods

### Installation:
1. Download the module from the releases
2. Open the magisk app and go to modules
3. Click the "Install from storage" button and select the .zip you just downloaded 

> Note: It should only be used on the Galaxy M53 (SM-M536B) running the corresponding Android security patch version as written in the releases. Trying on other devices is at your own risk.<br/>The changes are always reversable, by simply removing the module in Magisk.

### Troubleshooting:
- If camera app crashes, please clear camera app data.
- If system apps start crashing, boot into your Recovery and on
  <details open>
  <summary>Stock recovery</summary>
  1. Wipe cache partition</br>2. Repair apps
  </details>
  <details open>
  <summary>TWRP recovery</summary>
  1. Wipe cache partition</br>2. Wipe dalvik cache
  </details>
- To make Object / Shadow / Reflection Eraser show, update [Samsung Photo Editor](https://www.apkmirror.com/apk/samsung-electronics-co-ltd/samsung-photo-editor/) by installing the latest APK.
- To fix Samsung Health root detection, I recommend using [SamsungAppsPatcher](https://adil.hanney.org/SamsungAppsPatcher/)

### Known bugs:
- Camera app crash. Happens when using either facial recognition, or switching from selfie camera to the front camera.
Two workarounds:
- When wanting to use the front camera clear the Camera app storage data and launch it again
- Or switch to another mode when using selfie camera than the default (e.g. video) and it will not crash when switching back to the front

#### Added OS Features:
- Added Native AppLock (To open the app download Activity Launcher search for applock and open activity .settings.AppLockSettingsActivity)
- Higher Audio Quality (Disabled DRC, which deeply compresses audio)
- Disabled Samsung Marketing
- High-End Animations
- Enhanced CPU Responsiveness
- Added High Performance mode (also known as Enhanced Processing mode)
- Voice Recorder Interview mode
- AOD to Lockscreen Transition
- Full Edge Lighting
- Fixed Smart View (Normally broken on rooted devices)
- Enhance Photo Feature in Gallery
- S-Series Gallery Object Capture
To use it, press and hold part of an image for it to make a cut-out.
- Codec support for APE, DSD and HDR10+ content
- Camera Privacy Toggle
- ADPS (Wi-Fi Power Saving)
- Enabled Resolution changing (FHD, HD - only visible in Bixby Routines)
- Smart Widgets
- Samsung Smart Suggestions (Smart Calendar, Smart Widgets Auto Rotation, ..)
- Low Heat Mode
- Color Lens support
- HDR Effect support
- DSP Volume Monitoring
- Added Emergency mode to power off menu
- Hearing aid compatibility
- S-Pen hovering detachment support

#### Added Camera Features:
- Extended Pro (video) mode features
- Unlimited Video File Size
- EIS Support / Video stabilization @ 4K (Disable energy saving mode to avoid lag)
- Object/Shadow/Reflection Eraser (Update [Samsung Photo Editor](https://www.apkmirror.com/apk/samsung-electronics-co-ltd/samsung-photo-editor/) to make it work, by installing the latest APK)
- Full Beauty features (Beauty in Live Focus, Beauty Brighten, Body Beauty, change skin tone)
- Torch Flash in Live Focus
- Review feature
- Audio Input Control
- Improved Scene Detection
- S-Series AI-Models & AI Features
- Video Audio Zoom
- Full Intelligent Recognition (like Smart Scan Text Extraction)
- Full Live Focus (all S-Series effects)
- [Galaxy Watch Camera Controller](https://www.samsung.com/us/support/answer/ANS00084676/)
- Higher Gallery Zoom Quality
- Video Auto FPS
- Many, not worth to mention, additions
