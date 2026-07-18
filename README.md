# Verilog Gate-Level Modeling

Implementation and simulation of basic digital logic gates using **Gate-Level Modeling** in **Verilog HDL**.

## 📖 Project Overview

This repository contains the implementation of fundamental digital logic gates using Gate-Level Modeling in Verilog HDL. Each design has been functionally verified using **Icarus Verilog** and analyzed with **GTKWave**.

## 🚀 Implemented Logic Gates

- ✅ AND Gate
- ✅ OR Gate
- ✅ NOT Gate
- ✅ NAND Gate
- ✅ NOR Gate
- ✅ XOR Gate
- ✅ XNOR Gate

## 🛠️ Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave
- Visual Studio Code

## 📂 Repository Structure

```
Verilog-Gate-Level-Modeling/
│
├── AND_Gate/
├── OR_Gate/
├── NOT_Gate/
├── NAND_Gate/
├── NOR_Gate/
├── XOR_Gate/
├── XNOR_Gate/
└── README.md
```

## ▶️ Simulation Flow

1. Write the Verilog design.
2. Create the testbench.
3. Compile using Icarus Verilog.
4. Run the simulation.
5. Verify the output.
6. Analyze the waveform using GTKWave.

## 💻 Compile

```bash
iverilog -o output design.v testbench.v
```

## ▶️ Run Simulation

```bash
vvp output
```

## 📈 View Waveform

```bash
gtkwave waveform.vcd
```

## 📚 Concepts Learned

- Gate-Level Modeling
- Verilog HDL Syntax
- Testbench Development
- Functional Simulation
- Waveform Analysis using GTKWave

## 🎯 Future Work

This repository is the first step in my RTL Design learning journey. Upcoming repositories will include:

- Universal Gates using NAND/NOR
- Half Adder
- Full Adder
- Multiplexers
- Decoders
- Encoders
- Comparators
- Sequential Circuits
