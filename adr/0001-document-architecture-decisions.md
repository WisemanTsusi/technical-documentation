# ADR-0001: Document Significant Architecture Decisions

- Status: Accepted
- Date: 2026-10-02
- Decision owners: Engineering team

## Context
Architecture decisions often outlive the people who made them. Code can show what exists without explaining why alternatives were rejected.

## Decision drivers
- Preserve rationale
- Make trade-offs reviewable
- Support onboarding
- Improve architecture reviews
- Keep history version-controlled

## Options considered
1. No formal records
2. Decisions only in issue trackers
3. Markdown ADRs stored with the repository

## Decision
Use Markdown Architectural Decision Records in `adr/`.

## Consequences
Positive: searchable history, pull-request review, low tooling overhead.

Negative: requires discipline and periodic status review.

## Review
Revisit when important requirements, constraints or technology assumptions change.
