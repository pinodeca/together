---
id: contributions_ledger
title: Contributions Ledger and Conventions
status: draft
owner: unassigned
last_updated: 2026-04-26
tags: [governance, contributions, accounting]
summary_for_ai: >-
  This document defines the v0 conventions for tracking contributions in Together.
  It records hours logged, hours recognized, and review notes in a transparent ledger.
related: [governance_model, foundational_principles, open_questions]
---

# Contributions Ledger and Conventions

## Purpose
Track contribution effort transparently from day one, while keeping policy simple enough for a small founding team.

## v0 Conventions
- `hours_logged`: Self-reported hours by contributor.
- `hours_recognized`: Hours endorsed after group review.
- `hours_recognized` may be lower, equal, or higher than `hours_logged`, but any difference must include a short note.
- Logged work should include enough context to be auditable (what was done and where to find evidence).
- This ledger is not yet a cash payment system. It is a contribution and recognition record.
- Ownership and compensation formulas are intentionally deferred to a later decision process.

## Logging and Commit Policy
- Time can be logged in its own commit or bundled with related project work.
- Preferred default: include time-log updates in the same commit as the work when practical.
- Use a separate time-log-only commit when needed for accuracy, timing, or administrative cleanup.
- The key requirement is that log entries remain timely, reviewable, and linked to evidence.

## Time-Log Commit Naming Convention
- For time-log-only commits, use: `log-time: YYYY-MM-DD contributor hours`.
- Example: `log-time: 2026-04-26 pinodeca 2.0h`.
- If a commit includes both product work and logging updates, use the normal work-focused commit message.

## Review Process
- Review cadence: weekly by default.
- Review participants: founding contributors active in that period.
- Minimum review outputs:
  - accepted entries
  - adjusted entries with reasons
  - unresolved entries moved to next review

## Entry Requirements
Each row must include:
- date
- contributor
- work summary
- evidence links (PR, commit, issue, doc)
- hours_logged
- hours_recognized
- notes

## Ledger (v0)

| date | contributor | work_summary | evidence_links | hours_logged | hours_recognized | notes |
|---|---|---|---|---:|---:|---|
| 2026-04-25 | pinodeca | AI-first repo setup: structure scaffolding, contribution workflow, and foundational strategy docs | 67a795c; 2443f64 | 2.0 | 0.0 | pending review |
| YYYY-MM-DD | name | concise summary | link(s) | 0.0 | 0.0 | pending review |

## Future System Migration
- This markdown ledger is a bootstrap system for early-stage coordination.
- As membership and transaction volume increase, migrate to a dedicated contribution accounting system.
- Candidate options may include a database-backed application, auditable ledger infrastructure, or blockchain-based implementation.
- Migration decisions should prioritize transparency, low contributor friction, legal compliance, and data portability.

## Change Log
- 2026-04-26: Initial v0 contribution tracking conventions created.
- 2026-04-26: Added commit policy for time logging and future migration guidance.
- 2026-04-26: Added time-log commit naming convention and first ledger entry.
