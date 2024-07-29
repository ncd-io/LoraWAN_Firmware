USB-serial driver https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers?tab=downloads

To update the firmware, you will need a

USB to Serial Converter(PR55-68 or any USB to serial) Windows PC

Note: if the file name has any special char, please remove it

How to put in program mode

Start the programming utility.

Select the correct COM port.

Select the updated file.

Click update immediately.

Press and release the RST button

Once the firmware update is finished, the device will reboot

command to use serial python update tool --

python ncd_py_bootloader_v2.py COM3 ./Upgrade.ncd 240

