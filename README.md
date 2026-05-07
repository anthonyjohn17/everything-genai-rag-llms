# Everything GenAI, RAG & OpenClaw (`everything-genai-rag-openclaw`)

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

Personal **reference and portfolio monorepo** by [John Anthony](https://github.com/anthonyjohn17). It groups curated links, patterns, and tooling around **generative AI**, **retrieval-augmented generation (RAG)**, **OpenAI Whisper**, and the **OpenClaw** agent ecosystem—organized so you can clone once and browse offline or point stakeholders at a single GitHub home.

> **Note:** This is a curated collection and documentation set, not a single installable application. Jump to the section that matches what you need; each subfolder has its own focus and license notes where applicable.

---

## Contents of this repo

| Folder | What it is |
|--------|-------------|
| [**everything-gen-ai/**](everything-gen-ai/) | Broad [Awesome List](https://github.com/sindresorhus/awesome)-style catalog of generative AI models, apps, dev tools, and learning material—plus a “Discoveries” feed for newer projects. |
| [**everything-rag/**](everything-rag/) | Structured map of RAG architecture, frameworks, evaluation, databases, and production practices. |
| [**everything-openai-whisper/**](everything-openai-whisper/) | Whisper-related models, APIs, apps, and community ports. |
| [**everything-openclaw/**](everything-openclaw/README.md) | OpenClaw bundle—see the [**index**](everything-openclaw/README.md): [**explain-openclaw/**](everything-openclaw/explain-openclaw/) guides, [**openclaw-agents/**](everything-openclaw/openclaw-agents/) templates, [**openclaw-skills/**](everything-openclaw/openclaw-skills/), [**openclaw-usecases/**](everything-openclaw/openclaw-usecases/), [**openclaw-mission-control/**](everything-openclaw/openclaw-mission-control/). |

---

## Why this exists

- **One clone for research** — Useful when comparing stacks (LLM APIs, RAG vector stores, agent patterns) without juggling dozens of bookmarks.
- **Portfolio signal** — Shows breadth across modern AI engineering: models, grounding/RAG, speech, and agent operations.
- **OpenClaw depth** — The `explain-openclaw` tree is a serious security-and-operations companion to upstream OpenClaw docs; agent templates under `openclaw-agents` are copy-paste starting points.

---

## Quick start

```bash
git clone https://github.com/anthonyjohn17/everything-genai-rag-openclaw.git
cd everything-genai-rag-openclaw
```

Then open the `README.md` inside the area you care about (for example `everything-rag/README.md`).

---

## Contributing

See [**CONTRIBUTING.md**](CONTRIBUTING.md) for how to propose additions. List-specific rules for the generative AI index live in [**everything-gen-ai/CONTRIBUTING.md**](everything-gen-ai/CONTRIBUTING.md).

---

## Licenses and attribution

- **`everything-gen-ai/`** and **`everything-rag/`** include **CC0 1.0** material (see each folder’s `LICENSE`). You can reuse those lists broadly; citing the repo is appreciated but not required by CC0.
- **Upstream projects** linked here keep their own licenses; this repo does not claim ownership of third-party code or trademarks.
- **OpenClaw** is an independent ecosystem; documentation here may summarize or analyze upstream behavior—always verify against [official OpenClaw docs](https://docs.openclaw.ai/) for installation and security.

---

## Publish to GitHub

After you create the repository `everything-genai-rag-openclaw` under your account:

```bash
git remote add origin https://github.com/anthonyjohn17/everything-genai-rag-openclaw.git
git add -A
git commit -m "Initial import: GenAI, RAG, Whisper, and OpenClaw reference monorepo"
git push -u origin main
```

GitHub Actions in [`.github/workflows/`](.github/workflows/) run **awesome-lint** on the generative AI list and **awesome_bot** link checks for `README.md` and `DISCOVERIES.md` under `everything-gen-ai/`.

---

## Maintainer

**[John Anthony](https://github.com/anthonyjohn17)** — personal portfolio and working notes, merged and maintained in this monorepo.
