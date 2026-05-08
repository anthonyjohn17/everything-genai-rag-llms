# Everything GenAI, RAG & LLMs (`everything-genai-rag-llms`)

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

Personal **reference and portfolio monorepo** by [John Anthony](https://github.com/anthonyjohn17). It groups curated links, patterns, and tooling around **generative AI**, **retrieval-augmented generation (RAG)**, **OpenAI Whisper**, and **LLM APIs**—organized so you can clone once and browse offline or point stakeholders at a single GitHub home.

> **Note:** This is a curated collection and documentation set, not a single installable application. Jump to the section that matches what you need; each subfolder has its own focus and license notes where applicable.

---

## Contents of this repo

| Folder | What it is |
|--------|-------------|
| [**everything-gen-ai/**](everything-gen-ai/) | Broad [Awesome List](https://github.com/sindresorhus/awesome)-style catalog of generative AI models, apps, dev tools, and learning material—plus a “Discoveries” feed for newer projects. |
| [**everything-rag/**](everything-rag/) | Structured map of RAG architecture, frameworks, evaluation, databases, and production practices. |
| [**everything-openai-whisper/**](everything-openai-whisper/) | Whisper-related models, APIs, apps, and community ports. |
| [**everything-llm-apis/**](everything-llm-apis/) | Curated list of free and open LLM API providers, inference endpoints, and related tooling. |

---

## Why this exists

- **One clone for research** — Useful when comparing stacks (LLM APIs, RAG vector stores, agent patterns) without juggling dozens of bookmarks.
- **Portfolio signal** — Shows breadth across modern AI engineering: models, grounding/RAG, speech, and LLM API providers.
- **LLM API coverage** — The `everything-llm-apis` section tracks free and open inference endpoints so you can evaluate providers without a subscription.

---

## Quick start

```bash
git clone https://github.com/anthonyjohn17/everything-genai-rag-llms.git
cd everything-genai-rag-llms
```

Then open the `README.md` inside the area you care about (for example `everything-rag/README.md`).

---

## Contributing

See [**CONTRIBUTING.md**](CONTRIBUTING.md) for how to propose additions.

---

## Licenses and attribution

- **`everything-gen-ai/`** and **`everything-rag/`** include **CC0 1.0** material (see each folder’s `LICENSE`). You can reuse those lists broadly; citing the repo is appreciated but not required by CC0.
- **Upstream projects** linked here keep their own licenses; this repo does not claim ownership of third-party code or trademarks.

---

## Publish to GitHub

After you create the repository `everything-genai-rag-llms` under your account:

```bash
git remote add origin https://github.com/anthonyjohn17/everything-genai-rag-llms.git
git add -A
git commit -m "Initial import: GenAI, RAG, Whisper, and LLM APIs reference monorepo"
git push -u origin main
```

GitHub Actions in [`.github/workflows/`](.github/workflows/) run **awesome-lint** on the generative AI list and **awesome_bot** link checks for `README.md` and `DISCOVERIES.md` under `everything-gen-ai/`.

---

## Maintainer

**[John Anthony](https://github.com/anthonyjohn17)** — personal portfolio and working notes, merged and maintained in this monorepo.
