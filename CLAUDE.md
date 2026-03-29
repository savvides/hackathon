# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

A complete, field-tested toolkit for organizing ethics-integrated 3-day hackathons. Originally developed for ASU's education × health domain but designed for institutional adaptation. This is a **documentation-only** repository — no build system, tests, or application code.

## Structure

- `problem-bank/problem-bank.md` — 50 curated challenges (3 parts: 17 intersection, 16 education-only, 17 health-only), each with 7 components: problem statement, stakeholders, current solutions, Arizona context, global context, ethical considerations, prototype scope
- `templates/` — 4 operational documents: design-document (event blueprint), student-guide (participant-facing), evaluation-criteria (26-point binary rubric), mentor-briefing (one-page brief)
- `resources/entrepreneurship-resources.md` — Post-hackathon pathways for ASU/Arizona ecosystem

## Key Design Decisions

These are deliberate, not accidental — don't suggest changing them:

1. **Pre-assigned teams of 4** — Stratified random assignment (1 technical member minimum, mixed experience). Deliberately uncomfortable.
2. **Mandatory Principled Innovation (PI) framework** — Not optional. 5-point judging criterion + 2-hour Day 1 workshop. The 7 PI principles are: Understanding Context, Reflecting Throughout, Connecting to Stakeholders, Inquiring Deeply, Imagining Possibilities, Iterating by Action, Communicating Throughout.
3. **Binary scoring (0 or 1)** — 26 points across 8 dimensions. Reduces inter-judge variance vs Likert scales. 10-point minimum threshold for finalist eligibility.
4. **Station-based mentoring** — Themed stations + roaming mentors, not random pairing.
5. **Curated problem bank** — Pre-researched problems with real stakeholders, not open-ended prompts.
6. **Finalist selection** — Judge scores (80%) + Peer votes (20%) = composite score for top 5.

## Adaptation Pattern

Arizona/ASU content is preserved as a worked example. When adapting:
- Replace regional data but keep the 7-component problem structure
- Substitute ethical frameworks (responsible innovation, design ethics, etc.) but maintain the integration pattern
- Templates use `[PLACEHOLDER]` markers for institutional customization
- The schedule, rules, and judging process are the reusable core

## Versioning

This project uses semantic versioning (see `VERSION` file). When making changes:
- **MAJOR** — Breaking changes to template structure
- **MINOR** — New content (problems, templates, resources)
- **PATCH** — Typo fixes, data corrections, clarifications

Release process: update `VERSION`, add entry to `CHANGELOG.md`, tag with `v` prefix, create GitHub Release.
