# How to read a repository name

The names are a code. It is a compact one, and it was not written for
strangers — this page is the key.

## Prefixes

| Prefix | Means |
|---|---|
| `sw-` | Software Wrighter's own: a component meant to be depended on, not a throwaway. |
| `web-` | A browser front end for the thing after it, Rust compiled to WebAssembly with a Yew interface. `web-tc24r` is the browser UI for `tc24r`. |
| `demo-` | Built to learn or teach one idea. Small, readable, and not maintained after the lesson landed. |
| `try-` | An evaluation of somebody else's library, kept as a record of the verdict. |
| `hw-` | Hardware: a board, an FPGA target, a circuit. |
| `*-rs` | A Rust implementation, usually where a non-Rust one exists or existed. |
| `*-poc` | Proof of concept. It answered a question and stopped. |
| `*-live` | A hosting repository whose only job is to serve a stable demo of its sibling. |

## The COR24 language codes

COR24 is a 24-bit RISC machine of my own design. The languages hosted on it
are named `<language><24><host>`: what the language is, the machine, and the
language it is *implemented in*. The host letter is the interesting part,
because implementing the same target from different hosts is the exercise.

| Name | Reads as |
|---|---|
| `tc24r` | **T**iny **C** for COR**24**, in **R**ust |
| `tf24a` | **T**iny **F**orth for COR**24**, in **A**ssembler |
| `tml24c` | **T**iny **M**acro **L**isp for COR**24**, in **C** |
| `p24c` | **P**ascal for COR**24**, in **C** |
| `pa24r` | **P**-code **A**ssembler for COR**24**, in **R**ust |
| `pl24r` | **P**-code **L**inker for COR**24**, in **R**ust |
| `pv24a` | **P**-code **V**M for COR**24**, in **A**ssembler |
| `pr24p` | **P**ascal **R**untime for COR**24**, in **P**ascal (dogfooding) |
| `cc24` | **C** **c**ompiler for COR**24** |
| `dv24r` | **D**ebugger for the p-code **V**M, in **R**ust (as `web-dv24r`) |

So `web-tf24a` is: the browser debugger, for Tiny Forth, on COR24, written in
assembler. Once the code is visible the collection reads as what it is — one
machine approached from every direction.

The `sw-cor24-*` repositories in [sw-embed](https://github.com/sw-embed) are
the settled versions of the same work: several are explicitly trimmed or
forked from an experiment above, and the description of each says which.

## Where a demo lives

A repository whose name starts with `web-`, or which has a `*-live` sibling,
has something you can run without cloning. The
[campus](https://software-wrighter-lab.github.io/sw-campus/) collects the ones
worth showing a visitor; the rest are runnable but unguided.

---

Back to [the index](index.md).
