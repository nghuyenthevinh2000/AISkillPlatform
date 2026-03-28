---
marp: true
theme: default
paginate: true
style: |
  section {
    font-family: 'Segoe UI', sans-serif;
    background: #ffffff;
    color: #1a1a2e;
  }
  section.cover {
    background: #1a1a2e;
    color: #ffffff;
    text-align: center;
  }
  section.cover h1 { font-size: 2.4rem; margin-bottom: 0.2em; }
  section.cover p { font-size: 1rem; color: #aaaacc; }
  section.section-title {
    background: #16213e;
    color: #ffffff;
    text-align: center;
    justify-content: center;
  }
  section.section-title h2 { font-size: 2rem; }
  h2 { border-bottom: 3px solid #e94560; padding-bottom: 0.3em; }
  table { width: 100%; font-size: 0.8rem; }
  th { background: #1a1a2e; color: #ffffff; }
  tr:nth-child(even) { background: #f0f0f0; }
  .blocker { color: #c0392b; font-weight: bold; }
  .p1 { color: #e67e22; font-weight: bold; }
  .p2 { color: #f1c40f; font-weight: bold; }
  .p3 { color: #27ae60; font-weight: bold; }
---

<!-- _class: cover -->

# AI Execution Squad Platform
## Action Plan

**Based on BMAD Brainstorming + Adversarial Review**
March 2026

---

## What This Deck Is

This action plan is derived from two BMAD outputs:

1. **Brainstorming session** `2026-03-26` — Lean Startup execution plan covering problem discovery, product validation, PMF, and scale
2. **Adversarial review** `2026-03-28` — Critical stress-test of the execution plan, surfacing blockers and high-risk assumptions

> **Purpose:** Translate those outputs into a prioritised sequence of actions — so nothing important falls through the gap between planning and execution.

---

<!-- _class: section-title -->

## 🗺 Platform Vision

---

## The Big Idea

**AI Execution Squads** — small teams of human AI operators sharing a domain `SKILLS.md`, delivering expert-quality output through built-in peer review.

| Layer | What it does |
|---|---|
| **SKILLS.md** | Encodes expert AI-direction reasoning so technique outlives any session |
| **Squad model** | Peer review ensures quality no single operator can guarantee alone |
| **Human veil** | Clients pay agency prices for human-backed delivery; AI is internal infra |
| **Iteration flywheel** | SKILLS.md used on 500 real tasks is categorically better than one used on 5 |

**The window:** Human-centric internet infrastructure (auth, crawling, sessions) takes decades to redesign for AI — 3–7 years of structural advantage.

---

## Six-Phase Execution Roadmap

| Phase | Timeline | Goal |
|---|---|---|
| **Gate 0** | Pre-launch ✅ | Warm government contact — skip cold outreach |
| **Phase 1** Concierge MVP | Weeks 1–6 | Validate squad delivery on real government documents |
| **Phase 2** Build SKILLS.md | Weeks 4–16 | Reach ≥90% accuracy, 5× throughput vs. manual |
| **Phase 3** Anchor Contract | Weeks 10–20 | Secure a recurring or exclusive government contract |
| **Phase 4** Expand in Gov | Months 5–9 | New document types, additional departments |
| **Phase 5** Commercial | Months 12–24 | Content marketing for startups/SMEs |
| **Phase 6** Scale | Month 18+ | New squads, geographies, platform marketplace |

> **Beachhead:** Government document digitisation & translation — binary quality check, massive backlog, zero creativity required.

---

<!-- _class: section-title -->

## 🔴 P0 — Blockers
### Must resolve before anything else starts

---

## 🔴 P0-1 — Verify Budget Authority

**Risk:** A warm promise ≠ procurement capacity. Gate 0 is pre-validated on access, not on money.

**Action:**
In your next meeting, ask directly:

> *"Do you have a budget line for outsourcing digitisation/translation, or would this require a new approval process? Who signs the contract?"*

**Success signal:**
Contact names a budget, a department, or a procurement officer you can speak to.

**If blocked:**
Find the actual procurement decision-maker through the contact — or treat Gate 0 as unvalidated and run cold outreach in parallel.

---

## 🔴 P0-2 — Pick One Document Type

**Risk:** Paper-to-digital and translation require different SKILLS.md, different skills, different QA — trying both fragments everything.

**Action:**
Ask your contact:

> *"Which document type has the highest backlog or the most urgent need right now?"*

Pick that one. Start there **only**.

**Success signal:**
You have a specific document type selected **before** the first squad meeting — e.g., *"handwritten forms to digital text"* or *"Vietnamese-to-English policy documents."*

---

<!-- _class: section-title -->

## 🟠 P1 — Before Concierge MVP
### Weeks 1–3

---

## 🟠 P1-1 — Define Your Price

**Risk:** The 1-page pitch you bring to the government meeting needs a number. "We'll quote later" is not a pitch.

**Action:**
Research current market rates — what do digitisation/translation vendors charge per page, per document, or per hour in Vietnam?

Set your price as a % below market to win, with a floor that covers costs.

**Output:**
A simple pricing table — e.g., cost per page for digitisation, cost per word for translation.

---

## 🟠 P1-2 — Build a Financial Model

**Risk:** Without knowing your runway, you cannot make rational decisions about pace or pivots.

**Action:**
Build a spreadsheet with three columns:

| Column | What it answers |
|---|---|
| Weekly costs (time + APIs + tooling) | What does each week cost me? |
| Break-even contract size | How large must the first contract be? |
| Months of runway | How long can I run before I must have revenue? |

**Success signal:**
You can answer *"how long can I run this before I need revenue?"* without hesitation.

---

## 🟠 P1-3 — Write a Squad Recruitment Profile

**Risk:** "2–3 people" is not a hiring spec. Vague criteria produce vague squads.

**Action:**
Define minimum qualifications:
- AI tool literacy — which tools specifically?
- Language ability — Vietnamese + English?
- Availability — hours/week?
- Willingness to do repetitive work within a structured process

**Output:**
A 1-paragraph description you can send to candidates this week.

---

## 🟠 P1-4 — Create a Quality Rubric

**Risk:** Peer review without a standard catches nothing. "Someone checked it" is not quality assurance.

**Action:**
Define what *"correct"* looks like for your chosen document type.

Example for digitisation:
- Character accuracy %
- Formatting match to original
- Handling of illegible text (flag? substitute? leave blank?)

**Output:**
A 1-page QA checklist that any squad member can use without explanation.

---

## 🟠 P1-5 — Define Accuracy Measurement

**Risk:** "≥90% accuracy" is a meaningless target without a measurement instrument.

**Action:**
Decide how accuracy is measured:
- Spot-check by human reviewer against original?
- Character-level diff tool?
- Client rejection count?

Document: **who** measures, **how**, and **how often**.

**Output:**
A documented measurement protocol (even 1 paragraph) before the Concierge MVP batch starts.

---

## 🟠 P1-6 — Check AI Disclosure Requirements

**Risk:** "Human veil" pricing is strategically smart but may constitute misrepresentation under Vietnamese government procurement rules.

**Action:**
Research (or ask a legally-informed contact) whether government procurement contracts in Vietnam **require disclosure of AI tools** used in service delivery.

**Success signal:**
You know:
1. Whether you must disclose AI involvement
2. If yes — how to frame it without undermining your pricing

---

<!-- _class: section-title -->

## 🟡 P2 — Before Anchor Contract Pitch
### Weeks 6–12

---

## 🟡 P2-1 — Add Contingency Logic

**Risk:** The execution plan assumes best-case at every phase. Government procurement in Vietnam can take **12–18 months**.

**Action:**
For each phase gate, add three columns:

| Column | Content |
|---|---|
| Expected timeline | Best-case duration |
| Worst-case timeline | Realistic delay ceiling |
| Circuit breaker | "If delayed by X weeks, we do Y" |

**Output:**
Updated plan with explicit decision rules at each phase — when to wait vs. when to pivot.

---

## 🟡 P2-2 — Build an AGI Contingency Pivot Plan

**Risk:** The Autonomy Extinction Bet is acknowledged but not planned for. An unplanned existential risk is just a blind spot.

**Action:**
Define the signal that would trigger a pivot — e.g.:

> *"If a major AI agent platform eliminates human-in-the-loop for document processing tasks, we will [pivot action] within [timeframe]."*

**Output:**
A 3-sentence contingency statement:
1. **Signal:** *If [observable event]…*
2. **Action:** *…we will [specific pivot]…*
3. **Timeframe:** *…within [X weeks/months].*

---

<!-- _class: section-title -->

## 🟢 P3 — Before Commercial Launch
### Months 9–18

---

## 🟢 P3-1 — Define a Customer Acquisition Channel

**Risk:** *"Squad reputation as network signal"* is not a channel. It is a hope with no mechanism.

**Action:**
Identify 1–2 specific channels to reach startups/SMEs who need content marketing — e.g.:
- LinkedIn outreach sequences
- Vietnam startup Slack/Facebook groups
- Specific accelerator partnerships
- Cold email sequences

Define the channel **before Phase 5 begins**, not during it.

**Output:**
A named distribution channel with a testable outreach tactic.

---

## 🟢 P3-2 — Run Customer Discovery for Commercial Segment

**Risk:** Content marketing for startups/SMEs was deferred with **zero discovery** done on that segment. Government digitisation learnings do not transfer automatically.

**Action:**
Before Phase 5 launches, run **at least 5 customer discovery conversations** with startup founders or SME owners about their content marketing pain.

Ask:
- What is the actual pain?
- What do they currently pay?
- What would make them switch?

**Output:**
A brief summary of the 5 conversations.

---

<!-- _class: section-title -->

## 📋 Priority Summary

---

## All Actions at a Glance

| ID | Action | Priority | When |
|---|---|---|---|
| P0-1 | Verify gov contact has budget authority | 🔴 P0 | Before everything |
| P0-2 | Pick one document type only | 🔴 P0 | Before everything |
| P1-1 | Define pricing | 🟠 P1 | Before Concierge MVP |
| P1-2 | Build financial model / runway | 🟠 P1 | Before Concierge MVP |
| P1-3 | Write squad recruitment profile | 🟠 P1 | Before Concierge MVP |
| P1-4 | Create QA checklist / quality rubric | 🟠 P1 | Before Concierge MVP |
| P1-5 | Define accuracy measurement method | 🟠 P1 | Before Concierge MVP |
| P1-6 | Check AI disclosure legal requirements | 🟠 P1 | Before Concierge MVP |
| P2-1 | Add contingency logic / timeline buffers | 🟡 P2 | Before anchor contract pitch |
| P2-2 | Build AGI contingency pivot plan | 🟡 P2 | Before anchor contract pitch |
| P3-1 | Define commercial customer acquisition channel | 🟢 P3 | Before Phase 5 |
| P3-2 | Run 5 customer discovery calls (commercial) | 🟢 P3 | Before Phase 5 |

---

<!-- _class: section-title -->

## ⚡ Start Here

---

## Your First Two Actions

Nothing else should start until these are answered.

### This week — P0-1

**Ask your government contact:**
> *"Do you have a budget line for outsourcing, or does this require a new approval? Who signs the contract?"*

---

### This week — P0-2

**Ask your government contact:**
> *"Which document type — digitisation or translation — has the most urgent backlog right now?"*

---

Pick one. Start there. Everything else follows.

---

<!-- _class: cover -->

## Sources

- `_bmad-output/brainstorming/brainstorming-session-2026-03-26-162717.md`
- `_bmad-output/action-items-adversarial-review.md`

*Rendered with [Marp](https://marp.app)*
