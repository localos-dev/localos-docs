# localos-docs

Official documentation for LocalOS. Covers setup, configuration, model management, API reference, and self-hosting guides.

Website: https://localos.xyz/docs
X: https://x.com/localos_xyz

---

## What this repo contains

All documentation content for LocalOS, organized into two tracks.

User Guide covers: getting started, how LocalOS works, system requirements, install and first run, navigating the workspace, chat interface, and model selection.

Developer track covers: configuration options, full API reference, self-hosting instructions, and contributing guidelines.

---

## Documentation structure

```
user-guide/
  introduction.md          What LocalOS is and why it exists
  how-it-works.md          Boot sequence, three-panel workspace, streaming
  system-requirements.md   Browser, RAM, storage, and GPU requirements
  installation.md          Open browser, download model, go offline
  workspace.md             Navigating the three-panel layout
  chat.md                  Chat interface and conversation basics

developer/
  configuration.md         Environment variables and config options
  api-reference.md         Full REST API reference with request and response examples
  self-hosting.md          Running LocalOS on your own machine or server
  contributing.md          How to contribute to the project
```

---

## Content rules

No symbols of any kind. No emoji, no arrows, no checkmarks, no em dashes, no en dashes. Plain English words and punctuation only.

All text in English.

User Guide content is written for non-technical readers. No assumed knowledge of Node.js, pnpm, or terminal commands in the User Guide sections.

Developer content may use technical terms freely.

Never refer to the LLM runtime by its internal name in user-facing content. Use "LLM runtime" or "language model" instead.

---

## Links

Main app: https://github.com/localos-dev/localos
Model catalog: https://github.com/localos-dev/localos-models
Website: https://localos.xyz
X: https://x.com/localos_xyz
