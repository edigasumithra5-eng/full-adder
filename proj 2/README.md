# Full Adder using Verilog

## Project Description

A Full Adder is a combinational logic circuit that adds three binary inputs:
- A
- B
- Cin (Carry Input)

It produces:
- Sum
- Cout (Carry Output)

This project demonstrates the design and simulation of a 1-bit Full Adder using Verilog HDL.

## Truth Table

| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
|0|0|0|0|0|
|0|0|1|1|0|
|0|1|0|1|0|
|0|1|1|0|1|
|1|0|0|1|0|
|1|0|1|0|1|
|1|1|0|0|1|
|1|1|1|1|1|

## Logic Equations

Sum = A ⊕ B ⊕ Cin

Cout = (A & B) | (B & Cin) | (A & Cin)

## Software Used

- Verilog HDL
- ModelSim / Vivado / Icarus Verilog
- GTKWave (optional)

## Files

- full_adder.v → Verilog design
- full_adder_tb.v → Testbench
- simulation.png → Simulation waveform

## Expected Output

The simulation verifies all 8 possible input combinations and confirms the Full Adder works correctly.

## Author

Name: Your Name

Department: Electronics and Communication Engineering (ECE)