# Wynand van Staden

Software developer who is enthusiastic about technology: how things work, why they
break, and how to fix them properly.

In my spare time I look for real bugs in open-source tools, reproduce them, and send
the fix upstream. It is the best way I have found to keep learning, because every
project has a different language, a different test setup and maintainers with their
own standards.

---

### Open-source contributions

**33 pull requests merged across 16 projects** · <sub>updated 22 October 2026</sub>

Bug fixes in projects I had not worked on before. Each one was reproduced before it was
fixed and checked against the project's own tests.

| Project | What I fixed | PR | Status |
|---|---|---|---|
| **[chunkhound](https://github.com/chunkhound/chunkhound)** · code search for AI agents · Python/Rust | Undefined names in two language parsers that broke lint and type checks | [#432](https://github.com/chunkhound/chunkhound/pull/432) | ✅ Merged |
| **[office365-rest-python-client](https://github.com/vgrem/office365-rest-python-client)** · Microsoft 365 client · Python | Apostrophes in SharePoint paths were escaped twice, so files could not be found | [#1053](https://github.com/vgrem/office365-rest-python-client/pull/1053) | ✅ Merged |
| **[collie](https://github.com/AltanS/collie)** · phone UI for terminal AI agents · TypeScript | tmux listings failed to parse with no UTF-8 locale, showing a healthy host as down | [#360](https://github.com/AltanS/collie/pull/360) | ✅ Shipped in v1.17.0 |
| **[rust-decimal](https://github.com/paupino/rust-decimal)** · decimal numbers for Rust | Exact parsing rejected a valid digit separator after the 28th decimal place | [#868](https://github.com/paupino/rust-decimal/pull/868) | ✅ Merged |
| **[smolvm](https://github.com/smol-machines/smolvm)** · micro-VMs from container images · Rust | Packed images could not be extracted on Windows because of an invalid path for directory entries | [#1617](https://github.com/smol-machines/smolvm/pull/1617) | ✅ Merged |
| **[snip](https://github.com/edouard-claude/snip)** · output trimming for coding agents · Go | The Pi agent hook produced a Windows path that bash could not run | [#197](https://github.com/edouard-claude/snip/pull/197) | ✅ Merged |
| **[doorstop](https://github.com/doorstop-dev/doorstop)** · requirements management · Python | The documented example server adapter had a syntax error | [#849](https://github.com/doorstop-dev/doorstop/pull/849) | ✅ Merged |
| **[chunkhound](https://github.com/chunkhound/chunkhound)** · Rust pipeline | Re-indexing an unchanged project needlessly rebuilt the vector index | [#433](https://github.com/chunkhound/chunkhound/pull/433) | ✅ Merged |
| **[flyline](https://github.com/HalFrgrd/flyline)** · Bash line editor · Rust | `${VAR}` was not highlighted as a variable the way `$VAR` is | [#1030](https://github.com/HalFrgrd/flyline/pull/1030) | ✅ Merged |
| **[atlas](https://github.com/pacifio/atlas)** · desktop app for coding agents · Rust/Tauri | Unit tests could not start on Windows because the test binary had no application manifest | [#390](https://github.com/pacifio/atlas/pull/390) | ✅ Merged |
| **[kloset](https://github.com/PlakarKorp/kloset)** · storage engine of the plakar backup tool · Go | Maintenance aborted on Windows backups whose drive letter was recorded in lowercase | [#567](https://github.com/PlakarKorp/kloset/pull/567) | ✅ Merged |
| **[KAPLAY](https://github.com/kaplayjs/kaplay)** · 2D game library for the browser · TypeScript | Colliding bodies ignored each other's mass and velocity, so collisions did not conserve momentum | [#1174](https://github.com/kaplayjs/kaplay/pull/1174) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · local stand-in for SaaS APIs (Slack, Jira, HubSpot …) · Python | The HubSpot API accepted `NaN` and `Infinity` in request bodies where the real service refuses them | [#640](https://github.com/brekkylab/backlot/pull/640) | ✅ Merged |
| **[chunkhound](https://github.com/chunkhound/chunkhound)** · documentation | Follow-up requested in review: descriptions still said the vector index is always rebuilt | [#438](https://github.com/chunkhound/chunkhound/pull/438) | ✅ Merged |
| **[scaleway-cli](https://github.com/scaleway/scaleway-cli)** · official CLI for the Scaleway cloud · Go | Generated command docs broke their argument tables when a description contained a `|` | [#6359](https://github.com/scaleway/scaleway-cli/pull/6359) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Google Docs | A document read was missing the `commentsViewMode` field the real API always sends | [#744](https://github.com/brekkylab/backlot/pull/744) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Gmail search | `newer:` and `older:` searches returned nothing instead of acting like `after:` and `before:` | [#745](https://github.com/brekkylab/backlot/pull/745) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · HubSpot | Three numeric object-type ids the real API accepts were refused as unknown | [#746](https://github.com/brekkylab/backlot/pull/746) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Gmail search | A `+` inside a search value (`cc:lena+update`) was read as part of the value instead of starting a new search term | [#772](https://github.com/brekkylab/backlot/pull/772) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Slack | A negative or very large `limit` dropped the last item or crashed, where the real API answers per method | [#773](https://github.com/brekkylab/backlot/pull/773) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Gmail search | `after:`/`before:` skipped dates they could not read and misread month-first, quoted and negated dates | [#782](https://github.com/brekkylab/backlot/pull/782) | ✅ Merged |
| **[flyline](https://github.com/HalFrgrd/flyline)** · follow-up | The braces of `${VAR}` are now coloured as part of the variable, as the reporter asked | [#1036](https://github.com/HalFrgrd/flyline/pull/1036) | ✅ Merged |
| **[flyline](https://github.com/HalFrgrd/flyline)** · styles | `set-style inline-suggestion` had no effect on the suggested text | [#1039](https://github.com/HalFrgrd/flyline/pull/1039) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Google Drive | A folder or file the caller does not own reported `canShare: true`, where real Drive says false | [#802](https://github.com/brekkylab/backlot/pull/802) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Gmail search | `-from:bob` and `from:-bob` were not read as "not from bob" | [#805](https://github.com/brekkylab/backlot/pull/805) | ✅ Merged |
| **[deja-vu](https://github.com/vshulcz/deja-vu)** · help text | `tests`, `recap` and `secrets` help now say the `--limit` default and that 0 shows all | [#5290](https://github.com/vshulcz/deja-vu/pull/5290) | ✅ Merged |
| **[repowise](https://github.com/repowise-dev/repowise)** · codebase intelligence for AI agents · Python | The refactoring planner proposed extracting cut-off function signatures and `...` stubs as shared helpers | [#3950](https://github.com/repowise-dev/repowise/pull/3950) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Gmail search | An empty `subject:`, `label:` or `in:` before another operator swallowed it instead of being dropped | [#858](https://github.com/brekkylab/backlot/pull/858) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Gmail search | `-label:inbox`, `NOT from:bob` and `-(from:bob)` were not read as negations | [#890](https://github.com/brekkylab/backlot/pull/890) | ✅ Merged |
| **[Backlot](https://github.com/brekkylab/backlot)** · Linear | A page reported more results in the direction it was not asked for | [#919](https://github.com/brekkylab/backlot/pull/919) | ✅ Merged |
| **[snip](https://github.com/edouard-claude/snip)** · tests | Tests wrote to the real home folder on Windows because `USERPROFILE` was not redirected with `HOME` | [#199](https://github.com/edouard-claude/snip/pull/199) | ✅ Merged |
| **[pyscn](https://github.com/ludo-technologies/pyscn)** · Python code quality analyser · Go | Conditional expressions (`a if c else b`) added nothing to McCabe complexity | [#853](https://github.com/ludo-technologies/pyscn/pull/853) | ✅ Merged |
| **[deja-vu](https://github.com/vshulcz/deja-vu)** · session recall for coding agents · Go | `deja promote` given two ids silently promoted the second, skipping a mistyped first | [#5099](https://github.com/vshulcz/deja-vu/pull/5099) | ✅ Merged |

[All my pull requests →](https://github.com/pulls?q=is%3Apr+author%3AWynandVStaden+-user%3AWynandVStaden)
