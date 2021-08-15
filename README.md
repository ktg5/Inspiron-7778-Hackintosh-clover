# Dell Inspiron 7000 Series Hackintosh
## This EFI goes unused as of Sep. 14, 2020 as the first release of my OpenCore EFI has been released. [You can find more find about this new EFI here.](https://github.com/ktg5/Inspiron-7778-Hackintosh-OC)

The EFI I use for my Dell Inspiron 7000 Series Hackintosh.

[You can easily download the latest version of this EFI folder by looking in the releases section.](https://github.com/ktg5/Inspiron-7778-Hackintosh-clover/releases)

## Note.
THIS IS STILL IN DEVLEOPMENT.

My "custom" EFI is only built for systems running an Dell Inspiron 7000 Series laptop with a Intel i5-6200U, and Intel HD Graphics 520. The reason why I'm talking about this is because in the config.plist, some settings may not match your configzation.

Also your SIMBIOS/BoardSerialNumber, /SerialNumber, /SmUUID, and RtVariables/MLB have to be set by you as they are all set to nothing and MAY cause issues when using services like iMessage and other iCloud services on your system.

Any other things you want to change is all up to you, just make sure you know what you're doing.

If you are switching EFIs; I recommend you reinstall macOS as there could be some issues when booting your original installation of macOS if you have one.

## What does and doesn't work.
### Working:
* Networking + WiFi (I don't remember anything I needed to do for this?...).
* Built-in (thanks to AppleALC).
* AirDrop and other WiFi services on macOS.
* Trackpad and Touchscreen features.
* Battery information.
* SD Card slot - EPIC!
* iMessage and other iCloud services.
* Bluetooth.
### Not working:
* Audio port? - Not too sure yet.
* Sleep. - Needs to be fixed - Stuck at a blank screen.
* FileVault - who even uses that.
### Unknown:
* HDMI and HDMI sound.
