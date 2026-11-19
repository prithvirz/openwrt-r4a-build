# OpenWrt Custom Build - Xiaomi R4A Gigabit

Custom OpenWrt 24.10 build with mt76x2 5G TX power fix (force 23 dBm when EEPROM returns 0).

## Build
Push to main triggers GitHub Actions. Firmware artifact uploaded on success.

## Flash
Use Breed bootloader fullflash method.

On a fresh install, connect by Ethernet and set a unique root password in LuCI. Configure WPA2 or WPA3 with a private passphrase before enabling Wi-Fi. If you keep settings from an older build, change any root or Wi-Fi passwords that came with that build.
