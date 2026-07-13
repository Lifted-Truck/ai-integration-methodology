# CLAUDE.md — ai-integration-methodology

Charter for the **human-epistemics half** of the practice: a methodology (and,
downstream, a consulting offering) for rigorous human-AI collaboration.
Everything above §Domain is the ecosystem harness layer.

## Truth contract
- **ROADMAP.md is the single source of direction.** DECISIONS.md is the
  append-only log. If the conversation and ROADMAP disagree, ROADMAP wins.
- **This is a knowledge product, not code.** "Done" = the ROADMAP gate met +
  `./verify` green (a doc-lint, not a test suite) + a `traces/` entry.
- **The methodology applies to its own construction.** This document argues
  that fluent AI output feels rigorous while drifting; writing it with AI is
  therefore the exact hazard it describes. Surface the desired conclusion
  before evaluating; treat comfortable agreement as a signal to check;
  re-anchor compressed claims against their foundations. (This is not a cute
  aside — it is the governing principle, self-applied.)
- **Claims carry citations or are marked as the doc's own synthesis.** A
  fluent unsourced empirical claim is the failure mode the doc warns about.
  Where a primary is unverified (e.g. DELEGATE-52), say so.

## Relationship to the ecosystem
Sibling to `autonomous` (github.com/Lifted-Truck/autonomous), not a consumer of
it. **autonomous = the agentic/deterministic half** (AI as a replaceable worker
inside a deterministic scaffold). **This project = the human-epistemic half**
(AI as a cognitive prosthetic for a motivated human; the discipline lives in the
human's head). They cross-reference and must not drift into each other's
territory: coordination/oracle/organ mechanics belong there; collaboration
epistemics, failure taxonomy, and the engagement model belong here. autonomous
has harvested the citable grounding (DELEGATE-52 + taxonomy) into its research/
and a doctrine tenet ("Human epistemic discipline at the gates"); this project
owns the full treatment.

---

## §Domain — ai-integration-methodology

**What this is.** `methodology.md` — "The Applied Epistemics of AI Integration":
the epistemic problem (why human-AI collaboration is uniquely dangerous), a
seven-mode failure taxonomy, the positive case (latent-space navigation / basin
escape), a five-stage methodology (Assumption Audit → Question Expansion →
Leverage Mapping → Iterative Scoping → Translation & Handoff), case studies, a
demonstration strategy (Part VI — placeholder), an engagement model (the
Operational Diagnostic), and an appendix (the metaorganism ontology).

**Form & audience.** A living document that will grow into pitch/demo/engagement
materials. Register shifts by section (philosophical appendix vs. business
engagement model) — keep each legible to its audience.

**Invariants (the critic checks against these).**
- Every empirical claim is cited or explicitly marked as the doc's own
  synthesis; unverified primaries are flagged, not laundered into fact.
- The five stages each keep their "prevents / enables" mapping to specific
  failure modes — that mapping is the doc's spine; don't sever it.
- Case studies stay concrete and truthful (real projects); no invented metrics.
- Confidentiality: client names appear only where the client is fine being
  named (Lochlin Smith Designs is; others may not be — check before adding).

**Verify targets.** `./verify fast` = doc-lint: internal-anchor integrity, no
orphaned/duplicate section numbers, every `## Part` present, flag TODO/placeholder
sections. `full` = fast + a citation-presence check (empirical-claim sections
carry a source or an explicit synthesis marker). No code; no network.

**Protected paths.** `methodology.md` (the product); `verify`; this charter.
