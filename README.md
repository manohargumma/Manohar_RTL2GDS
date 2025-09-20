# 🖥️ RISC-V Reference SoC Tapeout Program VSD
# ⚙️Tool Instalation
<p><b>All the instructions for installation of required tools can be found here:</b></p>
<b>💻System Requirements:</b><br>
🧠 6 GB RAM<br>
💾 50 GB HDD<br>
🐧 Ubuntu 20.04 or higher<br>
🔲  4 vCPU<br>

# Week 0 — Setup & Tools

> 🛠 **Foundation Week: Environment Setup and Tool Installation**  
This week focuses on preparing the development environment with essential open-source EDA tools for the complete RTL-to-GDSII flow.

---

## 📋 Tasks Overview

| Task   | Description          | Tools Installed             | Status |
|--------|----------------------|-----------------------------|--------|
| Task 0 | [Tools Installation](#tools-installed-in-week-0---task-0) | Complete EDA Toolchain Setup | ✅ Done |

---

## 🧰 Tools Installed in Week 0 - Task 0

### Core RTL Design & Synthesis Tools

| Tool       | Purpose                             | Verification |
|------------|-------------------------------------|--------------|
| **Yosys**  | RTL Synthesis & Logic Optimization  | ✅ Verified  |
| **Icarus Verilog (iverilog)** | Verilog Simulation & Compilation | ✅ Verified  |
| **GTKWave**| Waveform Viewer & Analysis          | ✅ Verified  |
| **Ngspice**| Analog & Mixed-Signal Simulation    | ✅ Verified  |
| **Magic VLSI** | Layout Design & DRC Verification | ✅ Verified  |


# 🖥️ OpenLane / Sky130A Setup

This repository documents my OpenLane VLSI environment setup on Ubuntu.

---

## Installed Software & Tools

| Software / Tool | Version / Notes          | Status      |
|-----------------|------------------------|------------|
| Python          | 3.12+                  | ✅ Installed |
| pip / venv      | Latest                  | ✅ Installed |
| Docker          | Latest                  | ✅ Installed |
| OpenLane        | v1.0.2 (commit ff5509f6) | ✅ Installed |
| Ciel            | 2.x                     | ✅ Installed |
| KLayout         | Latest (optional)       | ✅ Installed |

---

## Installed PDKs

| PDK Family | Version / Hash                                      | Status               | Location                 |
|------------|----------------------------------------------------|--------------------|-------------------------|
| sky130A    | 0fe599b2afb6708d281543108caf8310912f54af         | ✅ Enabled & Ready | `~/.ciel/sky130A`       |

---

## Usage

1. Activate virtual environment:
```bash
source ~/OpenLane/venv/bin/activate



