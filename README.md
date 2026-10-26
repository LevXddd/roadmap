# Learning Roadmap

My public roadmap from C fundamentals to embedded / firmware security.
I update the checkboxes as I go. All resources listed are free (or have free tiers).

**Legend:** ✅ done · 🔄 in progress · ⬜ not started

---

## Phase 1 — C Fundamentals 🔄

Goal: write correct, readable C and understand memory.

- 🔄 Work through **Modern C** (Jens Gustedt) — free PDF from the author
- ⬜ Pointers, arrays, strings, and manual memory management
- ⬜ Structs, unions, bit manipulation, and integer representation
- ⬜ Build with `-Wall -Wextra`, debug with **GDB**, check with **Valgrind** / sanitizers
- ⬜ Small practice programs in [c-playground](https://github.com/LevXddd/c-playground)

Resources: *Modern C* · `man` pages · [Beej's Guide to C](https://beej.us/guide/bgc/)

## Phase 2 — Reverse Engineering Basics ⬜

Goal: read disassembly and understand how programs behave at runtime.

- ⬜ x86-64 assembly basics and calling conventions
- ⬜ ELF format, linking, and the stack
- ⬜ **pwn.college** — Fundamentals → Program Security dojos
- ⬜ **crackmes.one** — start with difficulty 1–2 crackmes
- ⬜ **picoCTF** — Reverse Engineering and Binary Exploitation categories
- ⬜ Tools: GDB (+ pwndbg/GEF), Ghidra, `objdump`, `strace`, `ltrace`

Resources: [pwn.college](https://pwn.college) · [crackmes.one](https://crackmes.one) ·
[picoCTF](https://picoctf.org) · [Ghidra](https://ghidra-sre.org)

## Phase 3 — Embedded + Firmware Security ⬜

Goal: understand microcontrollers and analyze real firmware.

- ⬜ Microcontroller basics (ARM Cortex-M / AVR): registers, GPIO, interrupts
- ⬜ Bare-metal C on a cheap dev board (e.g. STM32 "Blue Pill" or Raspberry Pi Pico)
- ⬜ ARM assembly and reversing ARM binaries in Ghidra
- ⬜ Firmware extraction and analysis with **binwalk**
- ⬜ Hardware interfaces: UART, SPI, I²C, JTAG/SWD
- ⬜ Emulation with **QEMU**

Resources: [Azeria Labs ARM tutorials](https://azeria-labs.com) ·
[binwalk](https://github.com/ReFirmLabs/binwalk) ·
[Microcorruption](https://microcorruption.com) (embedded CTF) ·
[QEMU docs](https://www.qemu.org/docs/master/)

---

_Last updated: 2026-10_
