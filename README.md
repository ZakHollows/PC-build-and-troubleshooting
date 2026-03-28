# Windows 11 PC Building, Testing, Troublshooting and Verify of System Set-up

# Project summary

This project was to test my ability to build a PC, troublshooting issues and completing the build with research into parts for connectivity and power supply before final assembly. Full part assembly,installation and troubleshooting followed by installation of Windows OS with troublehsooting steps taken. Updates for drivers, installation of programs and applications.

This taught me the basics of hardware and installation such as RAM into dual channels, CPU thermal paste application and heatsink installation, calculation for power supply and connectivity for wires to motherboard. Along with troubleshooting variours steps for hardware and software installation and updates with older technology.

# Documentation

* Prep area for PC components and tools
* Assemble PC:
    - CPU into CPU socket, secured in place,fresh thermal paste applied
    - SSD into NVME m.2 slot, secured in place
    - Ram into DIMM slots 2nd and 4th slot placements
    - GPU into PCI express slot
    - Power suuply secured in base, wires fed through case slots
    - 24 x pin into motherboard, 8 x pin into CPU, 8 + 6 x pin into GPU, SATA cable into fan hub
    - CPU cooler attached to CPU, wire connected to CPU_fan connector on motherboard
    - Case wires into front panel display connectors on as labled on wires and motherboard
    - Case fans and fanr RGB connected to fan hub, fan hub connected to CHA_FAN header
    - Plug into mains and switch on
    - Plug in USB for Windows 11 OS installation software
    - Download latest drivers, change settings to prioritise performance of system

# Troubleshooting

## Issue - Fan hub connection for RGB
- Cause - Fan hub RGB connection was 3 pin, Motherboard requires 4 pin
- Fix - Connect RESET SW wire from case into fan hub. Minimal functionality to adjust lighting with no hazards of mismatched connectors
- Additional work - Aquire adapter for current fan hub to connect to motherboard
                  - Aquire new fan hub which comes with the correct pin head and additional functionality
## Issue - OS errors
- Cause - TPM and secure boot not enabled in BIOS
- Fix - Go into BIOS and enable both TPM and secure boot, then save settings
## Issue - Blank screen
- Cause - Damage to display port socket on GPU
- Fix - GPU has 1 display port socket and three HDMI sockets. Switched out wire for HDMI to connect monitor to different GPU socket
## Issue - Driver issues
- Cause - Asus driver installer is outdated, only offer 32 bit installation for newest drivers
- Fix - Download Intel Driver & support assistant, this application reads the motherboard and hardware. Application finds the latest compatible drivers and installs
## Issue - Audio driver missing
- Cause - Previous driver issue missed RealTek audio driver
- Fix - Manual installation required, downloaded latest RealTek audio driver from official online site. Once installed checking device management to find the RealTek audio driver 

# Photos
![Cable management](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/055ead3500b4be98dafa800fd5a15a381ddde5a2/Pc%20resources/20251116_141908.jpg)

![Without glass panel](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/055ead3500b4be98dafa800fd5a15a381ddde5a2/Pc%20resources/20251116_142049.jpg)

![with glass panel](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/055ead3500b4be98dafa800fd5a15a381ddde5a2/Pc%20resources/20251116_142441.jpg)

# Acquisition, specifications and cost
View Raw -![Excel spreadsheet](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/5fa844deb6a2236051d35a3de5dc23a53918a119/Pc%20resources/Acquisition%20and%20cost%20spreadsheet.xlsx)

# What I learned

* Types of connections through generations
* Power supply requirements and headroom for future proofing
* Types of screws for different components and how they overlap with other parts and thier installation
* Application and cleaning of thermal paste
* Choosing fan direction for positive/negative airflow
* Installation of all parts and thier wiring
* Cable management
* Installation of OS
* Driver Updates
* Benchmarking
  
