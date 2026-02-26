Zhao Yu (Zhao Lun Yu)
Principal Engineer & System Architect @ CNBC (Versant)
Architecting high-scale web experiences for 50M+ monthly users | 1.1s LCP at the Akamai Edge

🏛️ Engineering Philosophy
I build systems based on a few non-negotiable architectural opinions:

Latency is the enemy of trust. Performance is a feature, not an afterthought. I architect for a 1.1s LCP at a global scale.
URL > Store. The URL is the only reliable single source of truth. I prefer URL-driven state to eliminate desynchronization.
WET > DRY. Clarity and composition over premature, leaky abstractions. I'd rather write it twice than maintain a "God Component."
Server > Client. Shipping HTML via Akamai EdgeWorkers to minimize the JavaScript tax on the browser.
Plan-First AI. AI should be a high-leverage orchestrator of intent, governed by strict in-house guardrails and automated "Definition of Done."
🚀 Selected Work & Systems
CNBC.com Next-Gen Migration
Role: Lead Architect
Impact: Migrated legacy monolith to Isomorphic Akamai Edge Architecture, achieving a 1.1s LCP (Top 1% globally) and <300ms TTFB.
Tech: React, Akamai EdgeWorkers, Node.js, GraphQL.
CNBC AI Insight Engine
Focus: HCI for non-deterministic AI output — solving user trust at 60fps token rendering.
Architecture: Latency masking layer + real-time citation engine mapping AI-generated tokens to verified CNBC sources.
Tech: React, Akamai Edge, Generative AI.
zhaoyu.io
Focus: This site — a hybrid edge application bridging global CDN performance with local-first interactivity.
Architecture: SvelteKit + Svelte 5 Runes frontend, PGlite (WASM Postgres) in the browser, ElectricSQL WAL sync, deployed to Cloudflare Pages.
🏃 Endurance Metrics
Trading latency metrics for endurance miles.

Metric	Value
Marathon PR	3:07:45
Half-Marathon PR	1:31:49
Next Target	Sub-1:25 HM
🌐 Connect
Portfolio: zhaoyu.io
LinkedIn: linkedin.com/in/zhaolyu
© 2026 Zhao Yu — Hand-coded with Svelte. Deployed to the Akamai Edge.
