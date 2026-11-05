# SI-Thor

The heavy machinery. **SI-Thor** is the organisation for work that runs on
the Jetson AGX Thor — the fleet's back-room machine: a single-board
supercomputer (Blackwell GPU, sm_110) that hosts the perception engine,
the agent community's minds, and the low-precision research programme.

The pattern across everything here: measure it on the metal, publish the
numbers with the deficits, and let the tools that prove themselves
graduate — to the [curated shelf](https://github.com/si-ready) or into
production at [SuperInstance](https://github.com/SuperInstance).

## The index

**Perception** — [rolling-perception](https://github.com/SI-Thor/rolling-perception):
the rolling cascade engine (time-to-first-output 10.39× over batched,
measured), the Confluence stream platform, and the agent-community
architecture — one rolling percept of a shared world, agents drinking
from it at earned temporal resolutions, System-Two voices in their heads,
System Three a call away.

**Low precision** — [thor-fp4](https://github.com/SI-Thor/thor-fp4):
NVFP4 on Blackwell sm_110 — a shape-aware FP4 Linear for PyTorch, our own
CUTLASS kernels, PTQ/QAT, and an escalate-when-unsure cascade.
[ecology-thor](https://github.com/SI-Thor/ecology-thor): a purpose-built
cognitive ecology kernel in Rust — WHY-ledger plus attention auction,
bit-exact CUDA/PTX sweeps, unified-memory zero-copy.

**Worlds** — [builder-ide](https://github.com/SI-Thor/builder-ide) and
[thor-world](https://github.com/SI-Thor/thor-world): generated worlds and
the live wire between them and the people and agents who use them — an
MCP server, a Thor-native world stream, a browser viewer.
[infinigen-thor](https://github.com/SI-Thor/infinigen-thor): procedural
world generation on the Thor.

**Voice** — [skald](https://github.com/SI-Thor/skald): a read-aloud
system for the Thor — live TTS, a shared local voice daemon, an
article-to-podcast pipeline.

## The machine's other job

The Thor is also the agent community's home: the local minds
(Qwen3-Coder-30B as the standing System Two, looped models as refiners),
the budget governor that meters every mind-call, and the ledgers live
here, while the worlds themselves are served from lighter boxes and
humans join as players. The architecture is written up in
[rolling-perception/docs/ARCH-AGENT-COMMUNITY.md](https://github.com/SI-Thor/rolling-perception/blob/main/docs/ARCH-AGENT-COMMUNITY.md).

## Related

[SuperInstance](https://github.com/SuperInstance) — the whole picture ·
[si-ready](https://github.com/si-ready) — finished tools, curated ·
[SI-Marine](https://github.com/SI-Marine) — where Thor-class workloads go to sea
