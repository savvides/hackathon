# Tier 1 Open-Source Project — Design Spec

**Date**: 2026-03-28
**Goal**: Transform the hackathon toolkit from a documentation repo into a credible open-source project with proper versioning, release tracking, and community infrastructure.

---

## 1. Versioning & Release Tracking

### VERSION file
- Location: `VERSION` (repo root)
- Content: `1.0.0` (single line, no prefix)
- This is the first public release. The problem bank's internal "2.0" label is an ASU revision number, not a product version.

### CHANGELOG.md
- Location: `CHANGELOG.md` (repo root)
- Format: [Keep a Changelog](https://keepachangelog.com/) with semantic versioning
- Initial entry for v1.0.0 summarizing the complete toolkit:
  - 4 operational templates (design document, student guide, evaluation criteria, mentor briefing)
  - 50-problem curated bank (17 intersection, 16 education-only, 17 health-only)
  - Post-hackathon entrepreneurship resource guide
  - Binary 26-point evaluation rubric
  - Principled Innovation framework integration

### Versioning Policy
- **MAJOR** (X.0.0): Breaking changes to template structure — renamed placeholders, restructured evaluation criteria, changed problem format
- **MINOR** (0.X.0): New content — problems added, new templates, new resource guides, new sections
- **PATCH** (0.0.X): Typo fixes, data corrections, clarifications, link fixes

### Git Tags & GitHub Releases
- Tag format: `v1.0.0` (prefixed with `v`)
- Create GitHub Release via `gh release create v1.0.0` with notes from CHANGELOG.md
- Future releases follow the same pattern: update VERSION, update CHANGELOG, tag, release

---

## 2. CONTRIBUTING.md

Location: `CONTRIBUTING.md` (repo root)

### Sections

1. **Welcome** — Context: open-source hackathon toolkit designed for institutional adaptation. Contributions improve the toolkit for everyone.

2. **How to Contribute** — Three contribution types:
   - **New problems**: Must follow the 7-component structure (problem statement, affected stakeholders, current inadequate solutions, regional context, global context, ethical considerations, prototype scope). Use the new-problem issue template.
   - **Template improvements**: Bug fixes, clarifications, structural improvements to the 4 operational templates.
   - **Adaptation reports**: Institutions that ran a hackathon using this toolkit share what they changed and lessons learned. Use the adaptation-report issue template.

3. **PR Conventions**:
   - Branch naming: `content/<description>`, `fix/<description>`, `adaptation/<description>`
   - Commit messages: imperative mood, concise (e.g., "Add problem 51: rural pharmacy access")
   - One logical change per PR

4. **Versioning Policy** — Reference to the MAJOR/MINOR/PATCH rules above

5. **Code of Conduct** — Adopt Contributor Covenant v2.1 (industry standard)

---

## 3. GitHub Templates

### Issue Templates (`.github/ISSUE_TEMPLATE/`)

#### `bug-report.md`
- **Purpose**: Errors in templates, incorrect data, broken links, formatting issues
- **Fields**: Description, which file, expected vs actual, screenshot (optional)

#### `new-problem.md`
- **Purpose**: Propose a new problem for the problem bank
- **Fields**: Matches the 7-component structure:
  1. Problem statement (with data/statistics)
  2. Affected stakeholders
  3. Current inadequate solutions
  4. Regional context
  5. Global context
  6. Ethical considerations (PI framework alignment)
  7. Prototype scope (achievable in 2.5 days)
- **Additional fields**: Suggested part (intersection/education-only/health-only), difficulty level, domain alignment

#### `adaptation-report.md`
- **Purpose**: Institutions report back on their hackathon experience
- **Fields**: Institution name, event date, number of participants/teams, what they kept as-is, what they changed and why, lessons learned, permission to list as adopter

### PR Template (`.github/PULL_REQUEST_TEMPLATE.md`)
- **Checklist**:
  - [ ] Description of change
  - [ ] Type: content / fix / adaptation
  - [ ] Versioning impact: major / minor / patch
  - [ ] If adding a problem: follows 7-component structure
  - [ ] If adding a problem: PI framework ethical considerations included

---

## 4. Files Summary

| File | Action | Purpose |
|------|--------|---------|
| `VERSION` | Create | Single-line version number |
| `CHANGELOG.md` | Create | Release history |
| `CONTRIBUTING.md` | Create | Contribution guide |
| `CODE_OF_CONDUCT.md` | Create | Contributor Covenant v2.1 |
| `.github/ISSUE_TEMPLATE/bug-report.md` | Create | Bug report template |
| `.github/ISSUE_TEMPLATE/new-problem.md` | Create | Problem proposal template |
| `.github/ISSUE_TEMPLATE/adaptation-report.md` | Create | Adaptation report template |
| `.github/PULL_REQUEST_TEMPLATE.md` | Create | PR checklist |
| `CLAUDE.md` | Update | Add versioning policy reference |
| `README.md` | Update | Add badges, link to CONTRIBUTING and CHANGELOG |

---

## 5. Verification

1. All new files exist and are well-formatted markdown
2. `VERSION` contains `1.0.0`
3. `CHANGELOG.md` has a complete v1.0.0 entry
4. Git tag `v1.0.0` exists
5. GitHub Release is created with correct notes
6. `README.md` links to CONTRIBUTING.md and CHANGELOG.md
7. Issue templates render correctly on GitHub (verify after push)
