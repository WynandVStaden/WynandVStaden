# Wynand van Staden

Software developer who is enthusiastic about technology: how things work, why they
break, and how to fix them properly.

In my spare time I look for real bugs in open-source tools, reproduce them, and send
the fix upstream. It is the best way I have found to keep learning, because every
project has a different language, a different test setup and maintainers with their
own standards.

---

### Open-source contributions

**11 pull requests across 10 projects** · 3 landed · 8 in review · <sub>updated 8 October 2026</sub>

Bug fixes in projects I had not worked on before. Each one was reproduced before it was
fixed and checked against the project's own tests.

| Project | What I fixed | PR | Status |
|---|---|---|---|
| **[chunkhound](https://github.com/chunkhound/chunkhound)** · code search for AI agents · Python/Rust | Undefined names in two language parsers that broke lint and type checks | [#432](https://github.com/chunkhound/chunkhound/pull/432) | ✅ Merged |
| **[office365-rest-python-client](https://github.com/vgrem/office365-rest-python-client)** · Microsoft 365 client · Python | Apostrophes in SharePoint paths were escaped twice, so files could not be found | [#1053](https://github.com/vgrem/office365-rest-python-client/pull/1053) | ✅ Merged |
| **[collie](https://github.com/AltanS/collie)** · phone UI for terminal AI agents · TypeScript | tmux listings failed to parse with no UTF-8 locale, showing a healthy host as down | [#360](https://github.com/AltanS/collie/pull/360) | ✅ Shipped in v1.17.0 |
| **[chunkhound](https://github.com/chunkhound/chunkhound)** · Rust pipeline | Re-indexing an unchanged project needlessly rebuilt the vector index | [#433](https://github.com/chunkhound/chunkhound/pull/433) | 🔄 In review |
| **[scaleway-cli](https://github.com/scaleway/scaleway-cli)** · Scaleway's official CLI · Go | Doc generator did not escape `\|`, breaking tables on three command pages | [#6359](https://github.com/scaleway/scaleway-cli/pull/6359) | 🔄 In review |
| **[rust-decimal](https://github.com/paupino/rust-decimal)** · decimal numbers for Rust | Exact parsing rejected a valid digit separator after the 28th decimal place | [#868](https://github.com/paupino/rust-decimal/pull/868) | 🔄 In review |
| **[webawesome](https://github.com/shoelace-style/webawesome)** · web components · TypeScript/CSS | Sprite-sheet icons rendered a 300px-wide box that stole clicks from neighbours | [#2920](https://github.com/shoelace-style/webawesome/pull/2920) | 🔄 In review |
| **[flyline](https://github.com/HalFrgrd/flyline)** · Bash line editor · Rust | `${VAR}` was not highlighted as a variable the way `$VAR` is | [#1030](https://github.com/HalFrgrd/flyline/pull/1030) | 🔄 In review |
| **[atlas](https://github.com/pacifio/atlas)** · desktop app for coding agents · Rust/Tauri | Unit tests could not start on Windows because the test binary had no application manifest | [#390](https://github.com/pacifio/atlas/pull/390) | 🔄 In review |
| **[smolvm](https://github.com/smol-machines/smolvm)** · micro-VMs from container images · Rust | Packed images could not be extracted on Windows because of an invalid path for directory entries | [#1617](https://github.com/smol-machines/smolvm/pull/1617) | 🔄 In review |
| **[doorstop](https://github.com/doorstop-dev/doorstop)** · requirements management · Python | The documented example server adapter had a syntax error | [#849](https://github.com/doorstop-dev/doorstop/pull/849) | 🔄 In review |

[All my pull requests →](https://github.com/pulls?q=is%3Apr+author%3AWynandVStaden+-user%3AWynandVStaden)

### What I work with

```
Languages   Python day to day; Go, Rust and TypeScript when a project calls for it
Interests   developer tooling, automation, trading systems, game development in Godot
Workflow    reproduce first, fix with a test, AI-assisted development, reading unfamiliar code
```

### Personal projects

- **[EventsTrader](https://github.com/WynandVStaden/EventsTrader)** — multi-strategy algorithmic trading suite in Python, with an LLM-driven signal judge and a FastAPI console to supervise it.
- **[aegis](https://github.com/WynandVStaden/aegis)** — a Godot space-colonization game for Android.
- **[elfray](https://github.com/WynandVStaden/elfray)** — Godot game project with custom shaders and voice systems.
