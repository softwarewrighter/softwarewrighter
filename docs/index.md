# The whole index

246 repositories across 15 GitHub organisations, 126 blog posts, 84 videos and
a browsable campus — with the map that tells you which of them is worth your
ten minutes. The [short version](../README.md) is on the profile page; this is
all of it.

Most of this is one of three long projects, so if you read nothing else, read
the three paragraphs under [The through-lines](#the-through-lines).

> "Somebody who lands on the COR24 emulator has no way to discover the
> microkernel that runs on it, the assembler that targets it, or the 1802 work
> that rhymes with it. The connections exist. They just live in my head."
> — [Personal Software #11](https://blog.softwarewrighter.com/2026/09/12/software-wrighter-research-campus/)
>
> This repository is where they stop living only there.

Nothing here is a wrapper. If a repository says it emulates a CPU, the CPU is
in the repository; if it says it trains a model, the training loop is in the
repository. That is the whole editorial policy.

---

## If you only click once

| | Why this one |
|---|---|
| **[cor24-rs](https://github.com/sw-embed/cor24-rs)** | The MakerLisp COR24, a 24-bit RISC for FPGAs, emulated in Rust and running in your browser. The rest of the COR24 work hangs off it. |
| **[moe-microscope](https://github.com/sw-ml-study/moe-microscope)** | A mixture-of-experts model small enough that every routing decision is visible. Built from scratch; no framework. |
| **[ibm-1130-rs](https://github.com/sw-comp-history/ibm-1130-rs)** | A 1965 IBM 1130 with working console lights, keypunch and printer, in WebAssembly. |
| **[rlm-project](https://github.com/softwarewrighter/rlm-project)** | The most-starred thing here, and the best entry point to the language-model experiments. |
| **[sw-mlpl](https://github.com/sw-ml-study/sw-mlpl)** | A small language for writing machine learning you can actually read. |
| **[sw-campus](https://github.com/software-wrighter-lab/sw-campus)** | The guided tour: exhibits, wings, and live demos you can run without installing anything. |

## By topic

Ten pages, and each of the 246 appears on exactly one of them. The counts are
of repositories I wrote — public, and not forks. Forks and private work are
excluded everywhere except the totals in
[organisations](organizations.md), which match what GitHub shows.

| Topic | Repos | What it is |
|---|---:|---|
| [COR24: one CPU, a dozen languages](cor24.md) | 58 | One 24-bit RISC machine, reached from assembler, C, Pascal, Forth, Lisp, APL, Prolog, Smalltalk, SNOBOL4, RPG II, FORTRAN and OCaml — most with a browser demo. |
| [Machine learning, from scratch](machine-learning.md) | 47 | Models, training loops and a teaching language, all small enough to read. |
| [Agents, and the tools that keep them honest](agents-and-dev-tools.md) | 28 | An agent that cannot skip a step, a checklist that fails a build, an installer that refuses a stale binary. |
| [Apps and utilities](apps-and-utilities.md) | 24 | Working software that solves one problem each. |
| [Languages, compilers and instruction sets](languages-and-compilers.md) | 21 | The reusable IR, ISA and codegen machinery, plus language designs of my own. |
| [Games and graphics](games-and-graphics.md) | 19 | Vector arcade hardware on wgpu, finished small games, visual experiments. |
| [Historic machines, emulated](historic-machines.md) | 18 | IBM 1130, IBM 390, RCA 1802 — emulator plus the toolchain you would have needed. |
| [Audio, video and speech pipelines](media-pipelines.md) | 13 | The production side of the blog and the videos. |
| [Rust in the browser](browser-and-wasm.md) | 8 | WebAssembly, Yew, and the same scene rendered six ways to compare platforms. |
| [Embedded and hardware](embedded-and-hardware.md) | 4 | FPGA soft CPUs, an ESP32 carrier, bench instruments over SCPI. |

Also: [the 15 organisations](organizations.md) and what each is for;
[how to read a repository name](conventions.md) — the names are a code,
and once you know it, `tf24a` and `web-tml24c` stop being noise; and
[what is in flight](in-flight.md) — what started in `softwarewrighter`,
what has moved to an organisation, and which copy is the live one when there
are two.

## The through-lines

**One CPU, approached from every direction.** COR24 is MakerLisp's 24-bit RISC
for FPGAs. I did not design it; I adopted it, and then built the world around
it. There is an emulator, an assembler, a monitor, a
debugger, a tiny operating system, an FPGA soft-CPU target — and then a dozen
languages hosted on it, each one implemented in a *different* host language on
purpose: Tiny C in Rust, Pascal in C, Forth in assembler, Macro Lisp in C,
with APL, Prolog, Smalltalk, SNOBOL4, RPG II, FORTRAN, OCaml and BASIC
alongside. Most have a Yew/WASM front end, so you can run them from a link
instead of a checkout. It is a compiler-construction course with no textbook.

**Real machines, brought back.** The IBM 1130, the IBM 390 and the RCA 1802
are emulated in Rust to the level of console lamps and card hoppers, each with
its own assembler, code generator and ISA model rather than a shared shortcut.
The 1130 in particular is a complete 1965 ecosystem: keypunch, printer,
peripherals, and an assembly game to learn it with.

**Machine learning I can see all of.** Everything in this group is built from
scratch and kept small on purpose: a mixture-of-experts microscope where you
can watch the router choose, a neural net in Rust with no dependencies, a
typed decision model of 33,065 parameters, and sw-MLPL, a language for writing
the maths so it reads like the paper. Where a measurement disappointed, the
repository says so — a negative result that is honestly measured is a result.

## The writing, and the tour

The code is half of it. The other half is
[the blog](https://blog.softwarewrighter.com) — 126 posts, mostly walking
through the work above while it was being built — and 84 videos.
[The campus](https://software-wrighter-lab.github.io/sw-campus/) is the guided
version: wings and exhibits with the live demos embedded, so a visitor can
click rather than clone.

| | Repository |
|---|---|
| The blog | [software-wrighter-lab/blog](https://github.com/software-wrighter-lab/blog) |
| The campus | [software-wrighter-lab/sw-campus](https://github.com/software-wrighter-lab/sw-campus) |
| The index behind both | [software-wrighter-lab/sw-atlas](https://github.com/software-wrighter-lab/sw-atlas) |
| The lab's site | [software-wrighter-lab.github.io](https://github.com/software-wrighter-lab/software-wrighter-lab.github.io) |

## Honest status

Not all of these are finished, and the ones that are not say so. A
repository here is in one of four states, and the index in
[sw-atlas](https://github.com/software-wrighter-lab/sw-atlas) records which:

- **Finished** — done, and not expected to change.
- **Working** — there is a live demo or a runnable binary.
- **Early** — the source is real, nothing is runnable yet.
- **Planned** — a placeholder with a stated intent.

The `demo-*` repositories are a separate idea rather than a state: each was
built to learn one thing and then left where it landed, which is the point of
them, not a defect in them.

Forks are excluded from every count above, except the nine I have written
about, which appear beside the work that cites them. Counting them and my
private work, the 15 accounts hold more than this index shows; 247 public
repositories are mine, and the index lists 246 of them because it does not
index itself.

## How this page stays true

This index is generated, not maintained by hand. `sw-atlas` already holds one
semantic index over every public artifact — repositories, posts, videos, demos
and campus exhibits, with their concepts and relations — and this README and
the pages under `docs/` are rendered from it. That is why the counts in the
tables agree with each other: if they ever stop agreeing, the generator is
broken and a build fails.

<sub>Counts from the GitHub API, read live on 2026-09-26, for the 15 accounts
listed in [organisations](organizations.md). Regenerated, not
hand-counted.</sub>
