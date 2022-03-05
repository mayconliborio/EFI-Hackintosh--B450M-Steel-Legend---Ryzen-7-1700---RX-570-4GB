# EFI-Hackintosh- B450M Steel Legend - Ryzen 7 1700 - RX 570 4GB

Sucessful Monterey installation with Zen Series CPU and B450M Steel Legend motherboard

## Hardware - Hackintosh Config

|       Type       | Item                                   |
|:----------------:|----------------------------------------|
|     **CPU**      | [ AMD Ryzen 1700 ]                     |
| **Motherboard**  | [ B450M Steel Legend (Bios v3.30) ]    |
|     **RAM**      | [ Team Group T-Force Delta 3000Mhz ]   |
|     **GPU**      | [ MSI AMD Radeon RX 570 Armor 4GB OC ] |
|     **SSD**      | [ Adata XPG Gammix S11 Pro NVME 1TB ]  |
| **Power Supply** | [ AeroCool KCAS 500W Bronze 80 Plus ]  |
|                  |                                        |
|    **SMBIOS**    | [ MacPro1,1 ]                          |
|    **MacOS**     | [ Monterey ]                           |
|   **Opencore**   | [ 0.7.8 ]                              |


## Bios Settings

|        Config         | Status      |
|:---------------------:|------------ |
|     **Fast Boot**     | [ Disable ] |
|    **Secure Boot**    | [ Disable ] |
|        **CSM**        | [ Disable ] |
| **Above 4G Decoding** | [ Disable ] |

## Boot Args

`npci=0x2000`

## Notes

`Builtin` is not checked on Ethernet adapter, making it impossible to connect with Apple ID
- to solve this, watch this video after 7:30 : https://youtu.be/mJFfWGryPsk?t=450 (PT-BR)


Discord require a fix to enable Noise Suppression and Watch Live/Share Screen,
- to solve this, watch this video after 4:10 : https://youtu.be/odYcvq-iTGg?t=250 (PT-BR)

# References
https://youtu.be/Oq2dfKEY9OQ (PT-BR)
<br>
https://github.com/luchina-gabriel/BASE-EFI-AMD-RYZEN-THREADRIPPER
<br>
https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html
<br>
https://dortania.github.io/Getting-Started-With-ACPI/
<br>
https://github.com/AMD-OSX/AMD_Vanilla

## Discord - Universo Hackintosh
- [Access Discord](https://discord.universohackintosh.com.br)