# RISCV_SingleCycle_Processor
This repository contains a Verilog implementation of a single-cycle RISC-V processor core based on the RV32I instruction set architecture using VSCode and GTKWave.

# Introduction
RISC-V is an open-source Instruction Set Architecture (ISA) that has gained significant traction in both academia and industry. It offers a simple, clean, and extensible design that makes it ideal for various applications, from embedded systems to high-performance computing.
This project implements the RV32I base integer instruction set, which is the fundamental instruction set of the 32-bit RISC-V architecture. The RV32I includes basic integer computational instructions, control flow operations, and memory access instructions.

# Features

Implementation of the RV32I base integer instruction set
Single-cycle core design for simplicity and educational purposes
Support for the following instruction types:

R-type: Register-to-register arithmetic and logical operations
I-type: Immediate arithmetic, logical, and load operations
S-type: Store operations


32-bit data path
32 general-purpose registers (x0 to x31)
Memory-mapped I/O for simple interfacing
