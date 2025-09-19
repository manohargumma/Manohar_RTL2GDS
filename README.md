# RISC-V Reference SoC Tapeout Program VSD
Manohar_RTL2GDS

A simplified, week-wise journey from **RTL (Register Transfer Level)** to **GDSII layout** using **open-source EDA tools**.  
This project is inspired by the original [RTL2GDS_Alchemy](https://github.com/TheVoltageVikingRam/RTL2GDS_Alchemy) flow,  
but focuses on a smaller design and easier setup for quick learning.

---

## 🌟 Project Objective
To design, synthesize, and generate a GDSII layout of a simple digital circuit  
using open-source tools such as **OpenLane**, **Magic**, and **Sky130 PDK**.

---

## 📅 Weekly Progress

| Week | Topics Covered | Highlights |
|------|-----------------|------------|
| **Week 0** | Environment Setup | Installed OpenLane, Sky130 PDK, and verified toolchain on Ubuntu. |
| **Week 1** | RTL Design | Designed a basic 4-bit ALU in Verilog and created testbenches. |
| **Week 2** | Synthesis | Performed synthesis with Yosys, analyzed timing and area reports. |
| **Week 3** | Floorplanning & Placement | Defined core area, placed standard cells. |
| **Week 4** | Routing & GDS Export | Completed routing, checked DRC, and generated final GDSII. |

---

## 🛠️ Tools & Technology
- **OpenLane** for automated digital flow  
- **Yosys** for logic synthesis  
- **Magic** & **KLayout** for layout visualization  
- **SkyWater 130nm PDK** as the process design kit  

---

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/RTL2GDS_Lite.git

