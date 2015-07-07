# Jflte DevCon
### Developers
[B--B](https://github.com/B--B) - Lead

[AntaresOne](http://github.com/AntaresOne) - Developer, git mantainer, scripting, tester

[Alucard24](http://github.com/Alucard24) - Kernel Developer

[MatthewBooth](http://github.com/MatthewBooth) - OTA Updates, git maintainer, scripting, tester

[angelcalibur](https://github.com/angelcalibur) - tester

[smeroni68](https://github.com/smeroni68) - tester



### Changelog (full)
[AOSP-JF](https://github.com/AOSP-JF) - Project GitHub

### Changelog (short)

#### (Beta 2)
* Kernel
    * Various code updates
* ROM
    * Fixed a2dp audio streaming
    * Fixed data usage graph on settings
    * Added Changelog
    * Hopefully fixed audioflinger/mediaserver crash and audio stuttering when indexing media files
    * Enhanced camera, less crashes during usage
    * Fixed camera opening when flash is enabled
    * Updated stagefright with latest cm changes and fixed ffmpeg 2.7 compiling
    * Updated ffmpeg to 2.7
    * Fixed some crash on MediaProvider
    * Blacklisted some bt devices for better compatibility
    * Use Google dns
    * Updated code to android-5.1.1_r6
    * Camera: stop using gps when camera app is in background
    * Reverted Archidroid optimizations for better compatibility with all devices
    * Use Dialer InCallUI and Contacs repos from AOSP
    * Added Launcher3 to build
    * Added 60fps BootAnimation, big thanks to guerreromanuel XDA
    * Tons of fixes on frameworks/base
    * RRO Fully fixed
    * Small fixes on Telephony
    * Added dancing led at boot
    * Added Advanced Reboot Menu
    * A lot of fixes to build enviroment

#### 20150619 (Beta 1)
* Kernel:
    * Unified platform: fixed sensors for all jflte variants
    * F2FS driver updates
    * Small optimizations for alucard, darkness & nightmare governors
    * Various code updates
* ROM:
    * ArchiDroid optimizations v4
    * Added MultiROM compatibility
    * RRO added and partially working: Contacts, Dialer and Settings need some changes. Everything else is correctly themed
    * Fixed BT/WiFi coexistence, now can be turned ON at the same time
    * Fixed back/menu keys lights (timeout set at 5 seconds, user settings soon available in Settings app. For now, enable/disable by writing "softkeys" without quotes in Terminal Emulator (available on Play Store))
    * Fixed F2FS for /cache partition
    * Fixed "First boot doesn't have sound across all the system if the external SD card is not in FAT32"
    * Fixed MicroSD card, all filesystems are mounted well and working in r/w
    * Init: use our specific init
    * Temporarily fixed "No SIM" on Keyguard (removed Carrier text)
    * Various updates on audio/camera code
    * Various updates on BT/WiFi code

#### 20150606
Initial Release