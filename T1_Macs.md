# T1 Macs

-
## macOS Restore Stick
1. Create macOS Restore Stick (reach out to Apple SE for help)
2. Turn off device to be imaged
3. Insert Restore Stick into device
4. Hold "Option" key and power on the device
5. (optional) Enter Firmware password.
6. Select Restore Stick as boot device
7. The Restore stick should now either: Use ASR to wipe and restore the OS (If the OS version on the stick is the same as the device) OR The restore stick will wipe the device and run the OS installer to ensure proper firmware updates occur.

## TwoCanoes MDS
## startosinstall
1. Download desired macOS installer (installmacos.py, app store, softwareupdate --fetch-full-installer, etc.)
2. In terminal, run: ```/Applications/Install\  macOS\   <VERSION (Name not number)>.app/Contents/Resources/startosinstall --eraseinstall --agreetolicense```
3. This will run the installer and tell it to wipe the device.

## Recovery
1. Turn off device.
2. Hold Left Command + r and power on the device. This will boot you into recovery mode. You may need to remove any firmware password first.
3. Wipe the disk with disk utility (You may need to select "Show All Devices" in the view menu (Top Left).
4. Run the installer

## Internet Recovery
1. Tuirn off the device.
2. Hold Left Command + Left Option + r and power on the device. This will boot you into internet recovery mode. You may need to remove any firmware password first.
3. Wipe the disk with disk utility (You may need to select "Show All Devices" in the view menu (Top Left).
4. Run the installer.
