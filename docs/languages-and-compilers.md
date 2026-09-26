# Languages, compilers and instruction sets

The reusable machinery behind the emulators, and the experimental languages that are not tied to COR24: a typed IR with an optimiser, shared ISA/codegen/target cores, a RISC-V RV32I toolchain, and several language designs of my own.

**21 repositories** of 246. Part of [Start Here](../README.md),
the index to everything public.

| Repository | What it is | Language |
|---|---|---|
| [engramish-rs](https://github.com/softwarewrighter/engramish-rs) <br><sub>softwarewrighter</sub> | A Rust demo of a Deepseek Engram-inspired external cache | — |
| [risc-v-rs](https://github.com/sw-embed/risc-v-rs) <br><sub>sw-embed</sub> | RISC-V emulator in Yew/Rust/WASM | Rust |
| [sw-codegen-core](https://github.com/sw-langtools/sw-codegen-core) <br><sub>sw-langtools</sub> | Codegen scaffolding (regalloc, branch relaxation, frame, asm) for the sw-langtools toolchain | Rust |
| [sw-isa-core](https://github.com/sw-langtools/sw-isa-core) <br><sub>sw-langtools</sub> | Core ISA description traits for the sw-langtools toolchain | Rust |
| [sw-rv32i-asm](https://github.com/sw-langtools/sw-rv32i-asm) <br><sub>sw-langtools</sub> | RV32I Assembler: text source to instruction bytes | Rust |
| [sw-rv32i-codegen](https://github.com/sw-langtools/sw-rv32i-codegen) <br><sub>sw-langtools</sub> | RV32I Codegen: lowering TIR to instructions | — |
| [sw-rv32i-emulator](https://github.com/sw-langtools/sw-rv32i-emulator) <br><sub>sw-langtools</sub> | RV32I Emulator: instruction execution semantics | Rust |
| [sw-rv32i-isa](https://github.com/sw-langtools/sw-rv32i-isa) <br><sub>sw-langtools</sub> | RV32I ISA description: opcodes, encoding, decoding, disassembly | Rust |
| [sw-rv32i-target](https://github.com/sw-langtools/sw-rv32i-target) <br><sub>sw-langtools</sub> | RV32I Target description: ABI, calling convention, register classes | Rust |
| [sw-target-core](https://github.com/sw-langtools/sw-target-core) <br><sub>sw-langtools</sub> | Target / ABI / register-class description for the sw-langtools toolchain | Rust |
| [sw-tir](https://github.com/sw-langtools/sw-tir) <br><sub>sw-langtools</sub> | Target-Independent Representation (TIR): SSA IR with block parameters for the sw-langtools toolchain | Rust |
| [sw-tir-opt](https://github.com/sw-langtools/sw-tir-opt) <br><sub>sw-langtools</sub> | Target-independent TIR optimisation passes for the sw-langtools toolchain | Rust |
| [DiscoveryOne](https://github.com/sw-vibe-coding/DiscoveryOne) <br><sub>sw-vibe-coding</sub> | A Rust based new infix/tuple/minting language programmed in 3D based on Tuple | Rust |
| [forthlet](https://github.com/sw-vibe-coding/forthlet) <br><sub>sw-vibe-coding</sub> | a Forth-based implementation of an experimental tuple-first language, Tuplet | Shell |
| [gen-isa](https://github.com/sw-vibe-coding/gen-isa) <br><sub>sw-vibe-coding</sub> | Tool for generating new target ISA emulators, assemblers, tooling different from sw-embed/sw-cor24-isa | Rust |
| [nt-rs](https://github.com/sw-vibe-coding/nt-rs) <br><sub>sw-vibe-coding</sub> | Neural Thickets in Rust: RandOpt-style local expert discovery via parameter perturbation | Rust |
| [rust-to-prolog](https://github.com/sw-vibe-coding/rust-to-prolog) <br><sub>sw-vibe-coding</sub> | An intermediate implementation of Prolog (in Rust) to be ported to COR24 (in PL/SW and SNOBOL4) | Rust |
| [sw-apl](https://github.com/sw-vibe-coding/sw-apl) <br><sub>sw-vibe-coding</sub> | Software Wrighter's APL in Rust | Rust |
| [sw-apl-workspaces](https://github.com/sw-vibe-coding/sw-apl-workspaces) <br><sub>sw-vibe-coding</sub> | educational workspaces for ../sw-apl | Witcher Script |
| [tuplet](https://github.com/sw-vibe-coding/tuplet) <br><sub>sw-vibe-coding</sub> | A named tuple infix PL implemented in OCaml with a FORTH runtime | OCaml |
| [tuplet-rs](https://github.com/sw-vibe-coding/tuplet-rs) <br><sub>sw-vibe-coding</sub> | A Rust-based implementation of an experimental tuple-first language, Tuplet | Rust |

---

Counts are of repositories I wrote: public, and not forks. See
[conventions](conventions.md) for how to read a repository name, and
[organisations](organizations.md) for the same repositories grouped by owner.
