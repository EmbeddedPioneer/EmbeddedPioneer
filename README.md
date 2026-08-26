# Embedded Systems & Hardware Design Engineer

## Summary
Hardware design engineer specializing in high-speed PCB routing, mixed-signal design, power electronics, and firmware development. Designs and delivers production-ready boards from schematic to fabrication, ranging from galvanically isolated through-hole industrial boards to complex 6-layer single-board computers.

## Core Technical Stack

- **EDA / CAD:** KiCad, Altium Designer, EasyEDA — 1–6 layer PCBs, mixed-signal, power, DDR3 length-matched routing
- **MCU / SBC / Firmware:** STM32, ESP32, AVR, PIC, Raspberry Pi, Xilinx Zynq-7020; grblHAL, Marlin, Klipper
- **Protocols:** UART, SPI, I2C, CAN, USB, Ethernet, JTAG
- **Power Electronics:** SMPS and isolated supplies, transformers, EMI filtering for 220 V, MOSFET/IGBT gate drivers (TLP250, bootstrap), isolated current sensing (LEM), 400 V DC bus design, CEM compliance
- **Fabrication & Lab:** THT/SMD soldering, UV/laser PCB prototyping, oscilloscope debugging, full manufacturing file generation
- **Programming & Tools:** C/C++, Python, VHDL, Git, Linux, Proteus, LTspice, LaTeX
- **Industrial Electrical:** Low-voltage cabinet wiring, VFDs, protection devices, AC/DC motor control, diagnostics

## Open-Source Architecture & Projects

### Edge AI Industrial Gateway (in progress)
- Xilinx Zynq-7020 based SBC: 1 GB DDR3, 16 GB eMMC, QSPI, Ethernet, CAN, USB, JTAG
- 6-layer PCB designed in Altium with length-matched DDR3 routing
- Repository: [Edge-AI-Industrial-Gateway](https://github.com/EmbeddedPioneer/Edge-AI-Industrial-Gateway)

### Track-Based Industrial CNC Plasma Cutting Machine
- Distributed architecture: 4 nodes — STM32F407 running grblHAL for motion, ESP32 for HMI/control, ATmega328P for isolated arc voltage PID using HCNR200 linear optocoupler, ultrasonic anti-collision
- Full optical isolation and CEM-compliant cabinet design
- Validated cuts on 14 mm steel; reduced fabrication cost by 70%
- Repository: [Track-Based-Industrial-CNC-Plasma-Cutting-Machine](https://github.com/EmbeddedPioneer/Track-Based-Industrial-CNC-Plasma-Cutting-Machine)

### Automatic Lead-Acid Battery Charge/Discharge System (deployed)
- Three-board system: isolated 34 V / 10 A charger, ESP32-S3 with LEM current/voltage sensing, relay source selection
- LCD and touchscreen interfaces; tested on 12 V and 24 V batteries
- Repository: [Automatic-Lead-Acid-Battery-Charge-Discharge-System](https://github.com/EmbeddedPioneer/Automatic-Lead-Acid-Battery-Charge-Discharge-System)

### Military Machine Gun Electric Trigger Tester (deployed)
- Portable diagnostic device delivering calibrated pulse to verify firing solenoids (PKT, NSV)
- ESP32-S3 isolated logic using TLP250 gate drivers and LEM sensors; validated on live weapons

### 400 V H-Bridge Motor Driver (freelance)
- Redesigned defective schematic: 4 N-channel MOSFETs, bootstrap high-side drive, freewheeling diodes on 400 V bus
- Isolation clearances and split ground planes per safety standards
- Repository: [400V-H-Bridge-Motor-Driver](https://github.com/EmbeddedPioneer/400V-H-Bridge-Motor-Driver)

### Additional Hardware Deliverables
- School attendance terminal (STM32/ESP32, 4-layer PCB)
- Motorized standing desk controller
- Static grass applicator
- Custom Cartesian 3D printer (APEXION) running Klipper
- 10 W laser cutter, CNC EVO CEM cabinet

## Current Research/Focus
Developing a Xilinx Zynq-7020 based industrial edge AI gateway with DDR3 routing and high-speed signal integrity constraints. Studying advanced digital hardware design through FEDEVEL Academy (Phil Salmony).

## Links
- LinkedIn: [linkedin.com/in/blg23m](https://www.linkedin.com/in/blg23m/)
- Email: b.mhadi22@gmail.com
