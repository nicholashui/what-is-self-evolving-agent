# What Is a Self-Evolving Agent?

A complete, research-backed book-production package on **self-evolving agents** — AI systems that continuously and autonomously improve their own prompts, memory, tools, workflows, and even source code.

The content is synthesized from 2025–2026 arXiv research, including the [Survey of Self-Evolving Agents (arXiv:2507.21046)](https://arxiv.org/abs/2507.21046), the [Darwin Gödel Machine (arXiv:2505.22954)](https://arxiv.org/abs/2505.22954), [Reflexion](https://arxiv.org/abs/2303.11366), [Voyager](https://arxiv.org/abs/2305.16291), and others (full citations inside each book).

## Contents

### Books

| File | Language | Description |
|------|----------|-------------|
| [`BOOK_EN.md`](BOOK_EN.md) | English | The full instructional book — 14 chapters + 5 appendices, first-principles theory, reproducible Python code, a complete DGM-style tutorial, evaluation, safety, and applications. |
| [`BOOK_ZH-TW.md`](BOOK_ZH-TW.md) | 繁體中文 | Faithful Traditional Chinese translation of the full book. |

### Diagrams ([`diagrams/`](diagrams/))

Optimized SVG architectural diagrams, referenced inline from the books:

- `01-system-architecture.svg` — overall self-evolving agent system architecture
- `02-evolution-loop.svg` — the closed-loop evolution data flow
- `03-taxonomy.svg` — the What × When × How taxonomy
- `04-dgm-population-loop.svg` — population-based (Darwin Gödel Machine) workflow
- `05-multi-agent-coevolution.svg` — multi-agent component interaction

### YouTube Narration Scripts ([`scripts/`](scripts/))

A 10-episode narration series derived from the English book, in three language versions:

| File | Language | Description |
|------|----------|-------------|
| [`scripts/youtube_scripts_en.md`](scripts/youtube_scripts_en.md) | English | Spoken-optimized scripts with on-screen / B-roll / pause cues. |
| [`scripts/youtube_scripts_zh-tw.md`](scripts/youtube_scripts_zh-tw.md) | 繁體中文 | Traditional Chinese narration scripts. |
| [`scripts/youtube_scripts_putonghua.md`](scripts/youtube_scripts_putonghua.md) | 普通话（简体） | Standard Mandarin (Putonghua) scripts in Simplified Chinese for mainland narration. |

## Reading Order

Start with [`BOOK_EN.md`](BOOK_EN.md) (or [`BOOK_ZH-TW.md`](BOOK_ZH-TW.md)). The book is self-contained and progresses from foundations → taxonomy → implementation → operations. The scripts condense the same material into a voice-over series for video production.

## Topics Covered

- First principles: the universal perceive → act → evaluate → evolve loop
- Taxonomy: **What** evolves, **When** it evolves, **How** it evolves
- Mechanisms: reward-based, imitation/bootstrapping, and population-based evolution
- A reproducible, sandboxed self-evolving coding agent tutorial (simplified Darwin Gödel Machine)
- Multi-agent co-evolution and framework integration
- Evaluation metrics, benchmarks, and continuous monitoring
- Safety, alignment, risks, and defense-in-depth mitigations

---

*Educational synthesis of publicly available research. Research content was paraphrased and summarized for licensing compliance; consult the linked primary arXiv sources for authoritative detail.*
