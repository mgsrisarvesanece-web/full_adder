# full_adder
1-bit Full Adder designed in Verilog using dataflow modeling. Includes RTL design, self-checking testbench, behavioral simulation (XSim), post-synthesis schematic analysis (LUT3 mapping), and power/utilization report in Xilinx Vivado targeting Artix-7.
1-Bit Full Adder – Verilog (Vivado)
📌 Overview

This project implements a 1-bit Full Adder using Verilog HDL in Xilinx Vivado. The design follows a complete RTL-to-synthesis flow including simulation, synthesis, schematic analysis, and power/utilization evaluation targeting an Artix-7 FPGA device.

⚙️ Design Specifications

Inputs:

a

b

c (Carry-in)

Outputs:

sum

carry

Boolean Equations:
sum   = a ^ b ^ c
carry = (a & b) | (b & c) | (a & c)

🏗️ Design Flow

✔ RTL coding using Dataflow modeling
✔ Testbench creation for functional verification
✔ Behavioral simulation using XSim
✔ Synthesis targeting Artix-7 (xc7a35tcpg236-1)
✔ Post-synthesis schematic validation (LUT3 mapping)
✔ Dataflow design summary analysis
✔ Power and resource utilization report evaluation

🔬 Synthesis Details

Logic mapped to LUT3 primitives

Automatic IBUF and OBUF inference

Clean synthesis (no errors or warnings)

Minimal FPGA resource utilization

⚡ Power Analysis

Junction temperature and thermal margin reviewed

Static and dynamic power components analyzed

Low overall power footprint

📊 Tools Used

Xilinx Vivado (2025.x)

Verilog HDL

XSim Simulator

📁 Repository Structure
├── full_adder.v          # RTL design
├── full_adder_tb.v       # Testbench
├── simulation_results/   # Waveform screenshots
├── synthesis_reports/    # Schematic & power reports

🚀 Future Enhancements

Parameterized N-bit adder

Ripple Carry Adder implementation

Carry Lookahead Adder design

ALU module integration

📖 Learning Outcome

This project strengthened understanding of:

RTL design methodology

FPGA LUT-based logic mapping

RTL-to-Netlist flow

Synthesis and power estimation in FPGA design
