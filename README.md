<h1 align="center">Embedded Systems & Hardware Design Engineer</h1>

<p align="center">
  <strong>Hardware Design | PCB Routing | Power Electronics | Firmware</strong>
</p>

---

## Summary

Hardware design engineer specializing in high-speed PCB routing, mixed-signal design, power electronics, and firmware development. Designs and delivers production-ready boards from schematic to fabrication, ranging from galvanically isolated through-hole industrial boards to complex 6-layer single-board computers.

---

## Core Technical Stack

| Domain | Technologies |
|---|---|
| **EDA / CAD** | KiCad, Altium Designer, EasyEDA — 1–6-layer PCBs, high-speed, mixed-signal, power, DDR3 length-matched routing |
| **MCU / SoC / SBC** | STM32, ESP32, AVR, PIC, Raspberry Pi, Xilinx Zynq-7000 series |
| **Firmware / CNC** | grblHAL, Marlin, Klipper |
| **Protocols** | UART, SPI, I2C, CAN, USB, Ethernet, JTAG |
| **Power Electronics** | SMPS, isolated supplies, mains EMI filtering (220 VAC), MOSFET/IGBT gate drivers (TLP250, bootstrap), isolated current sensing (LEM), 400 V DC bus, EMC compliance |
| **Fabrication & Lab** | THT/SMD soldering, UV/laser PCB prototyping, oscilloscope and logic analyzer debugging, Gerber/BOM/PnP generation |
| **Programming & Tools** | C/C++, Python, VHDL, Git, Linux, Proteus, LTspice, LaTeX |
| **Industrial Electrical** | Low-voltage cabinet wiring, VFDs, protection devices, AC/DC motor control, diagnostics |

---

## Open-Source Architecture & Projects

### Edge AI Industrial Gateway — *In Progress*
- Xilinx Zynq-7020 based SBC: 1 GB DDR3, 16 GB eMMC, QSPI, Ethernet, CAN, USB, JTAG
- 6-layer PCB designed in Altium with length-matched DDR3 routing
- Repository: [Edge-AI-Industrial-Gateway](https://github.com/EmbeddedPioneer/Edge-AI-Industrial-Gateway)

### Track-Based Industrial CNC Plasma Cutting Machine
- Distributed architecture: 4 nodes — STM32F407 running grblHAL for motion, ESP32 for HMI/control, ATmega328P for isolated arc voltage PID using HCNR200 linear optocoupler, ultrasonic anti-collision
- Full optical isolation and EMC-compliant cabinet design
- Validated cuts on 14 mm steel; reduced fabrication cost by 70%
- Repository: [Track-Based-Industrial-CNC-Plasma-Cutting-Machine](https://github.com/EmbeddedPioneer/Track-Based-Industrial-CNC-Plasma-Cutting-Machine)

### Automatic Lead-Acid Battery Charge/Discharge System
- Three-board system: isolated 34 V / 10 A charger, ESP32-S3 with LEM current/voltage sensing, relay source selection
- LCD and touchscreen interfaces; tested on 12 V and 24 V batteries
- Repository: [Automatic-Lead-Acid-Battery-Charge-Discharge-System](https://github.com/EmbeddedPioneer/Automatic-Lead-Acid-Battery-Charge-Discharge-System)

### 400 V H-Bridge Motor Driver
- Redesigned defective schematic: 4 N-channel MOSFETs, bootstrap high-side drive, freewheeling diodes on 400 V bus
- Isolation clearances and split ground planes per safety standards
- Repository: [400V-H-Bridge-Motor-Driver](https://github.com/EmbeddedPioneer/400V-H-Bridge-Motor-Driver)

### Smart School Attendance Terminal
- Dual-MCU architecture: STM32F411CEU6 for RFID/state handling, ESP32-WROOM-32 for Wi-Fi; offline-first SPI flash buffering with batched cloud upload
- 4-layer PCB with split 3.3 V rails via independent LDOs to isolate ESP32 RF transients from STM32 logic
- Repository: [Smart-School-Attendance-Terminal](https://github.com/EmbeddedPioneer/Smart-School-Attendance-Terminal)

### LED Signs Controller
- ATmega328P-based relay sequencer for retrofitting static shop signs into animated displays; 6-channel and 12-channel variants with SPDT relays for galvanic isolation, 12 V/24 V input support
- Single-layer THT PCB with 0-ohm SMD jump links to resolve routing constraints; hardware-only HMI via DIP switches and rotary potentiometer for animation patterns and 100–1000 ms transition timing
- Repository: [LED-Signs-Controller](https://github.com/EmbeddedPioneer/LED-Signs-Controller)

### APEXION 3D Printer
- Custom Cartesian FDM system running Klipper on RAMPS 1.4 for split-computing architecture; hybrid kinematics with dual Z-axis lead screws and belt-driven X/Y axes, 250×250×180 mm build volume at 100 mm/s
- Reinforced MDF frame with topology-optimized ABS brackets, magnetic spring-steel build plate with ABL, and environmental enclosure for ABS/ASA processing
- Repository: [APEXION-3D-Printer](https://github.com/EmbeddedPioneer/APEXION-3D-Printer)

### Additional Hardware Deliverables
- Military machine gun electric trigger tester
- Motorized standing desk controller
- Static grass applicator
- 10 W laser cutter
- CNC EVO EMC cabinet

---

## Current Research / Focus

Developing a Xilinx Zynq-7020 based industrial edge AI gateway with DDR3 routing and high-speed signal integrity constraints. Studying advanced digital hardware design through FEDEVEL Academy (Phil Salmony).

---

## Links

| Platform | Contact |
|---|---|
| LinkedIn | [linkedin.com/in/blg23m](https://www.linkedin.com/in/blg23m/) |
| Email | b.mhadi22@gmail.com |
