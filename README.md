# HP-8570w-Hackintosh-10.14-Mojave---EFI-Clover
* HP 8570w:
  - CPU: i7 3820QM
  - VGA: K2000M
  - Ram: 16GB DDR3
  - Disk: 1TB HDD 7200rpm
  - MacOs: 10.14.6
* Make USB BOOT (Windows + MacOS):
  - Tutorial Here: https://lzhoang2601.github.io/CreateUSBmacOSInstall/
* KextUpdater:
  - Link: https://bitbucket.org/profdrluigi/kextupdater/downloads/
* Working: Everything is almost fine except: 
  - Bluetooth (Kext ok but not connect device)
  - iMessage/FaceTime ( I don't use)
  - Brightness Control
  - Wifi ( You can use USB Wifi: I use TL-WN725N) ( P/s: Change IconWifi Here: https://github.com/yunyu/OSXRealtekWifiIcons)
  - ...
* Get smooth scrolling:
  - Download and install MOS: https://mos.caldis.me/
* Clover Configurator:
  - Link: https://mackie100projects.altervista.org/download-clover-configurator/
* Notes:
  - Open a terminal and run: sudo kextcache -i /
  - Fix keyboard shortcuts: https://karabiner-elements.pqrs.org/
* Demo:

![MacOsDemo](https://i.imgur.com/dT6hBR6.png)
