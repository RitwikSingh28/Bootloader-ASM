## Bootloader Example

A simple bootloader example for x86 architecture, written in Assembly language.

---
## Features

- Clears the screen
- Moves the cursor to the top-left corner
- Prints a custom message
- Halts the system

---
Assembly Details

- Assembled with NASM (Netwide Assembler)
- 16-bit real mode
- Uses BIOS interrupts for screen manipulation

---
Build and Run

1. Assemble with NASM: nasm -f bin bootloader.asm -o bootloader.bin
2. Write to a bootable disk image or run in an emulator

---
Note

This is a basic example and not intended for production use. It serves as a starting point for learning about bootloaders and low-level programming.
