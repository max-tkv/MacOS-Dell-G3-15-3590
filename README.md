# MacOS-Dell-G3-15-3590 Hackintosh

## BT + WiFi
itlwm - Intel Wi-Fi Drivers для macOS
IntelBluetoothFirmware - Intel Bluetooth Drivers для macOS
HeliPort - Intel Wi-Fi Client для itlwm

### itlwm
Cсылка https://github.com/OpenIntelWireless/itlwm/releases

Установка:
Распаковать
Скопируйте файлы в соответствующую папку загрузчика на системном разделе EFI. Clover: EFI\CLOVER\kexts\Other или OpenCore: EFI\OC\kexts
Только для OpenCore: пропишите kext'ы в config.plist (добавить из sample.plist)
Перезагрузить и проверить используя HeliPort!

![image](https://user-images.githubusercontent.com/92333709/192636427-ade73731-6e40-4cf6-ae69-1840a9fcc5b6.png)


### IntelBluetoothFirmware
Cсылка https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases

Установка:
Распаковать
Скопируйте файлы в соответствующую папку загрузчика на системном разделе EFI. Clover: EFI\CLOVER\kexts\Other или OpenCore: EFI\OC\kexts
Только для OpenCore: пропишите kext'ы в config.plist (добавить из sample.plist)
Перезагрузить и проверить
Для версии 12.x Monterey, необходимо добавить BlueToolFixup.kext, в папку:

![image](https://user-images.githubusercontent.com/92333709/192636580-ee08881b-633d-4c2e-9698-9d28ee5ce7b1.png)

Clover: EFI\CLOVER\kexts\Other или OpenCore: EFI\OC\kexts
Не используйте BlueToolFixup.kext совместно с IntelBluetoothInjector.kext


### HeliPort
Cсылка https://github.com/OpenIntelWireless/HeliPort/releases
