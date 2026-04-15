[Back to Portfolio](./)

# Ripple Carry Adder 

- **Class: Computer Architecture**
- **Grade: A**
- **Language(s): Verilog HDL**
- **Source Code Repository:** [mskegro/csci330](https://github.com/mskegro/csci330)  
  (Please [email me](mailto:mskegro@student.csuniv.edu?subject=GitHub%20Access) to request access.)

## Project Description

This project implements a 32-bit Ripple Carry Adder using Verilog HDL. The design is built using modular components including a Half Adder and a Full Adder, which are combined to construct a scalable multi-bit arithmetic system.

The circuit takes two 32-bit inputs, A and B, and produces a 32-bit output S, where S = A + B.

This project demonstrates hierarchical hardware design and is a core component used in a Single Cycle Processor for arithmetic logic operations.

## How to Run the Program

To run this project, follow the steps below.

### Install required dependencies

Make sure Icarus Verilog is installed on your system:

```bash
sudo apt install iverilog
```

### Compile the Verilog files

```bash
iverilog -o rca_sim half_adder.v full_adder.v ripple_carry_adder.v ripple_carry_adder_tb.v
```

### Run the simulation

```bash
vvp rca_sim
```

### View waveform output (optional)

```bash
gtkwave waves.vcd
```

### View output

The program runs in the terminal and verifies:

- Correct 32-bit addition results
- Proper carry propagation across all bits
- Multiple test cases including edge cases (0, max values, random inputs)

## UI Design

This program runs in the terminal using a Verilog testbench for simulation. The output is displayed in the console and waveform viewer (GTKWave), showing correct execution of the ripple carry adder logic (see Fig. 1).

![screenshot](images/project2 2.png)  
Fig 1. Simulation output of 32-bit ripple carry adder testbench

## 3. Additional Considerations

This project highlights important computer architecture concepts such as:

- Hierarchical hardware design (Half Adder - Full Adder - Ripple Carry Adder)
- Binary arithmetic operations at hardware level
- Carry propagation delay in combinational circuits
- Modular Verilog design for CPU datapath components

For more details see [mskegro](https://github.com/mskegro/csci330).

[Back to Portfolio](./)
