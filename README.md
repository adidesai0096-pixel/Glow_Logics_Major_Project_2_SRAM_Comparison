# Comparative Analysis of 6T, 8T and 10T SRAM Cells Using LTspice

## Major Project 2 – VLSI Internship

**Submitted by:** Aditya Ramakant Desai  
**Course:** VLSI  
**Organization:** Glow Logics  
**Simulation Tool:** LTspice 26.1.1

---

## 1. Project Overview

This project focuses on the study and simulation of Static Random-Access Memory (SRAM) cells using LTspice. Three SRAM architectures are considered: 6T, 8T and 10T.

The project examines their circuit structures, transistor organization, storage operation, and read/write concepts. The purpose is to understand how different SRAM architectures are designed and how additional transistors can provide separate or improved read paths.

## 2. Objectives

- Understand the working principle of SRAM.
- Study the CMOS cross-coupled inverter latch used for data storage.
- Construct 6T, 8T and 10T SRAM cell schematics in LTspice.
- Study the role of access transistors and read-port transistors.
- Observe transient simulation waveforms.
- Compare the architectures based on their structure and design considerations.
- Understand important SRAM parameters such as read stability, write ability, power and delay.

## 3. SRAM Architectures

### 6T SRAM Cell

The conventional 6T SRAM cell uses six MOSFETs. Four transistors form two cross-coupled CMOS inverters that store one bit of data. Two access transistors connect the internal storage nodes to the bit lines during read and write operations.

### 8T SRAM Cell

The 8T SRAM architecture uses additional transistors to provide a separate read path. This separates the read operation from the internal storage nodes more effectively than the conventional 6T arrangement.

### 10T SRAM Cell

The 10T SRAM architecture uses a larger transistor network to provide storage and read functionality. Different 10T SRAM designs use different read-port arrangements. The exact operation depends on the selected topology and transistor connections.

## 4. Software and Tools

- LTspice 26.1.1
- CMOS PMOS and NMOS transistor models
- Transient analysis
- Waveform viewer
- Circuit schematic editor

## 5. Repository Structure

```text
Glow_Logics_Major_Project_2_SRAM_Comparison/
│
├── 6T_SRAM/
│   ├── LTspice schematic
│   ├── Schematic screenshot
│   └── Waveform screenshots
│
├── 8T_SRAM/
│   ├── LTspice schematic
│   ├── Schematic screenshot
│   └── Waveform screenshots
│
├── 10T_SRAM/
│   ├── LTspice schematic
│   ├── Schematic screenshot
│   └── Waveform
