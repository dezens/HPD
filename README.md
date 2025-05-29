
# Hackintosh ROG Strix X570 I-Gaming Ryzen 3 3200g 

![Screenshot 2025-05-29 at 16 03 02](https://github.com/user-attachments/assets/8de6d0bc-a79d-4165-acfb-db440d0f7cad)

## My Specs:
  |       Type       | Item                                    |
|:----------------:|-------------------------------------------|
|     **CPU**      | [ AMD Ryzen 3 3200G ]                     |
| **Motherboard**  | [ Asus ROG STRIX X570-i GAMING ]          |
|     **RAM**      | [ XLR8 Gaming 16Gb 3200Mhz ]              |
|     **GPU**      | [ AMD Radeon Vega 8 APU) ]                |
|     **SSD**      | [ NVMe Adata Legend 710 256gb ]           |
|                  |                                           |
|    **SMBIOS**    | [ iMacPro1,1 ]                            |
|    **MacOS**     | [ Ventura 13.4]                           |
|   **Opencore**   | [ 1.0.4 ]                                 |

> Note Motherboard need USB Mapping & CPU need value matching (Vanilla OpenCore Guide)

> For USB Mapping I'm using USBTool Box on Windows & Change ur setting (USE NATIVE CLASS)
## Bios Settings

|        Config                                                    | Status                     |
|:----------------------------------------------------------------:|----------------------------|
| **Enter BIOS -> Press Delete ->**                                | [ Enter Setup ]            |
| **Exit ->**                                                      | [ Load Optimised Defaults ]|
| **Ai Tweaker -> Ai Overclock Tuner ->**                          | [ D.O.C.P.]                |
| **Advanced -> APM Configuration -> Power On By PCIe ->**         | [ Disable ]                |
| **Advanced -> PCI Subsystem Settings -> Above 4G Decoding ->**   | [ Enabled ]                |
| **Advanced -> PCI Subsystem Settings -> Re-Size BAR Support ->** | [ Enabled ]                |
| **Advanced -> USB Configuration -> Legacy USB Support ->**       | [ Auto or Disabled ]       |
| **Advanced -> AMD CBS -> IOMMU ->**                              | [ Disabled ]               |
| **Boot -> Boot Configuration -> Fast boot ->**                   | [ Disable ]                |
| **Boot -> CSM -> Launch CSM ->**                                 | [ Disable ]                |
| **Boot -> Secure boot -> OS Type ->**                            | [ Windows UEFI mode ]      |
| **Boot -> Secure boot -> Key Management ->**                     | [ Clear Secure Boot Keys ] |

> Note Need Attention to ur BIOS setting

> for APU need at least 512mb or More GPU memory
 
## OS Support 

|        macOS                                                     | Status                     |
|:----------------------------------------------------------------:|----------------------------|
| **Monterey  ->**                                                 | [ Running Well ]           |
| **Ventura ->**                                                   | [ Running Well ]           |
| **Sonoma ->**                                                    | [ Haven't Try]             |
| **Sequoia ->**                                                   | [ Freeze ]                 |

> Nootedred Cause Freeze on Chrome, Chromium-based browsers and apps like Sublime Text cause graphical artefacts amongst other problems

> need to disable experimental 
> open -a Google\ Chrome --args --disable-gpu

> I think if u really want run on Sequoia ,u'll need AMDTSCSync From ChefKiss 
