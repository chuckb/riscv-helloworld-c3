# Risc-V 32 Embedded Example With C3 and QEMU
Example code to accompany my video RISC-V Bare Metal Hello World with C3 https://youtu.be/0iAJxx6Ok4E

This code uses the QEMU virt board UART0 to print Hello World to the console without any standard library or boot loader (other than what QEMU provides).

## Prereqs
- QEMU https://www.qemu.org/ 
- Risc-V toolchain https://github.com/riscv-collab/riscv-gnu-toolchain
- C3C https://github.com/c3lang/c3c
- Make

## Running
`make run`
