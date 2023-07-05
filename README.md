# Dell G3 15 3590 Hackintosh
Hackintosh для ноутбука Dell G3 15 3590

OpenCore Guide: https://dortania.github.io/OpenCore-Install-Guide/<br />
Flash Boot: https://dortania.github.io/OpenCore-Install-Guide/installer-guide/winblows-install.html#making-the-installer <br />

## BT + WiFi
Был заменен WiFi-адаптер на **Intel AX200 Wi-Fi 6**<br />
itlwm - Intel Wi-Fi Drivers для macOS<br />
IntelBluetoothFirmware - Intel Bluetooth Drivers для macOS<br />
HeliPort - Intel Wi-Fi Client для itlwm<br />

### HeliPort WiFi Client
Cсылка https://github.com/OpenIntelWireless/HeliPort/releases

## Audio
Realtek	ALC295<br />	
layouts: <b>(77)<b/>

## Sleep mode
Reboot during sleep.
Decision:
Test solution of the problem
![image](https://user-images.githubusercontent.com/92333709/196003818-8fae3f3e-b211-43e4-8d0e-744d1bd45cd7.png)
