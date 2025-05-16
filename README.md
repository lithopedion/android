# android

**install**
- sudo apt-get install adb fastboot heimdall-flash android-sdk-platform-tools
- com.looker.droidify, com.fdroid.web, moe.shizuku.privileged.api, org.samo_lego.canta, com.apkpure.arya, tk.hack5.treblecheck, fossify.***.apk, com.termux

**adb**
- adb devices - Ki lakik odalent, kit rejt a víz?
- adb install valami.apk - applikáció telepitése
- adb shell pm list packages
- adb sideload valami.zip - TWRP vagy ROM feltornászása
- adb uninstall valami.apk

**fastboot**
- fastboot devices
- fastboot flash recovery recovery.img
- fastboot flashing unlock             
- fastboot getvar all - partíciók, valami eldurvul
- fastboot oem unlock 
- fastboot reboot

**heimdall** [Samsung]
- heimdall flash --RECOVERY recovery.img –no-reboot

**OS**
- CyanogenMod
- LineageOS
- CrDroid
- Resurrection Remix
- GSI Treble [github.com/phhusson/treble_experimentations]
- AOSP

**OS névsémák** [name scheme]
- CyanogenMod 11 = Android 4
- CyanogenMod 12 = Android 5
- LineageOS 13 = Android 6 = CyanogenMod 13
- LineageOS 14 = Android 7 = CyanogenMod 14
- LineageOS 15 = Android 8
- LineageOS 16 = Android 9
- LineageOS 17 = Android 10
- LineageOS 18 = Android 11
- LineageOS 19 = Android 12
- LineageOS 20 = Android 13
- LineageOS 21 = Android 14
- LineageOS 22 = Android 15

**feltétel**
- build number pötyögtetés > developer options
- USB debugging vagy Wireless debugging
- OEM-feloldás [állitsd be az időt meg a wifi-t]

**sw**
- microG, addonsu, Odin, SP Flash, Magisk, Qualcomm Flash, SN Writer, TWRP, ClockworkMod Recovery, Shizuku

**Enemy at the Gates**
- com.google.android.gm
- com.google.android.gms
- com.android.vending
- telekom bloatware
- samsung bloatware
- duraspeed
- Superfish, wellbeing & friends
- Google/Facebook/Amazon/Microsoft

**Universal Android Debloater**
- bash debloat_script.sh
- adb install fileexplorer.apk - SHTF-scenario, ha túllövünk a célon

**platform**
- ARM-v7a
- ARM64-v8a

**URL**
- androidfilehost.com
- download.lineageos.org/extras
- eu.dl.twrp.me
- firmwarecare.com
- firmwarefile.com
- ftp.acc.umu.se/mirror/lineageos/su
- gsmarena.com
- lineage-archive.timschumi.net
- los-legacy.de
- naijarom.com
- samfw.com/firmware
- twrp.me
- unofficialtwrp.com/devices
- updater-api.oddsolutions.us
- wiki.lineageos.org/devices
- xdaforums.com
- web.archive.org

**repositories**
- apt.izzysoft.de/fdroid/repo
- cromite.org/fdroid/repo 
- f-droid.org/repo
- guardianproject.info/fdroid/repo
- microg.org/fdroid/repo
- newpipe.net/fdroid/repo
