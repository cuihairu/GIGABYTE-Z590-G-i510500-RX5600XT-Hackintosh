# GIGABYTE-Z590-G-i510500-5600XT-hackintosh

Install macOS Ventura on GIGABYTE Z590-Vison-G Mainboard with 10th Gen Intel CPU.

### Information 

- macOS: [Ventura](https://www.apple.com/macos/ventura/)
- bootloader: [OpenCore 0.8.6](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.8.6)

### Hardware

| Component    | Variant                   | Link                                                                                                                                         |
|:------------:|:-------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------:|
| Mainboard    | GIGABYTE Z590-VISON-G | [www.gigabyte.com](https://www.gigabyte.com/Motherboard/Z590-VISION-G-rev-10)                                           |
| Processor    | Intel Core i5 10500      | [ark.intel.com](https://www.intel.com/content/www/us/en/products/sku/199277/intel-core-i510500-processor-12m-cache-up-to-4-50-ghz/specifications.html)     |
| DDR4 RAM     | Corsair 32GB   | [www.corsair.com](https://www.corsair.com/ja/zh/%E7%B1%BB%E5%88%AB/%E4%BA%A7%E5%93%81/%E5%86%85%E5%AD%98/VENGEANCE-LPX/p/CMK128GX4M4A2666C16)|
| NVMe SSD     | Kingston 1TB              | [www.kingston.com](https://www.kingston.com.cn/en/ssd/dc1000b-data-center-boot-ssd)                                                          |
| Graphics     | AMD RX 5600XT 6G (sapphire)   | [www.sapphiretech.com](https://www.sapphiretech.com/en/consumer/pulse-radeon-rx-5600-xt-be-6g-gddr6)                                        |
| WiFi / BT    | BCM94360CD                | [taobao](https://m.tb.cn/h.UXkgkEk?tk=SmoX2D0F2aq)                                                                                           |


### BIOS 

- firmware 

[Version F7b](https://www.gigabyte.cn/Motherboard/Z590-VISION-G-rev-10/support#support-dl-bios)

- settings

```
Settings
    - Platform Power
      - ErP : Enabled
    - IO Ports
      - Internal Graphics : Enabled
      - DVMT Pre-Allocated : 128M
      - DVMT Total Gfx Mem : MAX
      - Above 4G Decoding : Enabled
      - Re-Size BAR Support : Auto
    - Serial Port : Disabled
    - SATA Andd RST Configuration
      - SATA Mode Selection : AHCI
    - Miscellaneous
      - VT-D : Disabled
Boot
    - Secure Boot
       Preferred Operating Mode : Auto
    - CSM Support : Disabled
```
