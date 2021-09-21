# Acer Nitro 5 AN515-54 Hackintosh (OpenCore 0.6.9)

#### Suporte a MacOS Monterey 12.0 Beta (Se houver crash, volte pro BigSur)

![](Images/Home.png)

![](Images/242317474_4287792841258543_7517741188412772262_n.jpeg)

<br/>

## Detalhes do Sistema

| Model            | Acer Nitro 5 AN515-54-58CL 15"                               |
| :--------------- | :----------------------------------------------------------- |
| Processor        | Intel i5-9300H                                               |
| GPU              | Intel UHD Graphics 630 & NVIDIA GeForce® GTX 1650 (Disabled) |
| Memory           | 2x 2666MHz DDR4 8GB HYPERX IMPACT                            |
| SSD              | 1x XPG S41 TUF NVMe SSD 512 GB & 1x HD SATA 1TB              |
| WiFi / BT        | Intel AX200 WI-FI 6                                          |
| Audio            | Realtek ALC255                                               |
| Touchpad         | ELAN 0504                                                    |
| BIOS Version     | 1.33                                                         |
| OpenCore Version | 0.6.9                                                        |

<br/>

#### Suporte a MacOS 11.6.0

<br/>

## O que funciona:

- Wi-fi ✅;
- Bluetooth ✅;
- Trackpad ✅;
- Intel UHD Graphics 630 ✅;
- Webcam ✅;
- Audio ✅;
- Microfone ✅;
- Rede Ethernet ✅;
- Toas as portas USB ✅;
- Teclado e comandos fn ✅.

<br/>

## O que não funciona:

- HDMI (HDMI é controlado pela GeForce® GTX 1650, que não tem suporte, pode usar um adaptador) ver Nota;
- Nvidia GeForce® GTX 1650;
- Hibernação (Set para não hibernar).

<br/>

## Nota 1:

Você pode usar um adaptador para HDMI

[Aqui está um bom](https://s.click.aliexpress.com/e/_A1hTAn)

<br/>

## Nota 2 !!!:

Use GenSMBIOS para gerar um número de série.

[Pode usar esse vídeo de referência](https://www.youtube.com/watch?v=M93oJ1UBrS4)

<br/>

## Créditos

- **Special Thanks** to [dortania](https://dortania.github.io/vanilla-laptop-guide) for the vanilla laptop guide.
- **Special Thanks** to [Acidanthera](https://github.com/acidanthera) for most of the Kexts.
- Thanks to [OpenCore Bootloader](https://https://github.com/acidanthera/OpenCorePkg).
- Thanks to [daliansky](https://github.com/daliansky) for [ACPI Hotpatch Samples for the OpenCore Bootloader](https://github.com/daliansky/OC-little).
- Thanks to [alexandred](https://github.com/alexandred) for [VoodooI2C](https://github.com/alexandred/VoodooI2C).
- Thanks to [corpnewt](https://github.com/corpnewt) for [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS).
- Thanks to [VampFOX67](https://github.com/VampFOX67) for sharing bluetooth fix.
