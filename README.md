# CMOS 6-Transistor (6T) SRAM Project

## Overview
This project involves the design, simulation, and analysis of a **CMOS 6-Transistor (6T) Static Random-Access Memory (SRAM) cell** using **Cadence Virtuoso**. The SRAM cell is designed to store a single bit of data efficiently, ensuring high stability and low power consumption.

## Software & Tools Used
- **Cadence Virtuoso** (for schematic capture, layout, and simulation)
- **Assura** (for DRC and LVS verification)
- **Analog Design Environment (ADE)** (for waveform analysis)

## Project Workflow
1. **Schematic Design**
   - Designed using **Virtuoso Schematic Editor**.
   - Includes six MOSFETs (4 NMOS & 2 PMOS) forming a cross-coupled inverter pair and access transistors.
   - Verified through **Transient analysis**.

2. **Layout Design**
   - Created using **Virtuoso Layout Editor**.
   - Optimized for **area efficiency** and minimal parasitics.
   - Design Rule Check (**DRC**) performed for layout validation.

3. **Layout Versus Schematic (LVS) Check**
   - Ensured the layout matches the schematic using LVS.

4. **Parasitic Extraction & Post-Layout Simulation**
   - Extracted layout using **Assura**.
   - Post-layout simulation performed to analyze parasitic effects.

## Technical Specifications
- **Technology Node**: 90nm (as per design constraints)
- **Supply Voltage (VDD)**: 1v
- **Word Line (WL) & Bit Line (BL) Operation**
- **Read & Write Stability Analysis** (SNM, Read/Write margins)

## Results & Observations
- **Schematic Simulation**: Verified correct read/write operations.
- **Layout Optimization**: Ensured minimal area and DRC compliance.
- **Post-Layout Simulation**: Observed deviations due to parasitic capacitance and resistance.

## Reference Images

![6_T_SRAM_Schematic](https://github.com/user-attachments/assets/9c9c00ad-e26e-48f0-a146-019346c929d4)

![6_T_SRAM_ADE](https://github.com/user-attachments/assets/64ff13c6-8141-469e-a760-6a0a049863fc)

![6_T_SRAM_Layout](https://github.com/user-attachments/assets/4ff88937-07c9-4c71-b59f-a5f7ae61046c)

![6_T_SRAM_AV_Extracted](https://github.com/user-attachments/assets/68a89d10-cdfa-4917-959d-e0180e196502)

## Contributors 
- **N U Surya Kiran**.

*This project is developed for educational and research purposes.*

