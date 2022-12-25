# Dumper

Dumper is a Frida script to dump L3 private keys from any Android device. (Android 7-9)

## Dependencies

Use pip to install the dependencies:

`pip3 install -r requirements.txt`

## Usage

* Enable USB debugging
* Start frida-server on the device
* Execute dump_keys.py
* Start streaming some DRM-protected content

## Use L3 instead
A few phone brands let us use the L1 keybox even after unlocking the bootloader (like Xiaomi). In this case, installation of a Magisk module called [liboemcrypto-disabler](https://github.com/umylive/liboemcrypto-disabler) is necessary.


## Credits
Thanks to the original author of the code.
