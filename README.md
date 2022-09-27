# Dell-G3-15-3590 Hackintosh

## BT + WiFi
itlwm - Intel Wi-Fi Drivers для macOS<br />
IntelBluetoothFirmware - Intel Bluetooth Drivers для macOS<br />
HeliPort - Intel Wi-Fi Client для itlwm<br />

### itlwm
Cсылка https://github.com/OpenIntelWireless/itlwm/releases<br />

Установка:<br />
Распаковать<br />
Скопируйте файлы в соответствующую папку загрузчика на системном разделе EFI. Clover: EFI\CLOVER\kexts\Other или OpenCore: EFI\OC\kexts<br />
Только для OpenCore: пропишите kext'ы в config.plist (добавить из sample.plist)<br />
Перезагрузить и проверить используя HeliPort!

![image](https://user-images.githubusercontent.com/92333709/192636427-ade73731-6e40-4cf6-ae69-1840a9fcc5b6.png)


### IntelBluetoothFirmware
Cсылка https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases<br />

Установка:<br />
Распаковать<br />
Скопируйте файлы в соответствующую папку загрузчика на системном разделе EFI. Clover: EFI\CLOVER\kexts\Other или OpenCore: EFI\OC\kexts<br />
Только для OpenCore: пропишите kext'ы в config.plist (добавить из sample.plist)<br />
Перезагрузить и проверить<br /><br />
Для версии 12.x Monterey, необходимо добавить BlueToolFixup.kext, в папку:<br />
Clover: EFI\CLOVER\kexts\Other или OpenCore: EFI\OC\kexts<br />
Не используйте BlueToolFixup.kext совместно с IntelBluetoothInjector.kext<br />

![image](https://user-images.githubusercontent.com/92333709/192636580-ee08881b-633d-4c2e-9698-9d28ee5ce7b1.png)

### HeliPort
Cсылка https://github.com/OpenIntelWireless/HeliPort/releases
