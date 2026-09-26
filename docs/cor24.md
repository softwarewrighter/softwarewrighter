# COR24: one CPU, a dozen languages

MakerLisp's 24-bit RISC for FPGAs -- not my design, but adopted and then surrounded with toolchains, languages and an operating system. This is the largest single thread of work here: the same machine reached from assembler, C, Pascal, Forth, Lisp, APL, Prolog, Smalltalk, SNOBOL4, RPG II, FORTRAN and OCaml, most with a browser demo you can run.

**58 repositories** of 246. Part of [Start Here](../README.md),
the index to everything public.

| Repository | What it is | Language |
|---|---|---|
| [hw-cor24-tang-nano](https://github.com/hardwarewrighter/hw-cor24-tang-nano) <br><sub>hardwarewrighter</sub> | Soft CPU for makerlisp COR24 ISA running on a Tang Nano FPGA | — |
| [cc24](https://github.com/softwarewrighter/cc24) <br><sub>softwarewrighter</sub> | C-compiler for COR24 ISA | Rust |
| [p24c](https://github.com/softwarewrighter/p24c) <br><sub>softwarewrighter</sub> | Pascal for COR24 in C | Assembly |
| [pa24r](https://github.com/softwarewrighter/pa24r) <br><sub>softwarewrighter</sub> | p-code assembler for COR24 in Rust | Rust |
| [pl24r](https://github.com/softwarewrighter/pl24r) <br><sub>softwarewrighter</sub> | P-code Linker for COR24 in Rust | Rust |
| [pr24p](https://github.com/softwarewrighter/pr24p) <br><sub>softwarewrighter</sub> | Pascal Runtime for COR24 written in Pascal (dogfooding) | PLSQL |
| [pv24a](https://github.com/softwarewrighter/pv24a) <br><sub>softwarewrighter</sub> | p-code Virtual Machine for COR24 written in Assembler | Assembly |
| [web-dv24r](https://github.com/softwarewrighter/web-dv24r) <br><sub>softwarewrighter</sub> | Web UI Debugger for p-code VM on COR24, in Rust | Assembly |
| [web-p24c](https://github.com/softwarewrighter/web-p24c) <br><sub>softwarewrighter</sub> | Web UI for Running Pascal Demos in the browser | Rust |
| [cor24-rs](https://github.com/sw-embed/cor24-rs) <br><sub>sw-embed</sub> | COR24 emulator using Yew/Rust/WASM | Rust |
| [sw-cor24-apl](https://github.com/sw-embed/sw-cor24-apl) <br><sub>sw-embed</sub> | APL interpreter to run on COR24 | C |
| [sw-cor24-assembler](https://github.com/sw-embed/sw-cor24-assembler) <br><sub>sw-embed</sub> | COR24 native assembler written in C (runs on COR24 FPGA hardware) | Shell |
| [sw-cor24-basic](https://github.com/sw-embed/sw-cor24-basic) <br><sub>sw-embed</sub> | 1970s-terminal-inspired "Time Sharing" BASIC interpreter for COR24 ISA hardware and emulator | Pascal |
| [sw-cor24-debugger](https://github.com/sw-embed/sw-cor24-debugger) <br><sub>sw-embed</sub> | Debugging support for COR24 ISA that works with the emulator and hardware | — |
| [sw-cor24-emulator](https://github.com/sw-embed/sw-cor24-emulator) <br><sub>sw-embed</sub> | COR24 24-bit RISC emulator (trimmed from cor24-rs) | Rust |
| [sw-cor24-forth](https://github.com/sw-embed/sw-cor24-forth) <br><sub>sw-embed</sub> | Tiny Forth for the COR24 24-bit RISC soft-CPU — DTC assembler kernel | Assembly |
| [sw-cor24-fortran](https://github.com/sw-embed/sw-cor24-fortran) <br><sub>sw-embed</sub> | Fortran compiler for COR24 24-bit RISC ISA (research phase) | Shell |
| [sw-cor24-hlasm](https://github.com/sw-embed/sw-cor24-hlasm) <br><sub>sw-embed</sub> | HLASM for COR24 in assembler | Assembly |
| [sw-cor24-isa](https://github.com/sw-embed/sw-cor24-isa) <br><sub>sw-embed</sub> | COR24 ISA definitions: opcodes, encoding, registers, branch constants | Rust |
| [sw-cor24-macrolisp](https://github.com/sw-embed/sw-cor24-macrolisp) <br><sub>sw-embed</sub> | Tiny Macro Lisp for COR24 — Lisp-1 with closures, GC, and TCO (fork of tml24c) | C |
| [sw-cor24-monitor](https://github.com/sw-embed/sw-cor24-monitor) <br><sub>sw-embed</sub> | A COR24 ISA monitor. | C |
| [sw-cor24-ocaml](https://github.com/sw-embed/sw-cor24-ocaml) <br><sub>sw-embed</sub> | OCaml for COR24 | Pascal |
| [sw-cor24-plsw](https://github.com/sw-embed/sw-cor24-plsw) <br><sub>sw-embed</sub> | My own PL/I inspired system programming language for the COR24 ISA | C |
| [sw-cor24-project](https://github.com/sw-embed/sw-cor24-project) <br><sub>sw-embed</sub> | Software Wrighter COR24 Project -- umbrella repo with docs and links to all related COR24 projects | HTML |
| [sw-cor24-prolog](https://github.com/sw-embed/sw-cor24-prolog) <br><sub>sw-embed</sub> | Prolog based on WAM-like VM | Assembly |
| [sw-cor24-rpg-ii](https://github.com/sw-embed/sw-cor24-rpg-ii) <br><sub>sw-embed</sub> | RPG-II implementation for COR24 in assembler | Shell |
| [sw-cor24-rust](https://github.com/sw-embed/sw-cor24-rust) <br><sub>sw-embed</sub> | Experimental Rust-to-COR24 pipeline via MSP430 IR | Rust |
| [sw-cor24-script](https://github.com/sw-embed/sw-cor24-script) <br><sub>sw-embed</sub> | scripting language for COR24 | Assembly |
| [sw-cor24-smalltalk](https://github.com/sw-embed/sw-cor24-smalltalk) <br><sub>sw-embed</sub> | A demo Smalltalk implemented in Tiny BASIC for COR24 ISA | Awk |
| [sw-cor24-snobol4](https://github.com/sw-embed/sw-cor24-snobol4) <br><sub>sw-embed</sub> | Using PL/SW as SIL to implement SNOBOL4 on COR24 ISA | Shell |
| [sw-cor24-tinyc](https://github.com/sw-embed/sw-cor24-tinyc) <br><sub>sw-embed</sub> | COR24 native C compiler written in C (runs on COR24 FPGA hardware) — future | — |
| [sw-cor24-x-pc-aotc](https://github.com/sw-embed/sw-cor24-x-pc-aotc) <br><sub>sw-embed</sub> | COR24 p-code ahead-of-time cross compiler | Rust |
| [sw-cor24-x-tinyc](https://github.com/sw-embed/sw-cor24-x-tinyc) <br><sub>sw-embed</sub> | Tiny C compiler for the COR24 FPGA soft CPU (forked from tc24r) | Rust |
| [sw-cor24-yocto-ed](https://github.com/sw-embed/sw-cor24-yocto-ed) <br><sub>sw-embed</sub> | C-based line editor to run on COR24 ISA HW and emulator via UART to edit in-memory buffers | C |
| [sw-tos](https://github.com/sw-embed/sw-tos) <br><sub>sw-embed</sub> | Software Wrighters Tiny O/S for COR24 | Assembly |
| [swtos-live](https://github.com/sw-embed/swtos-live) <br><sub>sw-embed</sub> | For hosting stable demos of ../sw-tos at swtos.softwarewrighter.com | JavaScript |
| [web-sw-cor24-apl](https://github.com/sw-embed/web-sw-cor24-apl) <br><sub>sw-embed</sub> | Web UI for sw-cor24-apl | Rust |
| [web-sw-cor24-assembler](https://github.com/sw-embed/web-sw-cor24-assembler) <br><sub>sw-embed</sub> | Browser-based COR24 assembly IDE and emulator | Rust |
| [web-sw-cor24-basic](https://github.com/sw-embed/web-sw-cor24-basic) <br><sub>sw-embed</sub> | Rust/Yew/WASM Web UI for BASIC interpreter written in Pascal to run on a p-code VM on COR24 ISA | Assembly |
| [web-sw-cor24-demos](https://github.com/sw-embed/web-sw-cor24-demos) <br><sub>sw-embed</sub> | Demo landing page for COR24 ISA "live" web demos | HTML |
| [web-sw-cor24-forth](https://github.com/sw-embed/web-sw-cor24-forth) <br><sub>sw-embed</sub> | Browser-based Forth debugger on COR24 (fork of web-tf24a) | Rust |
| [web-sw-cor24-fortran](https://github.com/sw-embed/web-sw-cor24-fortran) <br><sub>sw-embed</sub> | Web UI for COR24 ISA Fortran demo | Rust |
| [web-sw-cor24-macrolisp](https://github.com/sw-embed/web-sw-cor24-macrolisp) <br><sub>sw-embed</sub> | Browser-based Tiny Macro Lisp REPL on COR24 | Assembly |
| [web-sw-cor24-ocaml](https://github.com/sw-embed/web-sw-cor24-ocaml) <br><sub>sw-embed</sub> | Live Demo for COR24 OCAML (implemented in COR24 Pascal) | Rust |
| [web-sw-cor24-pascal](https://github.com/sw-embed/web-sw-cor24-pascal) <br><sub>sw-embed</sub> | Browser-based Pascal demos for COR24 | Assembly |
| [web-sw-cor24-plsw](https://github.com/sw-embed/web-sw-cor24-plsw) <br><sub>sw-embed</sub> | Web UI for sw-cor24-plsw | Rust |
| [web-sw-cor24-smalltalk](https://github.com/sw-embed/web-sw-cor24-smalltalk) <br><sub>sw-embed</sub> | Web UI with live demos for sw-cor24-smalltalk | Rust |
| [web-sw-cor24-snobol4](https://github.com/sw-embed/web-sw-cor24-snobol4) <br><sub>sw-embed</sub> | Rust/Yew/WASM Web UI for SNOBOL4 interpreter written in PL/SW to run on COR24 ISA | JavaScript |
| [web-sw-cor24-x-assembler](https://github.com/sw-embed/web-sw-cor24-x-assembler) <br><sub>sw-embed</sub> | Web UI for the sw-cor24-x-assembler COR24 assembler. Live browser demo using Rust, Yew, and WebAssembly. | Rust |
| [web-sw-cor24-x-tinyc](https://github.com/sw-embed/web-sw-cor24-x-tinyc) <br><sub>sw-embed</sub> | Web IDE for the COR24 Tiny C compiler — browser-based compilation, assembly, and execution | Rust |
| [web-sw-tos](https://github.com/sw-embed/web-sw-tos) <br><sub>sw-embed</sub> | Web live-demo of Software Wrighter Tiny O/S TUI in a browser | Rust |
| [swvs](https://github.com/sw-vibe-coding/swvs) <br><sub>sw-vibe-coding</sub> | Software Wrighter Virtual Storage experimental Operating System | — |
| [tc24r](https://github.com/sw-vibe-coding/tc24r) <br><sub>sw-vibe-coding</sub> | _no description yet_ | Rust |
| [tf24a](https://github.com/sw-vibe-coding/tf24a) <br><sub>sw-vibe-coding</sub> | Tiny Forth for COR24 in Assembler (and Forth) | Assembly |
| [tml24c](https://github.com/sw-vibe-coding/tml24c) <br><sub>sw-vibe-coding</sub> | Tiny Macro Lisp compiled to COR24 toolchain (tc24r compiler, cor24-rs assembler/emulator) | C |
| [web-tc24r](https://github.com/sw-vibe-coding/web-tc24r) <br><sub>sw-vibe-coding</sub> | Web UI for Tiny COR24 in Rust compiler -- live browser demos using Rust/Yew/WASM | Rust |
| [web-tf24a](https://github.com/sw-vibe-coding/web-tf24a) <br><sub>sw-vibe-coding</sub> | Web UI Debugger for Tiny Forth COR24 in Assembler (and Forth) in Rust/Yew/WASM | Assembly |
| [web-tml24c](https://github.com/sw-vibe-coding/web-tml24c) <br><sub>sw-vibe-coding</sub> | Web UI for Tiny Macro Lisp COR24 in C -- live browser demos | Assembly |

---

Counts are of repositories I wrote: public, and not forks. See
[conventions](conventions.md) for how to read a repository name, and
[organisations](organizations.md) for the same repositories grouped by owner.
