# Action Items — Adversarial Review of Execution Plan

**Source:** Adversarial review of brainstorming session `brainstorming-session-2026-03-26-162717.md`
**Date:** 2026-03-28
**Status legend:** `[ ]` = not started · `[~]` = in progress · `[x]` = done

---

## 🔴 P0 — Blockers (Must Resolve Before Any Other Action)

These two items gate everything. Nothing else should start until they are answered.

- [ ] **[P0-1] Verify government contact has actual budget authority**
  - Do not assume a promise = procurement capacity.
  - Action: In your next meeting, ask directly — "Do you have a budget line for outsourcing digitization/translation, or would this require a new approval process? Who signs the contract?"
  - Success signal: Contact names a budget, a department, or a procurement officer you can speak to.
  - If blocked: Find the actual procurement decision-maker through the contact, or treat Gate 0 as unvalidated.

- [ ] **[P0-2] Pick one document type for the Concierge MVP — not both**
  - Paper-to-digital vs. translation require different skills, different SKILLS.md, different QA.
  - Action: Ask your contact which document type has the highest backlog or most urgent need. Pick that one. Start there only.
  - Success signal: You have a specific document type (e.g., "handwritten forms to digital text" or "Vietnamese-to-English policy docs") selected before the first squad meeting.

---

## 🟠 P1 — Must Resolve Before Concierge MVP Launch (Weeks 1–3)

- [ ] **[P1-1] Define your price**
  - The "1-page pitch" you bring to the government meeting needs a number.
  - Action: Research current market — what do digitization/translation vendors charge per page, per document, or per hour in Vietnam? Set your price as a % below market to win, with a floor that covers costs.
  - Output: A simple pricing table (e.g., cost per page for digitization, cost per word for translation).

- [ ] **[P1-2] Build a basic financial model — know your runway**
  - How many weeks can you operate before the first paid contract? What does each week cost (your time, API costs, tooling)?
  - Action: Spreadsheet with 3 columns: weekly costs, break-even contract size, months of runway you have.
  - Success signal: You know the answer to "how long can I run this before I must have revenue?"

- [ ] **[P1-3] Write a squad member recruitment profile**
  - "2–3 people" is not a hiring spec.
  - Action: Define minimum qualifications — AI tool literacy (which tools?), language ability (Vietnamese + English?), availability (hours/week), willingness to do repetitive work in a structured process.
  - Output: A 1-paragraph description you can send to candidates.

- [ ] **[P1-4] Create a quality rubric — not just "peer review"**
  - Peer review without a standard catches nothing.
  - Action: Define what "correct" looks like for your chosen document type. E.g., for digitization: character accuracy %, formatting match, handling of illegible text. Write this as a checklist the reviewer uses on every delivery.
  - Output: A 1-page QA checklist that any squad member can use without explanation.

- [ ] **[P1-5] Define your accuracy measurement method**
  - ≥90% accuracy is meaningless without a measurement instrument.
  - Action: Decide how accuracy is measured — spot-check by human reviewer against original? Character-level diff tool? Client rejection count? Who measures, how often?
  - Output: A documented measurement protocol (even 1 paragraph) before the Concierge MVP batch starts.

- [ ] **[P1-6] Check legal/regulatory disclosure requirements for AI use in government contracts**
  - "Human veil" pricing is strategically smart but may constitute misrepresentation under Vietnamese government procurement rules.
  - Action: Research (or ask a legally-informed contact) whether government procurement contracts in Vietnam require disclosure of AI tools used in service delivery.
  - Success signal: You know whether you must disclose AI involvement, and if so, how to frame it without undermining pricing.

---

## 🟡 P2 — Must Resolve Before Anchor Contract Pitch (Weeks 6–12)

- [ ] **[P2-1] Add contingency logic and timeline buffers to the execution plan**
  - Government procurement in Vietnam can take 12–18 months. The current plan assumes best-case at every phase.
  - Action: For each phase gate, add: (a) expected timeline, (b) worst-case timeline, (c) "if delayed by X weeks, we do Y" rule.
  - Output: Updated plan with explicit "circuit breaker" decisions at each phase — when to wait vs. when to pivot.

- [ ] **[P2-2] Build a contingency plan for faster-than-expected AI autonomy**
  - The Autonomy Extinction Bet is acknowledged but not planned for.
  - Action: Define the signal that would trigger a pivot — e.g., "if a major AI agent platform eliminates human-in-the-loop for document processing tasks, we pivot to X." Name the pivot direction now, even loosely.
  - Output: A 3-sentence contingency statement: "If [signal], we will [pivot action] within [timeframe]."

---

## 🟢 P3 — Must Resolve Before Phase 5: Commercial Launch (Months 9–18)

- [ ] **[P3-1] Define a concrete customer acquisition channel for the commercial phase**
  - "Squad reputation as network signal" is not a channel. It is a hope.
  - Action: Identify 1–2 specific channels to reach startups/SMEs who need content marketing — e.g., LinkedIn outreach, Vietnam startup Slack/Facebook groups, specific accelerator partnerships, cold email sequences. Define the channel before Phase 5 begins, not during it.
  - Output: A named distribution channel with a testable outreach tactic.

- [ ] **[P3-2] Do basic customer discovery on the commercial content marketing segment**
  - Content marketing for startups/SMEs was deferred from the MVP with zero discovery done on that segment.
  - Action: Before Phase 5 launches, run at least 5 customer discovery conversations with startup founders or SME owners about their content marketing pain. Do NOT assume the government digitization learnings transfer.
  - Output: A brief summary of the 5 conversations — what the pain actually is, what they currently pay, what would make them switch.

---

## Summary Table

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
| P3-2 | Do 5 customer discovery calls for commercial segment | 🟢 P3 | Before Phase 5 |
