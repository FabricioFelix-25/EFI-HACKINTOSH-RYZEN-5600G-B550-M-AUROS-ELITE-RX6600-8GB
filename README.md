# EFI-HACKINTOSH-RYZEN-5600G-B550-M-AUROS-ELITE-RX6600-8GB
EFI HACKINTOSH// RYZEN 5600G B550 M AUROS ELITE RX6600 8GB

<br/>
ℹ️ The current version is fully macOS  Ventura and Sonoma compatible. OpenCore, drivers, and kexts are always up to date!

:warning: **DISCLAIMER:**
<br/>
 ESTE NÃO É UM GUIA!
É apenas o meu EFI completo para o meu hardware com base nos meus experimentos, por favor, consulte Dortania antes de fazer qualquer coisa. Não me responsabilizo por qualquer dano. Esta configuração OpenCore é otimizada para o meu hardware específico, então por favor, use-o apenas como referência ou se acontecer de você ter o mesmo hardware ou similar.

![Screenshot 2024-06-10 at 10 27 35](https://github.com/FabricioFelix-25/EFI-HACKINTOSH-RYZEN-5600G-B550-M-AUROS-ELITE-RX6600-8GB/assets/126669160/8e2e8ba3-b040-4d63-92b6-abf27b1b4062)


## :computer: Hardware:

| **Category** | **Component**                                                                    |
| ------------ | -------------------------------------------------------------------------------- |
| **CPU**      | 3,9 GHz AMD Ryzen 5 5600G 6-Core Processor                                        |
| **GPU**      | Gigabyte Eagle - AMD Radeon RX 6600  8GB                       |
| **RAM**      | 16GB  DDR4 3600MHZ                                                   |
| **CHIPSET**  | B550M  [Gigabyte](https://www.gigabyte.com/Motherboard/B550M-AORUS-ELITE-rev-13#kf) |
| **SSD**      | 120GB ADATA SATA                                                                 |
| **Wi-Fi/BT** | Fenvi FV-HB1200  / 7260                                                                |
| **Ethernet** | Realtek RTL8111                                                                  |
| **Audio**    | Realtek ALC897 (layout-id=11)                                                    |


## :white_check_mark: Working:

✅ Trabalhando:
- [x] CPU power management.
- [x] Graphics acceleration.
- [x] Keyboard & Mouse
- [x] Wi-Fi.
- [x] Bluetooth.
- [x] USB ports.
- [x] HDMI video & audio output.
- [x] Ethernet.
- [x] Audio (Internal speakers, 3.5mm headphone jack).
- [x] Internal microphone.
- [x] VGA WebCam.
- [x] AirDrop & Handoff.
- [x] iCloud & App Store.
- [x] iMessage & FaceTime.

## :x: Not working:
             
❌ Não funciona:
 AirDrop não estão funcionando, uso uma placa wifi intel que pelo visto não funciona o airdrop.

Todos os recursos estão funcionando, apenas adicionado uma placa Fenvi FV-HB1200. Agora temos Wi-Fi, Bluetooth (usb mapeado) e outros.


## :closed_lock_with_key: SMBIOS


🔐 SMBIOS
Você precisará gerar seu próprio SMBIOS e configurar, já que é necessário trabalhar totalmente com o macOS. De acordo com este guia, você pode usar os seguintes SMBIOS: iMacPro1,1 ou MacPro7,1. Observe que se o seu hardware é diferente para o mencionado aqui você tem que escolher um SMBIOS apropriado, mais detalhes no guia.

Use GenSMBIOS para gerar seu próprio SMBIOS exclusivo e, em seguida, copie cada parâmetro seguindo o caminho (recomendado para seguir o guia acima):

Config.plist -> PlatformInfo -> Genérico

## BIOS setup:

🔐 Configuração do BIOS:

IMPORTANTE: Precisa ativar a Decodificação Above 4G e definir Resize BAR para Auto no BIOS ou não funcionará! Se você não tiver isso em seu BIOS, você precisará ajustar o config.plist, consulte as configurações do BIOS da AMD e o boot-args

## Credits:

Créditos:
[Gabriel Luchina](https://www.youtube.com/c/GabrielLuchina)

[AMD-OSX](https://github.com/AMD-OSX/AMD_Vanilla)

[Acidanthera](https://github.com/acidanthera)

[Dortânia](https://dortania.github.io/getting-started/)

[Maçã](https://www.apple.com/)
