# Asus-ROG-STRIX-pc-build

# Project summary

This project was to test my ability to build a PC from start to finish, solving any troublshooting issues that arose and completing the build within designated time from of 10 hours or less. This was accomplished with research on each part prior to assembly to ensure connectivity and power supply was adequate, and all tools needed aquired along with parts. Once assembled, the installation of Windows 11 via USB created boot drive was completed, followed by full update of all drivers and troubleshooting issues which are documented below. All of which was accomplished within the time frame of 7 hours, 48 minuets.

From this project i used my knowledge of the hardware to ensure installation was correct first time. And through the OS installation and updates I learned how to trouble shoot issues such as Boot up errors with BIOS settings enabling, blank output on monitors and driver updates for older hardware

# Project

Below is my step by step walk through of assembling a PC, from hardware parts and installation into case, to OS installation and driver updates. Included are the troubleshooting steps taken needed to complete this project

# Component research
* Motherboard and connections - DDR4 for RAM, 6th-7th Gen cpu LGA compatability, M.2 slot is PCIe 3.0
* Wattage needed to run components with headroom for overclocking
* Cleaning and reapplication process for thermal paste on used CPU and required tools
* Learning installation process for OS both on to USB and to PC
* Choosing PC case to fit motherboard and large CPU cooler (155mm)
  
# Parts List:
* Motherboard - Asus ROG STRIX B250I gaming mini ATX
* CPU - I7 7700k Quad core 8MB core processor  7th gen Kaby architecture
* CPU cooler - Thermalright peerless assassin 120 twin tower
* GPU - MSi geforce GTX 1080 8GB vram
* RAM - Corsair Vengeance LPX 16 GB (2 x 8 GB) DDR4-2400 CL16
* PSU - Corsair CX series 650W 80+ bronze
* SSD - Samsung 980 1TB MZ-V8V1T0 (PCIe 3.0) 2280 NVMe M.2
* Case - CIT sense black Mid tower (3 fans preinstalled)
* Tools - Thermal paste, Isopropanol Alcohol, cotton buds, compressed air canister, screw driver, hexaganol screw driver, cleaning brush, USB with Windows 11 boot up, ![Motherboard manual](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/9a458fb3b92e0d7c546ae4bc10db0bbd3eca2a46/Pc%20resources/E12478_STRIX_B250I_GAMING_UM_WEB.pdf) 

# Build steps after acquisition and cleaning

* Install Motherboard into case using standoff screws
* Install RAM into designated PCIe sockets
* Clean CPU of old thermal paste with isopropanol alcohol and cotton buds, and apply fresh thermal paste thin and evenly
* Install SSD at 45` angle into middle of motherboard PCIe slot, screw into place with specialist small screw
* Install CPU radiator on top of CPU and attatch the fans using the accompanying fan mounting clip. Attach the wires to a Y splitter connector, then connect to CPU_FAN connector on motherboard
* Install GPU into PCIe socket below SSD, taking out side panels on PC case to fit
* Connect case wires to motherboard labelled POWER SWITCH, RESET BUTTON, POWER LED, HDD LED into front panel connector pins
* Conenct case fan wires to fan hub, connect fan hub to CHA_FAN connector
* Install PSU in bottom of case, fan face down
* Connect PSU wires to CPU 8x pin, Motherboard 24 x pin and GPU 6 + 8 x pin, SATA sable into fan hub
* Cable management using inside PC case holes and cable ties
* Reattatch back panel and glass front panel
* Power on and load into BIOS
* Choose USB for OS installation
* Update all Drivers
* Benchmark tests using 3D mark application, setting Time Spy, as follows:
  - score of 7181 (AVG 7159) for e=whole build. GPU score 7698, CPU score 5202, FPS between 45-49 at 1080p resolution. Temperatures within acceptible tolerances reaching max of 71.44' for CPU and 59.99' for GPU. Potential for overclocking for better CPU performance, but will need better fan curve to compensate for extra generated heat. 

# Troubleshooting

## Problem - Fan hub connection for RGB
- Cause - Fan hub RGB connection was 3 pin, Motherboard requires 4 pin
- Fix - Connect RESET SW wire from case into fan hub. Minimal functionality to adjust lighting with no hazards of mismatched connectors
- Additional work - Aquire adapter for current fan hub to connect to motherboard
                  - Aquire new fan hub which comes with the correct pin head and additional functionality
## Problem - OS errors
- Cause - TPM and secure boot not enabled in BIOS
- Fix - Go into BIOS and enable both TPM and secure boot, then save settings
## Problem - Blank screen
- Cause - Damage to display port socket on GPU
- Fix - GPU has 1 display port socket and three HDMI sockets. Switched out wire for HDMI to connect monitor to different GPU socket
## Problem - Driver issues
- Cause - Asus driver installer is outdated, only offer 32 bit installation for newest drivers
- Fix - Download Intel Driver & support assistant, this application reads the motherboard and hardware. Application finds the latest compatible drivers and installs
## Problem - Audio driver missing
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
  
