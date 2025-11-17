# Asus-ROG-STRIX-pc-build

This project documents the complete process of building my first custom PC including components, assembly, BIOS and OS configuration, performance testing, and troubleshooting. The goal was to develop hands-on experience to gain a better understanding of how these software and hardware components work together, fit together and how to solve issues along the way. This is to better develope my understand of systems for my career goals working in IT.

Parts List:
* Motherboard - Asus ROG STRIX B250I gaming mini ATX
* CPU - I7 7700k Quad core 8MB core processor  7th gen Kaby architecture
* CPU cooler - Thermalright peerless assassin 120 twin tower
* GPU - MSi geforce GTX 1080 8GB vram
* RAM - Corsair Vengeance LPX 16 GB (2 x 8 GB) DDR4-2400 CL16
* PSU - Corsair CX series 650W 80+ bronze
* SSD - Samsung 980 1TB MZ-V8V1T0 (PCIe 3.0) 2280 NVMe M.2
* Case - CIT sense black Mid tower (3 fans preinstalled)
* Tools - Thermal paste, Isopropanol Alcohol, cotton buds, compressed air canister, screw driver, hexaganol screw driver, cleaning brush, USB with Windows 11 boot up, ![Motherboard manual](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/9a458fb3b92e0d7c546ae4bc10db0bbd3eca2a46/Pc%20resources/E12478_STRIX_B250I_GAMING_UM_WEB.pdf) 

# Build Steps after acquisition and cleaning

* Install Motherboard into case
* Install RAM into designated PCIe sockets
* Apply Thermal paste
* Install CPU cooler and attach wire to CPU_FAN connector
* Install GPU into PCIe socket, taking out side panels to fit
* Install SSD
* Connect case wires to motherboard
* Conecct fan wires to fan hub, connect fan hub to CHA_FAN connector
* Install PSU
* Connect PSU wires to CPU 8x pin, Motherboard 24 x pin and GPU 6 + 8 x pin, SATA sable into fan hub
* Cable management
* Reassemble case
* Power on and load into BIOS
* Choose USB for OS installation
* Update all Drivers
* Benchmark tests

# Troubleshooting

## Connection issues for wiring
- Cause - Mini ATX board and large CPU cooler
- Fix - uninstall CPU until all connection are done following motherboard manual, then reinstall CPU cooler
## Fan hub connection for RGB
- Cause - Fan hub RGB connection was 3 pin, Motherboard requires 4 pin
- Fix - connect RESET SW wire from case into fan hub. Minimal functionality to adjust lighting with no hazards of mismatched connectors
## SSD mismatch
- Cause - Motherboard SSD slot only supports PCIe 3.0, can fit PCIe 4.0 SSDs but not at thier speeds
- Fix - Aquired correct SSD with correct sized screws for installation, and additional heatsink

# Photos
![Cable management](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/055ead3500b4be98dafa800fd5a15a381ddde5a2/Pc%20resources/20251116_141908.jpg)

![Without glass panel](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/055ead3500b4be98dafa800fd5a15a381ddde5a2/Pc%20resources/20251116_142049.jpg)

![with glass panel](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/055ead3500b4be98dafa800fd5a15a381ddde5a2/Pc%20resources/20251116_142441.jpg)

# Acquisition, specifications and cost
View Raw -![Excel spreadsheet](https://github.com/ZakHollows/Asus-ROG-STRIX-pc-build/blob/5fa844deb6a2236051d35a3de5dc23a53918a119/Pc%20resources/Acquisition%20and%20cost%20spreadsheet.xlsx)

# What i learned

* Types of connections through generations
* Power supply requirements and headroom for futur proofing
* Types of screws for different components and how they overlap
* Application and cleaning of thermal paste
* Choosing fan direction for positive/negative airflow
* Installation of all parts and thier wiring
* Cable management
* Installation of OS
* Driver Updates
* Benchmarking
  
