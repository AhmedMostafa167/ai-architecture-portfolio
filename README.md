# AI Architecture Portfolio

A working portfolio that documents the design of an AI system end to end:
framing the problem, choosing building blocks, recording decisions, and
presenting a final architecture.

## Scenario

> _TODO: Describe the system you are designing in 2–4 sentences._
> Who are the users? What problem does the AI solve for them? What does
> success look like?

## Assumptions

> _TODO: List the assumptions that shape the design._

- Scale: _e.g. requests per day, number of users_
- Data: _e.g. sources, sensitivity, residency requirements_
- Constraints: _e.g. budget, latency targets, compliance, team skills_

## How to read this repo

| Folder | What's inside | Start here |
|---|---|---|
| [`docs/`](docs/) | One file per session, in order (`01-framing.md`, `02-building-blocks.md`, ...) | [`docs/01-framing.md`](docs/01-framing.md) |
| [`diagrams/`](diagrams/) | Exported diagrams (`export/`, PNG/SVG) and their editable sources (`src/`) | [`diagrams/README.md`](diagrams/README.md) |
| [`adr/`](adr/) | Architecture Decision Records, one file per decision (`0001-model-hosting.md`, ...) | [`adr/README.md`](adr/README.md) |
| [`capstone/`](capstone/) | Final architecture document (PDF) and presentation slides | [`capstone/README.md`](capstone/README.md) |

Suggested reading order: **README → docs (in number order) → ADRs → capstone**.
Diagrams are referenced from the docs and ADRs where they're relevant.

## Repository layout

```text
ai-architecture-portfolio/
├── README.md        # scenario, assumptions, how to read the repo
├── docs/            # one file per session: 01-framing.md, 02-building-blocks.md ...
├── diagrams/        # exported PNG/SVG + source files
├── adr/             # one file per decision: 0001-model-hosting.md ...
└── capstone/        # final architecture PDF + slides
```
