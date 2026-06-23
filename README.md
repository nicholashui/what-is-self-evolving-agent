# What Is a Self-Evolving Agent?

A complete, research-backed book-production package on **self-evolving agents** — AI systems that continuously and autonomously improve their own prompts, memory, tools, workflows, and even source code.

The content is synthesized from 2025–2026 arXiv research, including the [Survey of Self-Evolving Agents (arXiv:2507.21046)](https://arxiv.org/abs/2507.21046), the [Darwin Gödel Machine (arXiv:2505.22954)](https://arxiv.org/abs/2505.22954), [Reflexion](https://arxiv.org/abs/2303.11366), [Voyager](https://arxiv.org/abs/2305.16291), and others (full citations inside each book).

## Contents

Everything lives under the [`book/`](book/) folder.

### Books

| File | Language | Description |
|------|----------|-------------|
| [`book/BOOK_EN.md`](book/BOOK_EN.md) | English | The full instructional book — 14 chapters + 5 appendices, first-principles theory, reproducible Python code, a complete DGM-style tutorial, evaluation, safety, and applications. |
| [`book/BOOK_EN_hk.md`](book/BOOK_EN_hk.md) | 繁體中文 | Faithful Traditional Chinese translation of the full book. |

### Diagrams ([`book/diagrams/`](book/diagrams/))

Optimized SVG architectural diagrams, referenced inline from the books:

- `01-system-architecture.svg` — overall self-evolving agent system architecture
- `02-evolution-loop.svg` — the closed-loop evolution data flow
- `03-taxonomy.svg` — the What × When × How taxonomy
- `04-dgm-population-loop.svg` — population-based (Darwin Gödel Machine) workflow
- `05-multi-agent-coevolution.svg` — multi-agent component interaction

### Narration Scripts

Clean, spoken-word YouTube narration scripts (no headings, tags, or production cues), derived from the English book, in three language versions:

| File | Language | Description |
|------|----------|-------------|
| [`book/BOOK_EN.script.txt`](book/BOOK_EN.script.txt) | English | Spoken narration of the full book, optimized for listening. |
| [`book/BOOK_EN.script_hk.txt`](book/BOOK_EN.script_hk.txt) | 繁體中文 | Traditional Chinese translation of the narration. |
| [`book/BOOK_EN.script_zh.txt`](book/BOOK_EN.script_zh.txt) | 普通话（简体） | Putonghua (Standard Mandarin) version in Simplified Chinese. |

## Production Pipeline

The files were produced as a sequential pipeline:

1. **Write** the English book → `book/BOOK_EN.md`
2. **Translate** to Traditional Chinese → `book/BOOK_EN_hk.md`
3. **Convert** the English book to a spoken narration script → `book/BOOK_EN.script.txt`
4. **Translate** the script to Traditional Chinese → `book/BOOK_EN.script_hk.txt`
5. **Convert** the Traditional Chinese script to Putonghua → `book/BOOK_EN.script_zh.txt`

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
