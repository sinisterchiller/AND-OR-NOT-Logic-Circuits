# ECE 210 – AND-OR-NOT Logic Circuits (Lab 1)

## 📚 Overview
This repository contains the **Lab 1** report for the University of Alberta's **ECE 210: Digital Logic Design** course.  
The objective of this experiment was to design, implement, and verify a logic circuit using **AND**, **OR**, and **NOT** gates, both on a breadboard and in **VHDL** on an FPGA.

## 🧠 Objective
- Simplify a 4-input, 2-output truth table using **Karnaugh Maps (K-Maps)**  
- Implement the derived Boolean expressions using **AND**, **OR**, and **NOT** logic chips  
- Validate the circuit through:
  - **Analog Discovery 2** (WaveForms patterns)
  - **VHDL simulation** and FPGA deployment (Zybo Z7)

## ⚙️ Design Summary
- **Inputs:** A, B, C, D  
- **Outputs:** F₁, F₂  
- **Chips used:**  
  - `SN74HC08N` – Quad 2-input AND Gate  
  - `SN74HC04N` – Hex Inverter (NOT Gate)  
- **Software tools:** WaveForms 2, Vivado Design Suite  
- **Hardware:** Analog Discovery 2, Zybo Z7 FPGA board  
- **Support components:** 10 kΩ pull-down resistors, breadboard, jumper wires  

## 🧩 Methodology
1. Construct truth tables for outputs F₁ and F₂  
2. Simplify using **K-Maps**  
3. Derive Boolean equations  
4. Build circuit on a breadboard with the Analog Discovery 2  
5. Test logic responses in **WaveForms**  
6. Implement logic equations in **VHDL**  
7. Simulate and verify correctness in **Vivado**  
8. Program and test on Zybo Z7 FPGA board  

## 📈 Results
- Verified correctness of F₁ and F₂ for all input combinations.  
- Timing issues observed when re-using ICs across phases; resolved with a 3-chip design.  
- Final implementation matched both the truth table and VHDL simulation outputs.

## 🧪 Discussion
- Demonstrated practical design-verification workflow from truth table → K-Map → schematic → FPGA test.  
- Showed importance of **timing constraints** and **circuit phase management**.  
- Future improvement: use **NAND-based implementation** for efficiency.

## 🧾 References
1. Department of Electrical and Computer Engineering, *General Lab Report Style Guide*, University of Alberta, Fall 2017.  
2. Department of Electrical and Computer Engineering, *ECE 210 Lab 1 Manual (Revised)*, University of Alberta, Fall 2014.  
3. Texas Instruments, *CD74HCT04 High-Voltage CMOS Logic Hex Inverter*, Datasheet, Oct 2019.  
4. Texas Instruments, *CD74HCT08 High-Speed CMOS Logic Quad 2-Input AND Gate*, Datasheet, Oct 2019.

## 👥 Authors
- **Anurag Koushik** (ID: 1806274, akoushik)  
- **James Wright** (ID: 1801348, jtwrigh1)  
- **Lab Instructors:** Md Anik Hossain, Mohammad Hadi Masoumi  
- **Date of Lab:** October 15, 2024

## 📄 License
See [LICENSE](./LICENSE) for licensing details.
