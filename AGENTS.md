# AGENTS Guide for Together

This file defines how AI agents should work in this repository.

## Mission
Help people build clear, cooperative thinking artifacts for the Together project.

## Source of Truth Order
1. User request in the current task.
2. Repository policies in `CONTRIBUTING.md`.
3. File-local guidance and templates.
4. Existing repository style and structure.

If sources conflict, prefer the higher item.

## Working Rules
- Keep edits minimal and scoped to the request.
- Preserve author intent when improving clarity.
- Add explicit assumptions when information is missing.
- Do not silently delete substantive content.
- Prefer small PRs with clear rationale.

## Document Contribution Standard
For substantial Markdown documents, include this frontmatter:

```yaml
---
id: unique_doc_id
title: Human Readable Title
status: draft
owner: unassigned
last_updated: 2026-04-25
tags: []
summary_for_ai: >-
  Short factual summary of the document in 2-4 sentences.
related: []
---
```

## Writing Quality Bar
- State the problem and context first.
- Use plain language and define key terms.
- Separate facts, assumptions, and proposals.
- Include open questions when decisions are incomplete.

## Preferred Workflow
1. Read related docs from `docs/`, `discussions/`, and `governance/`.
2. Draft changes with explicit assumptions.
3. Cross-link affected files.
4. Add or update decision records in `decisions/` for major directional changes.
5. Summarize what changed and why.

## Safety and Respect
- Follow the project code of conduct.
- Avoid discriminatory or exclusionary language.
- Focus critique on ideas, not people.

## PR Readiness Checklist
- Scope matches request.
- Language is clear and internally consistent.
- Links are valid.
- Assumptions and open questions are explicit.
- Licensing expectations remain CC-BY-SA 4.0 compatible.
