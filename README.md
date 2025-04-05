# HARDWIRED_PROCESSOR

A SystemVerilog-based implementation of an 8-bit Hardwired Control Processor. This project demonstrates the integration of a control unit and datapath using a hardwired approach, modeled and simulated using SystemVerilog.

---

## 🧠 Project Description

This processor is designed to perform basic operations like loading, arithmetic, and output through a hardwired control unit. It includes:

- Program Counter (PC)
- Accumulator
- ALU (Arithmetic Logic Unit)
- Memory Unit
- Control Unit (hardwired)
- Output Register

The control logic is directly implemented using combinational logic, making it fast and simple for small-scale CPUs.

---

## 📁 Files

| File | Description |
|------|-------------|
| `design.sv` | Main module defining the processor architecture |
| `testbench.sv` | Testbench used to verify the processor functionality |

---

## 🧪 How to Run (Simulation)

You can simulate this project using any SystemVerilog-supported simulator such as:

- ModelSim
- Vivado Simulator
- Icarus Verilog (partial support for SV)
- Synopsys VCS (if available)

### Example using ModelSim:
```bash
vlog design.sv testbench.sv
vsim CPU8_1_tb
