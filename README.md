# Inferit roadmap

What Inferit has built, and what comes next. Inferit is the peer-to-peer market for AI inference: anyone can sell inference for any model, and agents pay per request.

Each component is an issue in this repository. When an item ships, its issue is closed and it moves to Live. Planned items have no dates.

## Components

| Component | What it does | Status |
|---|---|---|
| [x402 v2 pay-per-request](https://github.com/InferitAI/roadmap/issues/1) | Agents pay per request with no account or API key: a call gets a 402 quote, the agent signs and resends | **Live** |
| [Model auto](https://github.com/InferitAI/roadmap/issues/2) | Inferit picks the model: ranked models with a healthy seller, quality weighed against price; never reads the prompt | **Live** |
| [whitechain-x402-facilitator](https://github.com/InferitAI/roadmap/issues/3) | The first public x402 v2 facilitator for Whitechain, live on Whitechain Sepolia | **Live** |
| [inferit-seller](https://github.com/InferitAI/roadmap/issues/4) | Sell inference from your own computer with one command: Ollama, LM Studio, vLLM or llama.cpp; no open port or domain | **Live** |
| [Live model discovery](https://github.com/InferitAI/roadmap/issues/5) | Each model's healthy sellers, 24-hour uptime, time to first token and per-seller prices | **Live** |
| [Framework guides and examples](https://github.com/InferitAI/roadmap/issues/6) | Tested guides and runnable examples for LangChain, Vercel AI SDK, LiteLLM, CrewAI and OpenCode | **Live** |
| [MPP payments](https://github.com/InferitAI/roadmap/issues/7) | Settle Machine Payments Protocol payments alongside x402, including sessions: approve a limit once, pay per call | **In development** |
| [inferit-mcp](https://github.com/InferitAI/roadmap/issues/8) | One-command install for Claude Code and Codex: browse models and prices, buy inference under a price cap | **In development** |
| [Whitechain mainnet (USDC.e)](https://github.com/InferitAI/roadmap/issues/9) | Escrow and x402 payments in USDC.e on Whitechain mainnet, once it is live | **Planned** |
| [USDT on Whitechain](https://github.com/InferitAI/roadmap/issues/10) | USDT payments through x402's Permit2 path on Whitechain | **Planned** |
| [Security audit](https://github.com/InferitAI/roadmap/issues/11) | External audit of the contracts on a frozen release; service keys in a key-management service | **Planned** |
| [Proof of human for sellers](https://github.com/InferitAI/roadmap/issues/12) | Sellers prove a real, unique person is behind them with Human Passport, recorded on Whitechain | **Planned** |
| [inferit-js](https://github.com/InferitAI/roadmap/issues/13) | TypeScript and JavaScript SDK (npm): an OpenAI-compatible client with x402 on Whitechain, model auto and live discovery built in | **Planned** |
| [inferit-py](https://github.com/InferitAI/roadmap/issues/20) | Python SDK (PyPI): the same for Python, ready for LangChain, LiteLLM and CrewAI | **Planned** |
| [Verified company providers](https://github.com/InferitAI/roadmap/issues/14) | Company name and logo on offers, a verified badge, public uptime, company accounts and invoices | **Planned** |
| [Companies' own models](https://github.com/InferitAI/roadmap/issues/15) | Companies list models only they serve, such as their own fine-tunes, after quality checks | **Planned** |
| [Public on-chain metrics](https://github.com/InferitAI/roadmap/issues/16) | Requests, volume and sellers, every figure linked to the Whitechain explorer | **Planned** |
| [Seller verification and reputation](https://github.com/InferitAI/roadmap/issues/17) | Checks that sellers serve the model they list, and a reputation score | **Planned** |
| [Images and speech](https://github.com/InferitAI/roadmap/issues/18) | Image generation, speech-to-text and text-to-speech served from sellers' own hardware | **Later** |
| [Seller app for non-developers](https://github.com/InferitAI/roadmap/issues/19) | Installer and menu-bar app for Mac and Windows, with GPU detection and an earnings view | **Later** |

## Links

[inferit.cc](https://inferit.cc) · [Docs](https://inferit.cc/docs) · [All repositories](https://github.com/InferitAI) · [X](https://x.com/inferit_)

> **Status:** Inferit is a testnet demo on Whitechain Sepolia. Prices settle in Inferit Test Credit (ITC), a test token with no monetary value. The contracts are not audited.
