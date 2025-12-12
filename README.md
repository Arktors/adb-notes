# ADB Notes

## Basic Commands
- `adb devices` – List connected devices  
- `adb reboot` – Reboot device  
- `adb reboot bootloader` – Reboot to bootloader  
- `adb reboot recovery` – Reboot to recovery

## File Transfer
- `adb push <local> <remote>` – Copy file to device  
- `adb pull <remote> <local>` – Copy file from device

## App Management
- `adb install <apk>` – Install APK  
- `adb uninstall <package>` – Uninstall app

## Logcat / Debugging
- `adb logcat` – View live logs  
- `adb logcat > log.txt` – Save logs to file  

## Fastboot Commands
- `fastboot devices` – Check fastboot connection  
- `fastboot flash recovery recovery.img` – Flash recovery
- `fastboot oem unlock` – Unlock bootloader (varies by device)

## App Management
- `adb shell pm list packages` – List all packages  
- `adb shell pm list packages -s` – List system apps  
- `adb shell pm list packages -3` – List user apps  
- `adb install app.apk` – Install APK  
- `adb install -r app.apk` – Reinstall/overwrite APK  
- `adb uninstall <package>` – Uninstall  
