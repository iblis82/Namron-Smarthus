# EasyHome

This App adds support for ZigBee Devices to Homey.

You must install this App before adding the devices.

## What works

* Connecting ZigBee devices.

* Control ZigBee lights.

## List of supported

### Light (ZigBee)

* RGBW-CCT, RGBW Lighting, RGB-CCT (ZLL)

* CCT Lighting (ZLL)

* DIM Lighting (ZHA)

* ZG9101SAC_HP_Switch (ZHA)

* ZG9101SAC_HP (ZHA)

### Remote Control, Wall Controllers (ZigBee)

* ZGRC-KEY-001 (ZHA)

* ZGRC-KEY-004 (ZHA)

* ZGRC-KEY-037 (ZHA)

* ZG2833K4_EU06 (ZHA)

## Issues 

### Adding device failed?

* Make sure this App is installed.

* Make sure the device is in pair mode.

* Restart this App. (Homey -> More -> Apps -> This App -> Settings (Top right corner) -> Restart App).

* Restart the Homey device and Homey App.

* Reset ZigBee (Homey -> More -> Settings -> ZigBee -> Reset network).

### Identified as an unknown device?

* Provide the basic information of the device to us.

* Steps to get the information. 

> 1. Homey App -> Devices.
> 2. Long Press the unknown device.
> 3. Settings -> Advance settings.
> 4. Provide `Manufacturer ID, Product ID, Device ID, Profile ID` to us. 

## Contact Us

### Email
maginawin@163.com

### Report an issue
https://github.com/easyhomesrc/Homey_EasyHome/issues

## Git Repository 
https://github.com/easyhomesrc/Homey_EasyHome