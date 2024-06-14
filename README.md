# LEGv8 Disassembler

This LEGv8 Disassembler is designed to convert binary LEGv8 instruction sets into their corresponding LEGv8 assembly code. Implemented using "bit manipulation". 

## Features

  Input Handling: The disassembler processes input files containing binary LEGv8 instructions in big-endian byte order.
  Output: Outputs the original LEGv8 assembly code to the terminal.

## Supported Instructions

  - Arithmetic: ADD, ADDI, SUB, SUBI, SUBIS, SUBS, MUL
  - Logical: AND, ANDI, EOR, EORI, ORR, ORRI
  - Shift: LSL, LSR
  - Branch: B, BL, BR, CBNZ, CBZ, B.cond (with various condition codes)
  - Load/Store: LDUR, STUR
  - Emulator Specific: PRNT, PRNL, DUMP, HALT

## Usage

 - Run ./build.sh in the src directory to build the project
 - Run ./run.sh <filename.machine> to assemble the specified machine file into its respective LEGv8 assembly code. Output is 
   displayed in the terminal. Output is also written to a output file named assembled.txt.
