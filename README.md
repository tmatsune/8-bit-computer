# 🧠 8-Bit Computer from Scratch (Logisim)

This project is a fully functional **8-bit computer** designed and built from scratch using [Logisim](http://www.cburch.com/logisim/). Inspired by Ben Eater’s series and classic computer architecture, it aims to demonstrate the fundamentals of digital logic, CPU design, and low-level programming.

---
## Schematic
![My Project]/schematic/circuit_bottom_half.png

---

## 🚀 Features

- **8-bit data bus** and **16-bit address bus**
- **Custom instruction set architecture (ISA)**
- **Clock and control unit** with microprogrammed control logic
- **ALU (Arithmetic Logic Unit)** supporting addition, subtraction, AND, OR, NOT
- **Registers:** A, B, Instruction Register (IR), Program Counter (PC), Flags
- **RAM** module 
- **ROM** for hardcoded programs
- **Simple assembler & machine code format**
- **Support for jump, conditional branching, and immediate values**
- **Clock control:** manual step-through or automatic ticking

---

## 🧩 Modules

- `ALU.circ` – Arithmetic and logic operations
- `Registers.circ` – All general-purpose and special-purpose registers
- `ControlUnit.circ` – Instruction decoding and control signal generation
- `Memory.circ` – RAM/ROM and memory interface
- `Clock.circ` – Manual and automatic clock control
- `CPU.circ` – Top-level CPU integration

---

## 💻 Requirements

- Java 8 or higher

---
## Schematics

