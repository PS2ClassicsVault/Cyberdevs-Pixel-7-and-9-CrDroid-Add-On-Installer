![crdroid](images/crdroid.png)
# Cyberdev's Pixel 7 & 9 crDroid Add-On Installer
This mods crDroid with tweaks and extra applications that NikGapps didn't install upon installation!

## What is this?
This mod allows you to mod crDroid 11.1 & 11.2 and add additional customization to crDroid build prop and add new apps that NikGapps did not install, however this mod has limitations so please read this carefully so that you are aware of these limitations!

## Limitations:
This mod has limitations that require us to inform  you before using this mod these limitations are as follows:

- Mod is crdroid build specific, this means that we update the build based on the date the build has been released for public use, you should NEVER EVER install this mod that has a different build date then the current build date available on this repo.
- Mod requires a specific kind of gapps that properly resizes your system partitions sccordingly as this mod was created around this principle we recommend downloading this one from ionut: [NikGapps-full-pixels-arm64-15.zip](https://sourceforge.net/projects/nikgapps/files/Elite-Releases/ionut/Android-15/)
- Mod cannot be reverted back before you installed this mod, only way to revert is reflash crdroid as a clean install, you understand this limitation to it's full extent when using this mod.
- Upon installing this mod this modification to crDroid, this limits you from reporting to the developer of bugs present in the current build you have installed as mods to the firmware cannot properly distingish wither if the issue is actually from the OS itself or from the mod itself, thus developer may ignore your report!
- We are not responsible if things go wrong such as an unexpected bootloop, system behavior or loss of files/damage to the firmware due to this mod, though we tested this on my personal device, it's clear with anykind of mod this is a risk always, We always encourge to backup any data before using this or any mod that alters your device(s) firmware.
- This mod will not trip/trigger existing Google Play Integrity verification that is is the GREEN as some mods to build prop can trigger GPIV and lose verification, this mod does not trigger GPIUV and you will remain in the GREEN!
- This mod is device specific, do not install any builds we offer on a device that is not listed each build will have its platform at the end of the filename and in the title of the release.

## What this mod will never install:
- This mod will NOT install applications that requres root, out goal is to keep our mod clean and use on unrooted devices, if you decide to root your device some included applications may cease to work due to root detection.

  ## FOR PIXEL 7 USERS:
- If you are using the Pixel 7 version, We recommend you to use this gapps package for the install to be successful since the pixel 7 doesn't have a lot of storage that the pixel 9 has: [NikGapps-crdroid-official-arm64-15-20250127-signed.zip](https://sourceforge.net/projects/nikgapps/files/Elite-Releases/crdroid-official/Android-15/27-Jan-2025/NikGapps-crdroid-official-arm64-15-20250127-signed.zip/download)

## What applications/Features does this mod installs?
The following applications/features are installed when you install this mod:

### Apps:
- Google Wallet
- Gmail
- Google Play Protect Service STUB
- Google Play Games
- Google Pixel 2,3 & 4 Live Wallpapers
- Xperia Play Live Wallpaper (PS3 Like Design)
- Google Find My Device
- Google Pixel Buds STUB (Updatable via the Google Play Store)
- Google Gemini
- LineageOS Icons (change icons in crdroid home settings)
- Google Icons (change icons in crdroid home settings)
- Updater App shortcut
- YouTube

### Features:
- Pixel 9 Official Stock Bootanimation
- Build prop tweaks from official crdroid build (I update it on every release)
- Fixed permissions for included applications etc.

## NOTICE:
When a new build is released the following things will revert back to stock until i release a updated version of this mod for that build so please be paitent when that happens:
- Build prop tweaks
- Pixel 9 Official Stock bootanimation

## Installation:
To install you will need the following things:

- PC/Laptop
- Google OEM USB Drivers already installed
- crDriod already installed with gapps installed as well (installed separately)
- Up-To-Date platform-tools for adb functionality
- crDroids custom recovery.

## NOTICE FOR FIRST TIME INSTALLING & UPDATING INSTALLERS:
You will encounter an error when installing at the beginning such as metadata error etc, however this is normal and will continue to install the mod as normal, this ouccurs if the installer does not detect the library files for Google Play Protect Service, if it was poresent the erorrs would have not been displayed.

To install place the zip into your platform-tools folder and then open a terminal and type this, but before you do make sure you install this package after you flash you gapps oackage not before!:

Windows: `.\adb -d sideload filename.zip`

Other OS (if above fails): `adb -d sideload filename.zip`

If successful it will begin to run the installer, it will only take less than a minute to comeplete.

## UPDATING VIA THE UPDATER APP NOTICE:
- Before installing a crDroid update using the "Updater" application installed alongside this mod, be aware that during the installation of the update applications (excluding the build.prop modifications, that is reverted by the OS update itself) installed by our mod will be uninstalled and you will notice some or all apps installed by this mod were removed, this is because it is set to clean installation mode to ensure these apps do not break on install. If you wish for this to not occur, please consider installing the update via the System Settings application and updating the OS from there.

# NOTICE OF DEVICE SUPPORT:
If you wish for you variant of the Pixel 7/9 to be supported you will need to take the initiative to pass your build prop to me on every new update otherwise your device will not be updated!

# TROUBLESHOOTING:

### Q: Google Play Store Stub has installed successfully, but doesn't show up via updates in the google play store, is there a way to update the app?

### Answer:
- If it doesn't show up in the play store you can download the update by visiting this [link](https://play.google.com/store/apps/details?id=com.google.android.odad) on your mobile device and choose to open via play store and the listing for GPPS listing will be displayed and you can update it from there.
