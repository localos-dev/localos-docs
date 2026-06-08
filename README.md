# localos-docs

Official documentation for LocalOS. Covers getting started, model access, API reference, and self-hosting.

Website: https://localos.xyz/docs
X: https://x.com/localos_xyz

---

## What this repo contains

The documentation source for LocalOS, served as a React component at localos.xyz/docs.

All documentation is in a single file: src/DocsPage.tsx. Each section is a standalone page rendered client-side via routing.

---

## Documentation sections

### Get Started

Introduction to LocalOS. What it is, how to open it in a browser, how to download a model, and how to go offline. Written for non-technical readers with no assumed knowledge of Node.js or terminal commands.

### Models

Overview of the model catalog. Covers the 6 model families (Llama, Qwen, Gemma, Phi, Mistral, Hermes), what each family is good at, and how to browse models in the app.

### Model Access

Three pages covering the free and paid model system:

Free and Paid Models: which models are free (under 2 GB), which require a one-time USDC payment, and what the pricing tiers are (15, 20, or 25 USDC depending on model size).

Wallet Setup: how to connect a wallet (MetaMask or Coinbase Wallet) to the Base network and acquire USDC. Written for users who have never used crypto before.

Payment Process: step-by-step walkthrough of how to pay for a model. Covers sending USDC to the generated address, what happens during the relay, and how access is confirmed.

### API Reference

Full REST API reference for the LocalOS API server. Documents every endpoint under /api with request and response examples.

### Self-Hosting

Instructions for running LocalOS on your own machine. Covers cloning the repo, installing dependencies, starting the API server and frontend, and environment variables.

### Contributing

How to contribute to LocalOS. Covers reporting issues, submitting pull requests, and content guidelines.

---

## Content rules

No symbols of any kind. No emoji, no arrows, no checkmarks, no em dashes, no en dashes. Plain English words and punctuation only.

All text in English.

Get Started and Model Access content is written for non-technical readers. No assumed knowledge of terminal commands, Node.js, or blockchain concepts in those sections.

Developer and Self-Hosting content may use technical terms freely.

Never use the internal name of the LLM runtime in user-facing sections. Use "LLM runtime" or "language model" instead.

---

## Links

Main app: https://github.com/localos-dev/localos
Model catalog: https://github.com/localos-dev/localos-models
Smart contract: https://github.com/localos-dev/localos-contracts
Website: https://localos.xyz
X: https://x.com/localos_xyz
