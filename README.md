# ASRock-Z370-Pro4-Hackintosh

This config works under OpenCore 0.7.3 and BigSur 11.1
Also, please generate your SystemData by [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)

## BigSur 11.1 where Saphire 7770HD drives a display + UHD630 headless mode
* Bootloader: OpenCore
* Model Identifier:	**iMac19,1** 
* Motherboard: ASRock-Z370-Pro4
    * Audio Codec: Realtek ALC1220
    * LAN Chip: Intel I219-V
    * BIOS Ver: 4.30
* CPU: Intel i7-8700k Coffee Lake
* RAM: Kingston DDR4 2x16GB 2667 MHz
* Storage: Samsung 970 Evo 1 TB M.2 NVME SSD (M2A slot)  
* eGPU: Palit GeForce GTX 1080 Ti - switched off
* eGPU: Saphire 7770 HD 1ghz - primary gpu
* iGPU: intel UHD 630 is only used for computing tasks and doesn't drive a display
* Monitor: DELL U2715H 5120x2880 (5K/UHD+ - Ultra High Definition Plus)
* wifi: [Fenvi T919](https://aliexpress.ru/item/32778371977.html?&sku_id=12000018003239936) work out of the box

## BigSur 11.1 where Intel UHD drives a display
* Bootloader: OpenCore
* Model Identifier:	**iMac19,1** 
* Motherboard: ASRock-Z370-Pro4
    * Audio Codec: Realtek ALC1220
    * LAN Chip: Intel I219-V
    * BIOS Ver: 4.30
* CPU: Intel i7-8700k Coffee Lake
* RAM: Kingston DDR4 2x16GB 2667 MHz
* Storage: Samsung 970 Evo 1 TB M.2 NVME SSD (M2A slot)  
* eGPU: Palit GeForce GTX 1080 Ti - switched off
* iGPU: intel UHD 630
* Monitor: DELL U2715H 5120x2880 (5K/UHD+ - Ultra High Definition Plus)
* wifi: [Fenvi T919](https://aliexpress.ru/item/32778371977.html?&sku_id=12000018003239936) work out of the box

## High Sierra 10.13.6 + where NVIDIA drives a display
* Bootloader: Clover or OpenCore
* Model Identifier:	**iMac18,3**
* Motherboard: ASRock-Z370-Pro4
  * Audio Codec: Realtek ALC1220
  * LAN Chip: Intel I219-V
  * BIOS Ver: 4.30
* CPU: Intel i7-8700k Coffee Lake
* RAM: Kingston DDR4 2x16GB 2667 MHz
* Storage: Samsung 970 Evo 1 TB M.2 NVME SSD (M2A slot)
* eGPU: Palit GeForce GTX 1080 Ti - switched on by nvidia web drivers
* iGPU: intel UHD 630 is only used for computing tasks and doesn't drive a display
* Monitor: DELL U2715H 5120x2880 (5K/UHD+ - Ultra High Definition Plus)
* wifi: [Fenvi T919](https://aliexpress.ru/item/32778371977.html?&sku_id=12000018003239936) work out of the box

## Tools
* OpenCore Configurator
* [Hackintool](https://github.com/headkaze/Hackintool)
* [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)