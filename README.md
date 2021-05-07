
EFI-HP
HP Probook 430 G3


Carpeta EFI completa, totalmente optimizada y operativa, sin problemas de ACPI.

Creada desde 0 a partir de los repositorios y parches de @Rehabman y @Dortania en OpenCore 0.6.8.

Solo requiere:

1.- Generar un nuevo serial:

GenSMBIOS script:

- https://github.com/corpnewt/GenSMBIOS


2.- Para BLuetooth INTEL:

IntelBluetoothFirmware Kext:

- https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases/tag/1.1.2

Instalar en /EFI/OC/Kexts y tomar Snapshoot con ProperTree-master (Tecla Command + R) y salvar.


3.- Para acceder al WIFI desde el menu:

Heliport para WIFI intel:

- https://github.com/OpenIntelWireless/HeliPort/releases/tag/v1.4.0

Instalar en Aplicaciones


------------------------------------------------------------------------------------------

Mi configuraci—n:

Intel Core i5 6200U CPU (Skylake)
Intel HD 520 Graphics
8GB DDR3
13.3 1366x768 Display
Intel Wireless (Original)
2 USB 3.0 Ports, 1 USB 2.0 Ports
HDMI Port
SD Card Reader
HDD 1TB (Tradicional no SSD)


Configuraci—n del BIOS:

Disable Fast Boot
Disable Power On when AC Detected
Disable Power On when Lid is Opened
Disable Secure Boot
Disable Legacy Boot
Enable Turbo Boost
Enable Hyperthreading
Enable Multi Processor
Enable VT-x
Disable Wake on LAN
Video Memory Size: 64MB
Enable Runtime Power Management
Disable Extended Idle Power States
Enable Deep Sleep
Disable Wake when Lid is Opened
Disable Wake on USB
Enable Power Control


Que funciona:

macOS High Sierra - Mojave - Catalina - Big Sur (Comprobado)
Arranque UEFI via OpenCore 0.6.8
Teclas especiales de volume y brillo
Trackpad (Gestos B‡sicos)
HDMI Video y Sonido
Ethernet Realtek
Wifi,Bluetooth, AirDrop y AirPlay
Audio nativo con AppleALC y jack de audifono
Microfono integrado
Power manager - Sleep
Nivel de bateria
Camara integrada - FaceTime
Puertos USB 3.0
iServices


No Funciona:

Lector de huellas
Lector de tarjetas SD

