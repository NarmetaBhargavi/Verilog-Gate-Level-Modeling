# Universal Gates using NAND - Verilog HDL

## 📖 Overview

This repository demonstrates the implementation of basic logic gates using only the NAND gate, which is a universal gate.

Each circuit is implemented in Verilog HDL and verified using Icarus Verilog and GTKWave.

---

## 📌 Implemented Gates

- ✅ NOT using NAND
- ✅ AND using NAND
- ✅ OR using NAND
- ✅ XOR using NAND
- ✅ XNOR using NAND

---

## 🛠 Tools

- Verilog HDL
- Visual Studio Code
- Icarus Verilog
- GTKWave

---

## Simulation

Compile

```bash
iverilog -o output design.v testbench.v
```

Run

```bash
vvp output
```

Waveform

```bash
gtkwave waveform.vcd
```

---

## Learning Outcomes

- Universal Gates
- Gate-Level Modeling
- Hierarchical Design
- Verilog HDL
- Functional Verification
