# In flight

Work here starts in [softwarewrighter](https://github.com/softwarewrighter) and
graduates to an organization once it is clearly one thing. This page is the
ledger of that traffic, so a visitor who finds two copies of a repository knows
which one is alive.

Everything below is read from the GitHub API: names, descriptions, push dates,
and each fork's parent -- because GitHub's fork flag says which button was
pressed, not who wrote the code. Nothing is read from my machine, so every
claim here is one a visitor can check.

## Two copies of the same work

Work moved between accounts by forking, so both copies survive and GitHub
marks the newer one as the fork. Ten pairs. Last-push dates are the only
public evidence of which copy is still worked on, so that is what the table
shows -- and in two pairs the copy left behind is the newer one, which is a
real question rather than an oversight. The copy still being pushed is in
bold.

| Work | One copy | The other |
|---|---|---|
| Rust library for CLI common/shared code | **[sw-cli-tools](https://github.com/sw-cli-tools/sw-cli) (2025-11-24)** | [softwarewrighter](https://github.com/softwarewrighter/sw-cli) (2025-11-24) |
| Pascal for COR24 in C | **[sw-embed](https://github.com/sw-embed/sw-cor24-pascal) (2026-05-25)** | [softwarewrighter](https://github.com/softwarewrighter/p24c) (2026-03-29) |
| p-code Virtual Machine for COR24 written in Assembler | **[sw-embed](https://github.com/sw-embed/sw-cor24-pcode) (2026-05-08)** | [softwarewrighter](https://github.com/softwarewrighter/pv24a) (2026-03-29) |
| Web UI Debugger for p-code VM on COR24, in Rust | **[sw-embed](https://github.com/sw-embed/web-sw-cor24-pcode) (2026-06-16)** | [softwarewrighter](https://github.com/softwarewrighter/web-dv24r) (2026-03-28) |
| A Proof of Concept game that provides an MCP server for AI Agent t | **[sw-game-dev](https://github.com/sw-game-dev/game-mcp-poc) (2025-11-21)** | [softwarewrighter](https://github.com/softwarewrighter/game-mcp-poc) (2025-11-20) |
| Rust CLI "personal software" tool to rank wav files from "best" to | **[sw-music-tools](https://github.com/sw-music-tools/rank-wav-rs) (2026-03-07)** | [sw-cli-tools](https://github.com/sw-cli-tools/rank-wav-rs) (2026-03-07) |
| Rust CLI for AI Coding Agents to check if a project conforms to th | **[sw-vibe-coding](https://github.com/sw-vibe-coding/sw-checklist) (2026-06-12)** | [softwarewrighter](https://github.com/softwarewrighter/sw-checklist) (2026-02-11) |
| A CLI tool to generate documents proactively for coding agents to  | [sw-vibe-coding](https://github.com/sw-vibe-coding/sw-init) (2025-11-27) | **[softwarewrighter](https://github.com/softwarewrighter/proact) (2026-05-21)** |
| Rust CLI to install a Rust release binary (or debug binary) in a l | [sw-vibe-coding](https://github.com/sw-vibe-coding/sw-install) (2025-12-27) | **[softwarewrighter](https://github.com/softwarewrighter/sw-install) (2026-03-22)** |
| Rust CLI to ensure markdown files can be displayed properly | **[sw-vibe-coding](https://github.com/sw-vibe-coding/sw-markdown-checker) (2026-01-09)** | [softwarewrighter](https://github.com/softwarewrighter/markdown-checker) (2025-11-22) |

Where the names differ the pair is easy to miss: `sw-cor24-pascal` is `p24c`,
`sw-cor24-pcode` is `pv24a`, `web-sw-cor24-pcode` is `web-dv24r`,
`sw-markdown-checker` is `markdown-checker`, and `sw-init` is `proact`. The
first version of this page looked only for repositories with the same name,
and so found half of them.

One fork is not a duplicate at all:
[sw-cor24-x-assembler](https://github.com/sw-embed/sw-cor24-x-assembler) began
as a fork of [cor24-rs](https://github.com/sw-embed/cor24-rs) and became a
different program -- a cross-assembler library rather than an emulator -- so it
counts as its own work.

## Carried forward from an earlier account

Three repositories continue work from
[wrightmikea](https://github.com/wrightmikea), an earlier personal account
holding 45 repositories of mine that is no longer actively managed and is not
indexed here. The copy in these accounts is the one that counts:

| Continued here | From |
|---|---|
| [softwarewrighter/emacs-ai-study-group](https://github.com/softwarewrighter/emacs-ai-study-group) — for sharing documents with the Emacs AI Study Group disc | [wrightmikea/emacs-ai-study-group](https://github.com/wrightmikea/emacs-ai-study-group) |
| [softwarewrighter/viz-hrm-ft](https://github.com/softwarewrighter/viz-hrm-ft) — React app to Visualize simulated Hierarchical Reasoning  | [wrightmikea/viz-hrm-ft](https://github.com/wrightmikea/viz-hrm-ft) |
| [sw-fun/tt-rs](https://github.com/sw-fun/tt-rs) — Yew/Rust/WASM reimagining of ToonTalk web implementation | [wrightmikea/tt-rs](https://github.com/wrightmikea/tt-rs) |

Moved *within* the COR24 work the same way, from an experiment to its settled
home in [sw-embed](https://github.com/sw-embed). Each description names its
ancestor, which is the only trail a fork leaves:

| Settled | Grew out of |
|---|---|
| [sw-cor24-emulator](https://github.com/sw-embed/sw-cor24-emulator) | [cor24-rs](https://github.com/sw-embed/cor24-rs), trimmed |
| [sw-cor24-x-tinyc](https://github.com/sw-embed/sw-cor24-x-tinyc) | [tc24r](https://github.com/sw-vibe-coding/tc24r) |
| [sw-cor24-macrolisp](https://github.com/sw-embed/sw-cor24-macrolisp) | [tml24c](https://github.com/sw-vibe-coding/tml24c) |
| [web-sw-cor24-forth](https://github.com/sw-embed/web-sw-cor24-forth) | [web-tf24a](https://github.com/sw-vibe-coding/web-tf24a) |

## Queued to move

Still in `softwarewrighter`, and all of it belongs somewhere more specific.
Listed so the intent is public. A transfer redirects, so the links here will
keep working after a move.

### → `sw-embed`

The COR24 machine and its languages.

| Repository | What it is |
|---|---|
| [cc24](https://github.com/softwarewrighter/cc24) | C-compiler for COR24 ISA |
| [p24c](https://github.com/softwarewrighter/p24c) | Pascal for COR24 in C |
| [pa24r](https://github.com/softwarewrighter/pa24r) | p-code assembler for COR24 in Rust |
| [pl24r](https://github.com/softwarewrighter/pl24r) | P-code Linker for COR24 in Rust |
| [pr24p](https://github.com/softwarewrighter/pr24p) | Pascal Runtime for COR24 written in Pascal (dogfooding) |
| [pv24a](https://github.com/softwarewrighter/pv24a) | p-code Virtual Machine for COR24 written in Assembler |
| [sw-co24-yocto-ed](https://github.com/softwarewrighter/sw-co24-yocto-ed) | _no description_ |
| [web-dv24r](https://github.com/softwarewrighter/web-dv24r) | Web UI Debugger for p-code VM on COR24, in Rust |
| [web-p24c](https://github.com/softwarewrighter/web-p24c) | Web UI for Running Pascal Demos in the browser |

### → `sw-ml-study`

Machine learning built from scratch.

| Repository | What it is |
|---|---|
| [ai-stack](https://github.com/softwarewrighter/ai-stack) | Rust AI stack |
| [babyai-rs](https://github.com/softwarewrighter/babyai-rs) | Yew/Rust application for ML study |
| [billion-llm](https://github.com/softwarewrighter/billion-llm) | comparison of LLMs in the ~1B parameters range |
| [efficient-llm](https://github.com/softwarewrighter/efficient-llm) | demo of frontier |
| [engram-poc](https://github.com/softwarewrighter/engram-poc) | implementations demonstrating Deepseek's Engram paper |
| [engramish-rs](https://github.com/softwarewrighter/engramish-rs) | A Rust demo of a Deepseek Engram-inspired external cache |
| [local-llm-loop](https://github.com/softwarewrighter/local-llm-loop) | A Rust CLI that uses a high level local LLM to manage low level LLM tool using calls to achieve a goal. |
| [mHC-poc](https://github.com/softwarewrighter/mHC-poc) | explain/demo mHC paper using Apple Silicon and Nvidia GPUs |
| [many-eyes-learning](https://github.com/softwarewrighter/many-eyes-learning) | Structured exploration for better learning under sparse rewards. |
| [micro-rlm-lab-py](https://github.com/softwarewrighter/micro-rlm-lab-py) | An executable-design proof-of-concept toy RLM sandbox |
| [microgpt-mlpl](https://github.com/softwarewrighter/microgpt-mlpl) | sw-MLPL reimplementation of Karpathy's microgpt.py and my microgpt-rs |
| [microgpt-rs](https://github.com/softwarewrighter/microgpt-rs) | Karpathy-microgpt.py inspired Rust CPU, MLX Apple GPU, and CUDA Nvidia GPU PoC |
| [mlplunit](https://github.com/softwarewrighter/mlplunit) | a JUNIT-inspired unit test framework for sw-MLPL |
| [multi-hop-reasoning](https://github.com/softwarewrighter/multi-hop-reasoning) | Proof-of-concept for recent Princeton paper on multi-hop-reasoning |
| [pocket-llm](https://github.com/softwarewrighter/pocket-llm) | demonstrating offline LLM usage on an Android smartphone |
| [rag-demo](https://github.com/softwarewrighter/rag-demo) | Rust demo of RAG using Qdrant |
| [rlm-project](https://github.com/softwarewrighter/rlm-project) | implementing MIT RLM concepts in Rust using DSL, WASM, CLI, and recursive LLM calls |
| [train-trm](https://github.com/softwarewrighter/train-trm) | Yew/Rust/WASM/CLI that implement Tiny Recursive Model training |

### → `sw-cli-tools`

One job, one command.

| Repository | What it is |
|---|---|
| [cli-gen](https://github.com/softwarewrighter/cli-gen) | Rust CLI and Yew web ui tool to generate CLI skeletons |
| [guardian-cli](https://github.com/softwarewrighter/guardian-cli) | A tool that uses an LLM to enforce process/architecture during the use of an AI Coding agent |
| [json2toon](https://github.com/softwarewrighter/json2toon) | Rust CLI to convert JSON to TOON (Token Oriented Object Notation) |
| [label-it](https://github.com/softwarewrighter/label-it) | Rust CLI to generate a label to drag around the screen when recording videos |
| [markdown-checker](https://github.com/softwarewrighter/markdown-checker) | Rust CLI to ensure markdown files can be displayed properly |
| [modularizer](https://github.com/softwarewrighter/modularizer) | Rust AI tool to refactor projects to be more modular, follow conventions, loosen coupling, use patterns |
| [pdf2md](https://github.com/softwarewrighter/pdf2md) | Rust CLI to extract text from a PDF to create a similar markdown file. |
| [wordcloud](https://github.com/softwarewrighter/wordcloud) | Rust CLI to generate wordcloud images |

### → `sw-video-tools / sw-music-tools`

Media production.

| Repository | What it is |
|---|---|
| [alltalk-client-rs](https://github.com/softwarewrighter/alltalk-client-rs) | Rust CLI (w/Yew/WASM) client for Alltalk_tts to generate video narration and podcast conversations |
| [hybrid-vid](https://github.com/softwarewrighter/hybrid-vid) | Rust video processing CLI and Web tools |
| [midi-cli-rs](https://github.com/softwarewrighter/midi-cli-rs) | Audio tool for AI coding agent use |
| [musetalk-client-rs](https://github.com/softwarewrighter/musetalk-client-rs) | Rust CLI for lip syncing videos |
| [music-pipe-rs](https://github.com/softwarewrighter/music-pipe-rs) | music pipeline in Rust |
| [open-tts-rs](https://github.com/softwarewrighter/open-tts-rs) | Rust tool for using different Open TTS models. |
| [podcast-gen](https://github.com/softwarewrighter/podcast-gen) | Rust CLI (Yew/WASM Web UI) tool for managing other tools to create dialog and render to audio file |
| [text-to-sfx-gen](https://github.com/softwarewrighter/text-to-sfx-gen) | Demo using an AI agent to generate code that generates sound effects |
| [tts-infra-dev](https://github.com/softwarewrighter/tts-infra-dev) | Scenario-driven TTS infrastructure development project (Rust Yew/WASM, CLI, scripting, UI, tools) |
| [video_workflow_rs](https://github.com/softwarewrighter/video_workflow_rs) | A Rust Framework for delegating video production tasks to AI Agents |
| [yt-rs](https://github.com/softwarewrighter/yt-rs) | YouTube video preparation editor for OBS screen captures with narration using AI Agents |

### → `sw-game-dev / sw-fun`

Games and playable things.

| Repository | What it is |
|---|---|
| [godot-poc-rs](https://github.com/softwarewrighter/godot-poc-rs) | Godot game engine Proof of Concept using Rust |
| [n_body](https://github.com/softwarewrighter/n_body) | Rust/WASM n body simulation backend and frontend |
| [rts_mock](https://github.com/softwarewrighter/rts_mock) | A Rust/WASM sandbox for trying RTS game UI ideas |
| [rts_monitor](https://github.com/softwarewrighter/rts_monitor) | Rust/WASM RTS-like system monitor |
| [shut_the_box](https://github.com/softwarewrighter/shut_the_box) | Rust/WASM/three.js simulation of an old board game |
| [speed-kings](https://github.com/softwarewrighter/speed-kings) | Rust tooling to compare different hardware used by inference providers and local LLMs |
| [xmas-rs](https://github.com/softwarewrighter/xmas-rs) | lights |

### → `a vectorcade org, or sw-game-dev`

The vector-arcade project, six repositories and a shared crate.

| Repository | What it is |
|---|---|
| [vectorcade-fonts](https://github.com/softwarewrighter/vectorcade-fonts) | Vector fonts library for Vector Arcade platform |
| [vectorcade-games](https://github.com/softwarewrighter/vectorcade-games) | Game implementations for Vector Arcade platform |
| [vectorcade-meta](https://github.com/softwarewrighter/vectorcade-meta) | Meta repository for Vector Arcade platform |
| [vectorcade-render-wgpu](https://github.com/softwarewrighter/vectorcade-render-wgpu) | WGPU renderer for Vector Arcade platform |
| [vectorcade-shared](https://github.com/softwarewrighter/vectorcade-shared) | Shared library for Vector Arcade platform |
| [vectorcade-web-yew](https://github.com/softwarewrighter/vectorcade-web-yew) | Yew web shell for Vector Arcade platform |

## Staying in `softwarewrighter`

Some things have no better home and do not need one: one-off experiments, the
`try-*` evaluations, `demo-claude-mem`, `avoid-compaction`, `placeholder`. A
repository does not need an organization to be finished.

## How a move is done here

For anything that matters, **transfer**, do not fork-and-leave:

- A transfer moves stars, issues, forks and history, and GitHub redirects the
  old URL, including `git` remotes, so nothing that links to it breaks.
- A fork-and-leave produces the two-copies problem in the first table: the live
  copy is flagged a fork, automated indexes pick the abandoned one, and the
  only record of the relationship is a sentence in a description.
- If a fork-and-leave has already happened, archive the abandoned copy and put
  the live URL in its description. Archiving is reversible; deleting is not.

---

Back to [the index](index.md).
