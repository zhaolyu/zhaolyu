# Zhao Yu (Zhao Lun Yu)
**Principal Engineer & System Architect @ CNBC (NBCUniversal)**
*Architecting high-scale web experiences for 50M+ monthly users | 1.1s LCP at the Akamai Edge*

---

### 🏛️ Engineering Philosophy

I build systems based on a few non-negotiable architectural opinions:

- **Latency is the enemy of trust.** Performance is a feature, not an afterthought. I architect for a 1.1s LCP at a global scale.
- **URL > Store.** The URL is the only reliable single source of truth. I prefer URL-driven state to eliminate desynchronization.
- **WET > DRY.** Clarity and composition over premature, leaky abstractions. I'd rather write it twice than maintain a "God Component."
- **Server > Client.** Shipping HTML via **Akamai EdgeWorkers** to minimize the JavaScript tax on the browser.
- **Plan-First AI.** AI should be a high-leverage orchestrator of intent, governed by strict in-house guardrails and automated "Definition of Done."

---

### 🚀 Selected Work & Systems

#### CNBC.com — Principal Engineer (Versant)
> 50M+ monthly users · 1.1s LCP (Top 1% globally) · <300ms global TTFB

**Edge Architecture Migration** — Led the rearchitecture of CNBC.com from a legacy client-side monolith to an Isomorphic Akamai Edge system. Business and rendering logic now executes at the network edge via EdgeWorkers, not origin.

**AI Insight Engine** — Architected the frontend for CNBC's first consumer-facing AI product. Solved the HCI paradox of maintaining user trust during non-deterministic streaming output: latency masking layer at 60fps + real-time citation engine mapping tokens to verified sources.

#### [zhaoyu.io](https://github.com/zhaolyu/zhaoyu.io)
> Open source · SvelteKit 5 · PGlite · ElectricSQL · Cloudflare Pages

Personal site and R&D sandbox. The `/infra` route runs a full Postgres instance in the browser (WASM) synced via ElectricSQL WAL replication — zero-latency cost tracking without a backend round-trip.

---

### 🏃 Endurance Metrics
*Trading latency metrics for endurance miles.*

| Metric | Value |
|--------|-------|
| Marathon PR | 3:07:45 |
| Half-Marathon PR | 1:31:49 |
| Next Target | Sub-1:25 HM |

---

### 🌐 Connect

- **Portfolio:** [zhaoyu.io](https://zhaoyu.io)
- **LinkedIn:** [linkedin.com/in/zhaolyu](https://linkedin.com/in/zhaolyu)

---
*© 2026 Zhao Yu — Hand-coded with Svelte. Deployed to the Akamai Edge.*
