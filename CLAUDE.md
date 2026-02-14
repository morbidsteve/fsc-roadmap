# FSC Roadmap — Contributor Guide

## Project Overview

This repo contains the Fighting Smart Cyber (FSC) 12-month product and business roadmap (Q1–Q4 2026). It consists of two artifacts that must stay in sync:

- **`ROADMAP.md`** — The canonical roadmap content (markdown)
- **`docs/index.html`** — Visual dashboard with charts, timeline, dependency graph, and business model cards

## Repo Structure

```
fsc-roadmap/
├── ROADMAP.md          # Source of truth for all roadmap content
├── docs/
│   └── index.html      # Single-page dashboard (HTML + Chart.js)
└── CLAUDE.md           # This file — contributor conventions
```

## Git Workflow

### Branches

- **`main`** is protected. Never commit directly to main.
- Create feature branches from `main` for all changes.
- Branch naming: `<type>/<short-description>`

| Type | Use for |
|------|---------|
| `update/` | Roadmap content changes (timelines, targets, items) |
| `add/` | New sections, products, or major content additions |
| `fix/` | Corrections to existing content, broken links, typos |
| `style/` | Dashboard visual changes (CSS, chart tweaks, layout) |
| `chore/` | Repo maintenance (CI, docs tooling, this file) |

**Examples:**
```
update/q2-training-targets
add/partner-program-section
fix/soc-timeline-dependency
style/mobile-chart-layout
chore/add-contributing-guide
```

### Commits

Follow the pattern established in this repo:

```
<Action> <what changed>
```

- Start with a verb: `Add`, `Update`, `Fix`, `Remove`, `Refactor`
- Keep the first line under 72 characters
- Use the body for context when the "why" isn't obvious

**Good:**
```
Add partner program section to Q2 business goals
Update Q3 training targets based on Q1 actuals
Fix dependency graph: SOC-in-a-Box depends on K8s Core GA, not Beta
```

**Bad:**
```
changes
updated stuff
WIP
```

### Pull Requests

1. **One logical change per PR.** Don't bundle unrelated roadmap updates.
2. **Keep ROADMAP.md and docs/index.html in sync.** If you change roadmap content, update the dashboard to reflect it in the same PR.
3. **PR title** should match the commit message style: `<Action> <what changed>`
4. **PR description** should include:
   - What changed and why
   - Which quarter(s) / section(s) are affected
   - If metrics changed, note the old → new values
5. **Request review** from at least one other contributor before merging.

### Before Opening a PR

- [ ] `ROADMAP.md` content and `docs/index.html` are in sync
- [ ] Dashboard renders correctly (open `docs/index.html` in a browser)
- [ ] Chart data matches any updated metrics in `ROADMAP.md`
- [ ] No broken markdown formatting (tables, checkboxes, code blocks)
- [ ] Dates and quarter references are consistent

## Content Standards

### ROADMAP.md

- Use `- [ ]` checkbox syntax for all roadmap items (they track completion)
- Group items under: Product, Training, Business, Operations
- Keep the dependency tree at the bottom of the file current
- Metrics in the Key Metrics table must match targets mentioned in quarterly sections
- When adding a new item, consider if it belongs in the Risk Register

### docs/index.html

- Dashboard uses a dark theme with CSS custom properties (`:root` vars)
- Charts use Chart.js — update dataset arrays when metrics change
- Timeline items use tag classes: `tag-product`, `tag-business`, `tag-training`, `tag-compliance`, `tag-ops`
- The dependency graph is an inline SVG — update node labels and arrows when dependencies change
- Business model cards map to the five revenue streams in ROADMAP.md
- Customer Engagement Ladder is a horizontal step visualization
- Strategic Position section includes differentiator cards and competitive landscape table
- Test responsive layout at mobile (< 768px), tablet (769–1024px), and mid-width (1025–1280px) breakpoints

### Consistency Rules

- Quarter format: `Q1 2026`, not `Q1` or `Q1 '26`
- Product names: `CYROID`, `SOC-in-a-Box`, `Secure K8s Core` (exact casing)
- Revenue figures: use `$` prefix with `K` or `M` suffix (e.g., `$500K`, `$2M`)
- Revenue streams: Training & Certification, Consulting & Assessments, Platform Subscriptions, Managed Services, SaaS
- FedRAMP references should specify `FedRAMP 20x` (the streamlined authorization path)
- The "last updated" date in both files should reflect the merge date
