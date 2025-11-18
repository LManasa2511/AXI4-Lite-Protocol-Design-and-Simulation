# AXI4-Lite Protocol Design and Simulation (Verilog HDL)

This project focuses on the software-based design and simulation of the AXI4-Lite protocol using Verilog HDL. AXI4-Lite is a lightweight subset of ARM’s AMBA AXI4 standard used for simple, memory-mapped transactions in embedded and FPGA systems.

## 🔹 Project Highlights
- Verilog-based modelling of **AXI Master** and **AXI Slave**
- Supports all 5 AXI4-Lite channels:
  - Write Address (AW)
  - Write Data (W)
  - Write Response (B)
  - Read Address (AR)
  - Read Data (R)
- VALID–READY handshake implementation
- State-machine-based read/write simulation
- Software-only: No hardware implementation

## 🔹 Files Included
- `src/` – Verilog modules for master, slave, and top-level
- `simulations/` – Testbench and simulation waveforms
- `docs/` – Project description and notes

## 🔹 Tools Used
- Verilog HDL
- Simulation software (ModelSim / Vivado / QuestaSim)

## 🔹 Author
Manasa L
