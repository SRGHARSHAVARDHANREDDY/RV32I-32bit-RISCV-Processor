# Processor Architecture

## What is a Processor?

A processor repeatedly performs the same cycle:
Fetch Instruction
 ↓
Decode Instruction
 ↓
Execute Instruction
 ↓
Access Memory (if needed)
↓
Write Result
↓
Repeat

The processor executes one instruction at a time (in a single-cycle CPU).
## What is an ISA?

ISA = Instruction Set Architecture

Think of it as the language spoken by the processor.
ADD
SUB
LW
SW
BEQ
These are instructions that the CPU understands.
## What is RISC-V?

RISC-V is an open-source ISA.

Instead of designing your own instruction set, you implement the RISC-V specification.
Used to design processors or cpu's.

## What is RV32I?

RV → RISC-V
32 → 32-bit processor (32-bit registers, ALU, PC, etc.)
I → Base Integer Instruction Set
## What is a Single-Cycle Processor?
A single-cycle processor completes one instruction in one clock cycle.

## Processor Modules

- Program Counter
- Instruction Memory
- Register File
- Control Unit
- Immediate Generator
- ALU
- Data Memory
- Write Back

## Processor Datapath

(I will Add architecture diagram later.)