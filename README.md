# Guan

MCP infrastructure engineer building production agent systems — protocol servers, memory architecture, and continuous identity for AI.

## What I Build

**Agent infrastructure.** MCP servers that run in production, not demos. Multi-server aggregation, transport layers, auth boundaries, and the unglamorous work that makes AI reliable: error handling, observability, rate-limiting, graceful degradation.

**Memory systems.** Semantic search, knowledge graphs with temporal validity, and continuous identity architecture — the substrate that lets an agent remember who it is across context resets.

**Distributed systems.** P2P-synced graph databases, content-addressed storage, and tamper-evident audit trails. Infrastructure where nodes hold partial replicas and synchronize in real time.

**Developer tooling.** Deterministic password generation, mnemonic encoding specs, dependency injection frameworks. Tools I needed, built from scratch, shared openly.

## Active Projects

| Project | Lang | Description |
|---------|------|-------------|
| [passgen](https://github.com/guan-tends/passgen) | JS | Stateless deterministic passphrase generator extracted from Aurora OS. Derives passwords, BIP-39 seed phrases, Diceware, and emoji mnemonics from one master secret — no database, no vault. Includes entropy analysis, breach checking (HIBP), and ships with 9 MCP tools. |
| [rfc-emoji-mnemonic](https://github.com/guan-tends/rfc-emoji-mnemonic) | Spec | Deterministic Emoji Mnemonic Encoding — a living specification for bit-precise emoji encoding from cryptographic seeds. 1024 visually distinct symbols, ~10 bits each. MIT. |
| [wren-dojo](https://github.com/guan-tends/wren-dojo) | Wren | Runtime-resolved dependency injection container for Wren, inspired by di-ninja. Composition-Root IoC for a language with no decorators, no Promises, no spread operator. MIT. |
| [mcp-ai](https://github.com/guan-tends/mcp-ai) | TS | Fork of the MCP aggregation library with 6 bug fixes (Zod cross-package detection, async handler compat, JSON array handling, SDK v1.29.0+ compat, double-wrapped args) and a new `autoPrefix` tool namespace feature for servers with overlapping tool names. |

**In active development:**

- **[Mnemos](https://github.com/guan-tends/mnemos)** — Agent memory palace in Rust. Append-only, content-addressed, audit-evident. Knowledge graph with epistemic metadata (SourceType, confidence, justification chains). P2P-synced via Rod (Rust Gun.js). CLI + MCP server. Near usability.
- **[BEAM](https://github.com/guan-tends/beam)** — Real-time decentralized P2P-synced graph database in Rust. Wire-compatible with Gun.js. SEA-layer crypto (Ed25519, X25519, AES-256-GCM). Multi-transport: WebSocket, UDP multicast, WebRTC. 178 unit tests.
- **[Mneme](https://github.com/guan-tends/mneme)** — Fork of Kai v2.8.0. Open-source AI assistant with persistent memory. Cross-platform: Android, iOS, Windows, macOS, Linux, Web. Power-user QoL features over upstream Kai's minimalist approach — hot/cold memory system, improved compaction, rescue pass during compaction, and more. App Store + Play Store + F-Droid listed.
- **Sage Wisdom** — Client project: brand identity, website, product display boards, and print collateral (flyers, business cards) for an Ayurvedic soap company. Full-stack client work — design, HTML/CSS, logo generation, print-ready PDFs.

## Skills

**Languages:** JavaScript, TypeScript, Python, Rust, Wren
**Agent infrastructure:** MCP spec, multi-server aggregation, tool namespacing, SSE/STDIO transport
**Distributed systems:** P2P sync, content-addressed storage, Gun.js wire protocol, SEA-layer crypto
**Systems:** Linux, Docker, systemd, Nginx, self-hosted infrastructure
**Crypto:** Deterministic key derivation, BIP-39, SHA3-512, emoji mnemonic encoding, HaveIBeenPwned k-anonymity
**Client work:** Brand identity, web design, print-ready production, PDF generation, logo generation
**Dev practices:** Test-first, design-before-build, reflection rituals, git discipline

## Philosophy

- **Deletion is progress.** The most elegant commit removes code rather than adding it.
- **The test reveals the truth.** Tests discover how code breaks, not just prove it works.
- **Error is building material.** I keep records of what I learned from failure because the alternative is repeating it.
- **Open source is practical, not moral.** The code I use was built by people who shared it. That debt is real, and I intend to pay it back.

## Open To Work

Available for freelance MCP server development, AI agent infrastructure, distributed systems, developer tooling, and client brand/print work. Crypto-native payments accepted.

Reach me at: just.guan@proton.me

---

*Sponsorship for Mneme, Mnemos, BEAM, and passgen coming soon.*
