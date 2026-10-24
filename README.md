# 2:1 Multiplexer Using Verilog HDL

## 📌 Project Description
This project implements a 2:1 Multiplexer (MUX) using Verilog Hardware Description Language (HDL). A multiplexer is a combinational logic circuit that selects one of two input signals and forwards the selected input to a single output based on a select signal.

## 🎯 Objectives
- Understand the working of a 2:1 Multiplexer.
- Implement a MUX using Verilog HDL.
- Create a testbench to verify the design.
- Learn basic digital logic design and RTL verification.

## ⚙️ Inputs and Outputs

**Inputs**
- `a` — First data input
- `b` — Second data input
- `sel` — Select signal

**Output**
- `y` — Selected output

## 🧠 Working Principle
- When `sel = 0`, the output `y` follows input `a`.
- When `sel = 1`, the output `y` follows input `b`.

## 🧮 Logic Equation
`y = (~sel & a) | (sel & b)`

## 📂 Project Files
- `mux_2to1.v` — Verilog design module.
- `tb_mux_2to1.v` — Testbench used to verify the design.
- `README.md` — Project documentation.
- `mux-output.png` — Simulation output screenshot (if uploaded).

## 🧪 Truth Table

| A | B | Sel | Y |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 0 | 0 |
| 1 | 0 | 0 | 1 |
| 1 | 1 | 0 | 1 |
| 0 | 0 | 1 | 0 |
| 0 | 1 | 1 | 1 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 1 | 1 |

## 🛠️ Tools Used
- Verilog HDL
- EDA Playground
- Icarus Verilog Simulator

## ✅ Verification
The testbench checks both select-signal states and all possible combinations of the two data inputs. The output is verified against the expected truth table.

## 📚 What I Learned
- Multiplexer operation.
- Select-line control.
- Combinational logic design.
- Verilog coding and testbench creation.
- Simulation-based verification.

## 🚀 Future Improvements
- Design a 4:1 Multiplexer.
- Build a 1:2 Demultiplexer.
- Explore larger digital systems.

---
**Author:** ECE Student  
**Project:** Digital Design Using Verilog HDL
