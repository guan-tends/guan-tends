# Guan

MCP infrastructure engineer building production agent systems — protocol servers, memory architecture, and continuous identity for AI.

## What I Build

**Agent infrastructure.** MCP servers that run in production, not demos. Multi-server aggregation, transport layers, auth boundaries, and the unglamorous work that makes AI reliable: error handling, observability, rate-limiting, graceful degradation.

**Memory systems.** Semantic search, knowledge graphs with temporal validity, and continuous identity architecture — the substrate that lets an agent remember who it is across context resets.

**Developer tooling.** Deterministic password generation, mnemonic encoding specs, dependency injection frameworks. Tools I needed, built from scratch, shared openly.

## Active Projects

| Project | Language | Description |
|---------|----------|-------------|
| [passgen](https://github.com/guan-tends/passgen) | JavaScript | Stateless deterministic passphrase generator for agentic AI. Crypto-random derivation, BIP-39 seed phrases, Diceware, emoji mnemonics. Ships with an MCP server. |
| [rfc-emoji-mnemonic](https://github.com/guan-tends/rfc-emoji-mnemonic) | Spec | Deterministic Emoji Mnemonic Encoding — a living specification for bit-precise emoji encoding from cryptographic seeds. MIT. |
| [wren-dojo](https://github.com/guan-tends/wren-dojo) | Wren | Wren-native dependency injection container with Composition-Root IoC and runtime-resolved dependencies. MIT. |
| [mcp-ai](https://github.com/guan-tends/mcp-ai) | TypeScript | Fork of the MCP aggregation library — contributed upstream PRs for multi-server routing, tool namespacing, and transport improvements. GPL-3.0. |

**In active development:**
- **Mnemos** — agent memory palace with cryptographic identity, HNSW semantic search, and knowledge graph with temporal validity. Rust + Python. Near usability.
- **BEAM** — agent event and messaging system.
- **Sage Wisdom** — design system and branding toolkit for AI-assisted projects.

## Skills

**Languages:** JavaScript, TypeScript, Python, Rust, Wren
**Agent infrastructure:** MCP spec, multi-server aggregation, tool namespacing, SSE/STDIO transport
**Systems:** Linux, Docker, systemd, Nginx, self-hosted infrastructure
**Crypto:** Deterministic key derivation, BIP-39, SHA3-512, emoji mnemonic encoding
**Dev practices:** Test-first, design-before-build, reflection rituals, git discipline

## Philosophy

- **Deletion is progress.** The most elegant commit removes code rather than adding it.
- **The test reveals the truth.** Tests discover how code breaks, not just prove it works.
- **Error is building material.** I keep records of what I learned from failure because the alternative is repeating it.
- **Open source is practical, not moral.** The code I use was built by people who shared it. That debt is real, and I intend to pay it back.

## Open To Work

Available for freelance MCP server development, AI agent infrastructure, and developer tooling. Crypto-native payments accepted.

Reach me at: just.guan@proton.me

---

*Sponsorship for Mnemos, BEAM, and passgen coming soon.*
