# Dell Inspiron 7000 Series Hackintosh
The EFI I use for my Dell Inspiron 7000 Series Hackintosh.

[You can easily download the latest version of this EFI folder by looking in the releases section.](https://github.com/ktg5/Inspiron-7000-Series-Hackintosh/releases)

## Note.
THIS IS STILL IN DEVLEOPMENT.

My "custom" EFI is only built for systems running an Dell Inspiron 7000 Series laptop with a Intel i5-6200U, and Intel HD Graphics 520. The reason why I'm talking about this is because in some of the settings in the config.plist file, those settings may not match your configzation.

Also your SIMBIOS/BoardSerialNumber, /SerialNumber, /SmUUID, and RtVariables/MLB have to be set by you as they are all set to nothing and MAY cause issues when using services like iMessage and other iCloud services on your system.

Any other things you want to change is all up to you, just make sure you know what you're doing.

## Some known issues at the moment.
At times somethings like the keyboard, and trackpad may not work after a bit of using the laptop. I'll be trying to find out how to solve this, but I have no idea if this is something anyone can help with.

## What does and doesn't work.
### Working:
* Networking + WiFi (I don't remember anything I needed to do for this?...).
* Built-in (thanks to AppleALC).
* AirDrop and other WiFi services on macOS.
* Trackpad and Touchscreen features.
* Battery information.
### Not working:
* iMessage and other iCloud services. - Easy fix?
* Power button. - how
* Sleep. - Needs to be fixed - doesn't wake up after sleep.
### Unknown:
* HDMI and HDMI sound.
