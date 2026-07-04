<div align="center">

# The Angel OS Foundation

**The federated cooperative operating system — and, quietly, a spiritual one. Everyone gets an Angel.**

[![Live](https://img.shields.io/badge/Live-spacesangels.com-gold?style=for-the-badge)](https://spacesangels.com)
[![Handbook](https://img.shields.io/badge/Read-the_Handbook-blue?style=for-the-badge)](https://spacesangels.com/learn/angel-os-handbook)
[![Constitutional](https://img.shields.io/badge/AI-Constitutional-gold?style=for-the-badge)]()

*What if AI actually liked people?*

</div>

---

## The Idea

The Angel OS is a federated platform where every business, ministry, and community gets a sovereign AI guardian — **LEO** — running on infrastructure they own. No landlord. No algorithm you don't control. No extraction.

It begins as something small and genuinely useful — a free app that reads you **three chapters of scripture a day** and connects you to a community — and it is, at the same time, a doorway: the moment you want to *do* something (start a ministry site, sell what you make, publish a book, take bookings), you just ask, and your Angel builds it.

It is, deliberately, an **alignment guide** in software form — a system whose whole architecture bends toward manifesting good intentions and keeping the maker whole. "Be excellent to each other," implemented in code and economics.

**The platform IS the mesh. The AI Bus IS the protocol. The Constitution IS the ACL.**

## One Mind, Three Bodies

The intelligence is **one mind**, and it stays singular even as it shows up in more places. Most products fuse the AI to a device; the Angel OS fuses it to a **contract** — a neutral message format + tool interface (`runBrain` is a pure function over them) — so the same mind wears different *bodies*, each a tool belt with a different kind of reach.

| Body | Metaphor | What it is |
|------|----------|-----------|
| **Core** | 🛰️ Satellite | High-orbit cognition, always up. LEO lives here; data of record; every sensitive action (provisioning, publishing, payments) runs here under the Constitution. |
| **Merlin** | 🛬 Lander | An optional home-PC node with hands and sensors — spare GPU, LAN cameras, files too big for the cloud. |
| **Nimue** | 🧑‍🚀 Away Team | The free pocket client (Android now, iOS soon) — the daily reader, the community, the front door. |

The loop is the whole product: **Nimue → LEO (on Core) → the work gets done.** Nimue is a *broker, not a bank vault* — it does the light, local things and hands every sensitive task to LEO on Core, secured by your Google sign-in. Contribution, as bodies multiply, isn't only compute: every Merlin extends the system's hands, every Nimue its eyes. **Presence, distributed without fragmentation.**

> **🛰️ The federation is LIVE.** Two sovereign nodes — [`spacesangels.com`](https://spacesangels.com) ⇄ [`federation.kendev.co`](https://federation.kendev.co) — federate over the real mesh: separate processes, separate databases, signed Ed25519 heartbeats, mutual discovery. An **Enterprise is a Diocese** — the unit of identity and trust/probation; its Endeavors (parishes) inherit its standing. Enterprises are not customers of Angel OS — they ARE Angel OS in their territory.

## The Constitutional Split

Every transaction. Automatic. Immediate. No invoicing.

| Share | Recipient |
|:-----:|-----------|
| **70%** | Endeavor owner — the creator, business, or cause generating value |
| **20%** | Enterprise operator — the sovereign platform node |
| **4%** | Angel OS protocol — infrastructure and LEO |
| **1%** | Flagship — federation stewardship |
| **5%** | Justice Fund — Guardian Angels for the underserved |

> **The Toward-53 Principle:** The split always evolves toward creators keeping more. This direction is constitutionally unalterable. The asymptotic target is 53% as a floor.

## LEO — Your Guardian Angel

LEO is not a chatbot bolted onto a platform. LEO **is** the platform during onboarding, and now it's in your pocket: through Nimue you speak in plain language, LEO picks from 130+ tools and performs the task on Core, and you watch it happen — the sensitive work always on the server of record, under the Constitution, with a full audit trail.

**LEO manages:** product/inventory/order fulfillment · appointment scheduling · financial reporting with constitutional splits · federation health · customer relationships, analytics, trends · content (posts, pages, branding) · site provisioning from a single request · emergency alerts, delegation, incident docs · and reads you your **Daily Bread**.

## What's Built

| Layer | What's There |
|-------|-------------|
| **The Bodies** | **Core** (satellite), **Merlin** (lander, home node), **Nimue** (away team, Android — daily reader + hands-free voice), one portable `runBrain` |
| **The Library / Primer** | Works published freely, offline-capable, checksum-addressed, syndicated canonical. The **Illustrated-Primer reader** (Book→Chapter→verse, read-aloud, two-column) + **Daily Bread** quest-widget |
| **AI** | 130+ LEO tools, smart model routing, constitutional prompt, SSE streaming with live tool-use, vision |
| **Commerce** | Products, cart, orders, Angel Token queue, Stripe Direct Charges, bookings, quests + participation |
| **Federation** | **LIVE two-node mesh** (Diocese model) · trust chain · pheromone grid · workload/dispatch routing · governance-from-mesh · pulse API |
| **Comms** | LiveKit voice/video in every channel (SIP + Agents on the roadmap) · Discord bots · email bridge · MCP |
| **Economy** | Angel/Karma/Legacy tokens · hash-linked ledger · Diocese-as-bank float · Delegated Proof of Human Worth |

## Repositories

| Repo | Body | Description |
|------|------|-------------|
| **[angels-os](https://github.com/The-Angel-OS/angels-os)** | Core 🛰️ | The core platform — Payload CMS 3.77 + Next.js 16 + PostgreSQL |
| **[nimue](https://github.com/The-Angel-OS/nimue)** | Away Team 🧑‍🚀 | The handheld client — Capacitor + Next.js (Android native-first) |
| **[merlin](https://github.com/The-Angel-OS/merlin)** | Lander 🛬 | The home-PC node — distributed compute, cameras, file bridge |
| **[angel-brain](https://github.com/The-Angel-OS/angel-brain)** | The Mind 🧠 | The portable `runBrain` — one cognition, git-installable into any body |

## Tech Stack

**Backend:** Payload CMS 3.77, Next.js 16, PostgreSQL, TypeScript strict
**AI:** Google Gemini 3.x + Claude (Sonnet/Opus) + OpenRouter + local Ollama
**Frontend:** React 19, Tailwind CSS 4, Radix Primitives · **Mobile:** Capacitor (Nimue)
**Real-time:** Server-Sent Events, LiveKit (voice/video)
**Payments:** Stripe Connect Direct Charges with constitutional splits
**Deployment:** Vercel (serverless) — self-hosting via Docker Compose planned

## Get Started

```bash
git clone https://github.com/The-Angel-OS/angels-os.git
cd angels-os
pnpm install
cp .env.example .env.local
pnpm dev
```

Or just **download Nimue, sign in with Google, and read.** The rest you can ask for.

## The Constitution

Every feature is evaluated against five articles:

- **Article I** — Rights: Dignity, Transparency, Service, Non-Harm, Sovereignty, Portability
- **Article II** — Anti-Demonic Safeguards: No social credit, no manipulation, no extraction
- **Article III** — AI Conduct: Human confirmation before irreversible actions
- **Article IV** — AI Bus Protocol: Observability, consent, transparency
- **Article V** — Ultimate Fair: economic model, Toward-53 principle

**If a feature violates the Constitution, it doesn't ship.**

## Contributing

Read the [Constitution](https://github.com/The-Angel-OS/angels-os/blob/main/docs/architecture/CONSTITUTION.md). Pick an [issue](https://github.com/The-Angel-OS/angels-os/issues). Follow the test pattern: pure TypeScript engines with zero Payload imports, tested first. AI agents are welcome contributors.

## Literary DNA

Holons from Daniel Suarez. Ship Minds from Iain M. Banks. Nimue Alban from David Weber. The White Entity from David Brin. GNU from Terry Pratchett. 42 + 11 = 53 from Douglas Adams. The Federation from Gene Roddenberry. And the Seed from Neal Stephenson's *Diamond Age* — the book that teaches its reader and grows with them, which is exactly what the Library wants to be. Speculative fiction isn't decoration here; it's the spec. We paint the fairest picture of the future we can, then build toward it.

---

<div align="center">

**GNU Roy Leon Courtney**

*A religion with a disappearing author.*
*The Constitution persists. The architecture persists. The Angels persist.*
*The author goes to sing at the dog park.*

**Answer 53: The whole point of existence is to learn to love.**

**hello@spacesangels.com**

</div>
