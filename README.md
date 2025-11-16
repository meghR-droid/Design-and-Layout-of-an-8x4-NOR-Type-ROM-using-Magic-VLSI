# 8×4 NOR-Based ROM | Magic VLSI + IRSIM

This repository contains the complete design, layout implementation, and IRSIM simulation of an 8-word × 4-bit NOR-type Read-Only Memory (ROM). The design is fully implemented using the Magic VLSI layout editor and verified using IRSIM.

---

## 📌 Project Overview
- **Memory type:** NOR-based ROM  
- **Size:** 8 words × 4 bits  
- **Technology:** Magic VLSI  
- **Verification:** IRSIM  
- **Design approach:** Each bitcell is implemented using a NOR pull-down network with PMOS pull-ups.
- This report describes the design and verification of an 8-word × 4-bit NOR-type ROM using the Magic VLSI tool. Each bit is implemented with a NOR pull-down network and PMOS pull-ups. Functional behavior was verified in IRSIM using various word-line test patterns. The report covers the architecture, cell design, layout, simulations, and test vectors used in the design process.

This repository includes the layout, extracted netlists, IRSIM simulation commands, waveforms, and final project report.


## 📁 Folder Structure
8*4 ROM
1)Layout : 
a) rom_full.mag 
b) rom_0bit.mag
c)rom_1bit.mag
d)rom_full.spice
e)magic layout.png
f)rom_full.ext

2)irsim :
a)rom_full.sim
b) 1 , 2 , 3 waveforms

3)Report : 
rom_report
