mac-xps-tools
=============

Mac on XPS tools.

## DSDT

DSDT and SSDT files are on dsdt-mac-xps folder.
Most important files that you need to install after executing make.sh:
* DSDT.aml - patched video, audio, brightness, usb
* SSDT.aml - CPU Power management
* SSDT-4.aml - more video stuff with renamed GFX0 -> IGPU symbols

Other raw extracted SSDTs not necessary only syntax errors was fixed. 
