# ga-h97-hd3-opencore
My personal OpenCore configuration for the Gigabyte GA-H97-HD3 motherboard.
Based on korzhyk's [config](https://github.com/korzhyk/OpenCore_GA-H97M-D3H) for GA-H97M-D3H.

Currently tested working with macOS Catalina 10.15.5.

### Hardware configuration
* Gigabyte GA-H97-HD3 rev 1.0 motherboard
* Intel Core i7-4790 CPU
* 2×8 GB Samsung DDR3 1600 MHz RAM
* Biostar G330 256 GB SATA SSD
* WDC Blue 7200rpm 1 TB HDD
* Intel HD Graphics 4600 iGPU
* AMD Radeon RX Vega 64 8GB GPU
* Realtek RTL8168G/8111G ethernet
* Realtek ALC888B audio

## Installation

### BIOS Settings
* *Save & Exit* → Load Optimized Defaults [**Yes**]
* *BIOS Features* → Fast boot [**Disabled**]
* *BIOS Features* → VT-d [**Enabled**]
* *BIOS Features* → Windows 8 Features [**Windows 8 WHQL**]
* *BIOS Features* → CSM Support [**Disabled**]
* *Peripherals* → XHCI Mode [**Enabled**]
* *Peripherals* → Intel Processor Graphics Memory Allocation [**64M**]
* *Peripherals* → XHCI Hand-off [**Enabled**]
* *Peripherals* → EHCI Hand-off [**Enabled**]
* *Peripherals* → Super IO → Serial Port [**Disabled**]

## Issues
1. USB is not mapped correctly yet, but it's somewhat working.
2. Sleep is not working as USB is not fixed yet. Please disable sleep for now.
