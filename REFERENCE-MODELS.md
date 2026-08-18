# Reference-Model Registry

The purpose of a reference-model registry is not to write more templates. It is to hold a single origin for each pattern so that independent users, working on different clients, produce outputs that combine cleanly.

Drift is inevitable when public reasoning models — the ones the client's team actually uses day-to-day — generate freshly on each ask. The counter-move is not to fight the drift. It is to always start from the same origin.

---

## What lives here

| Model | Purpose | Status |
|---|---|---|
| **Session tenant boundary** | Client tenant holds delivery evidence. The commercialization firm's tenant holds the proprietary method. Chat/calendar in the client's domain; substantive content never in SMS. | Canon — see boot contract `EgD-BOOT-001`. |
| **Semantic-layer mirror** | Structural conventions for a sovereign agent that mirrors an enterprise system of record without breaking the record's semantic layer. | Referenced pattern; versioned. |
| **Enablement curriculum** | Session sequence from "the agent exists" to "we run it in production," bounded by secure- and open-lane workflows. | v0.1 — expandable per client. |
| **Fractional operating rhythm** | Monthly minimum plus surge — the working shape of the specialist pool. | v0.1 — see `PARTNER-PLAYBOOK.md`. |
| **Document-review checklist** | Standardized review pattern for artifacts produced under enablement — what to look for, what to keep, what to correct. | v0.1. |
| **Process-improvement one-pager** | The single-page format for surfacing a candidate improvement, its evidence, and its expected impact. | v0.1. |
| **PDF and canon compliance** | Palette, typography, watermark, footer, hash, timestamp — the output canon that keeps every deliverable recognizable and durable. | Canon — see boot contract. |

---

## Fork rules

- **Forks declare their parent.** Every derivative document names the reference-model version it forked from and the date.
- **Corrections go upstream.** If a fork discovered something the reference should carry, submit the correction back to the reference. Diverging forever is the drift the registry exists to prevent.
- **Version bumps are additive.** Reference models append and correct. They do not delete history.
- **Names are stable.** The names in the table above do not change casually. Renaming is damage, not housekeeping.

---

## Two boundaries the registry does not cross

1. **Client-specific content stays private.** The reference models are generic patterns. Client-specific engagement material — the training plan for one team, the review of one client's process — lives in the private engagement repository, not here.
2. **The reference registry does not host the agent.** The registry hosts the templates, checklists, and formats. The agent — the sovereign mirror of the system of record — lives inside the client's own tenant.

---

*Enterprise Agent Enablement · EVE Glyph Design.*
