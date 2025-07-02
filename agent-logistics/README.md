# Agent Logistics Handbook

Single source of truth for how AI and human collaborators organize, name, version, and locate every asset in this BOS repo.

## 🎯 Purpose

This handbook ensures consistency across all collaborators - whether AI agents, team members, or external partners. Follow these conventions to maintain a clean, scalable, and searchable business operating system.

## 📋 Quick Reference

### Naming Convention
```
<SHORT>-<domain-prefix>-<slug>-<YYYYMMDD>-v<rev>.<ext>
```

**Example**: `BTBT-2.4-landing-page-20250701-v1.html`

### Key Rules

1. **Create vs. Update**: Fork templates, never overwrite canonical versions
2. **Branching**: One feature branch per asset; PR to `main` when done
3. **Indexing**: Run `scripts/update-index` after adding files; updates `04-index-catalog.md`
4. **Tags**: Include `tags:` YAML in every Markdown doc for easy search

## 📂 Domain Prefixes

| Domain | Prefix | Description |
|--------|--------|-------------|
| Foundation | 0.x | Vision, mission, legal, brand |
| Market Intel | 1.x | ICP, competitive analysis, positioning |
| Growth Engine | 2.x | Marketing, lead gen, conversion |
| Sales Pipeline | 3.x | CRM, scripts, proposals |
| Delivery | 4.x | Customer success, onboarding |
| Product | 5.x | Roadmap, features, releases |
| Finance | 6.x | Accounting, budgets, KPIs |
| People | 7.x | Hiring, culture, training |
| Tech Stack | 8.x | Infrastructure, automation |
| Governance | 9.x | Reviews, improvements |

## 🔄 Workflow

1. **Before Creating**:
   - Check `04-index-catalog.md` for existing assets
   - Review naming convention above
   - Create feature branch: `git checkout -b add-<asset-name>`

2. **During Creation**:
   - Add YAML front-matter to all `.md` files
   - Follow folder structure exactly
   - Include meaningful commit messages

3. **After Creation**:
   - Run `scripts/update-index.py`
   - Create pull request to `main`
   - Tag reviewers in PR description

## 🏷️ YAML Front-Matter Template

```yaml
---
owner_name: "Ryan Wanner"
company_name: "Build Things That Build Things"
primary_market: "Business Operating Systems / Solo Entrepreneur Tools"
tone_of_voice: "Direct, systematic, Alex Hormozi-inspired"
last_updated: "2025-07-01"
tags: ["domain", "specific", "searchable", "tags"]
---
```

## 🚫 Common Mistakes to Avoid

- ❌ Editing files directly in `main` branch
- ❌ Creating files without YAML front-matter
- ❌ Using spaces in filenames (use hyphens)
- ❌ Forgetting to update the index catalog
- ❌ Overwriting canonical templates

## 🔍 Finding Assets

1. **By Domain**: Navigate to numbered folders
2. **By Tag**: Search repo for `tags: ["your-tag"]`
3. **By Date**: Use naming convention dates
4. **By Index**: Check `04-index-catalog.md`

## 🤖 AI Agent Instructions

When working in this repository:

1. Always check existing assets before creating new ones
2. Follow naming conventions exactly
3. Include complete YAML front-matter
4. Update index after adding files
5. Create descriptive commit messages
6. Reference this guide when uncertain

---

*This logistics system ensures your BOS scales smoothly as your business grows.*