---
owner_name: "Ryan Wanner"
company_name: "Build Things That Build Things"
primary_market: "Business Operating Systems / Solo Entrepreneur Tools"
tone_of_voice: "Direct, systematic, Alex Hormozi-inspired"
last_updated: "2025-07-01"
tags: ["agent-logistics", "naming", "convention", "standards", "organization"]
---

# File & Directory Naming Convention

*The system that keeps 10,000 files as organized as 10*

## 🎯 Master Formula

```
<COMPANY>-<domain>-<descriptor>-<YYYYMMDD>-v<version>.<extension>
```

### Real Examples:
- `BTBT-2.4-landing-page-checkout-20250701-v1.html`
- `BTBT-0.1-vision-mission-values-20250630-v3.md`
- `BTBT-3.2-sales-script-discovery-20250615-v2.md`

## 📊 Component Breakdown

### 1. **COMPANY** (Required)
Your company abbreviation in CAPS. Keep it short.
- `BTBT` = Build Things That Build Things
- `ACME` = Acme Corporation
- `SS` = Scaling Systems

### 2. **Domain** (Required)
The numerical domain from our system:
- `0.x` = Foundation
- `1.x` = Market Intel
- `2.x` = Growth Engine
- `3.x` = Sales Pipeline
- `4.x` = Customer Success
- `5.x` = Product Innovation
- `6.x` = Finance/Admin
- `7.x` = People/Culture
- `8.x` = Tech Stack
- `9.x` = Governance

### 3. **Descriptor** (Required)
Clear, hyphenated description of the file's purpose:
- ✅ `email-nurture-sequence`
- ✅ `landing-page-variant-a`
- ✅ `quarterly-review-template`
- ❌ `email_nurture_sequence` (no underscores)
- ❌ `emailsequence` (not readable)

### 4. **Date** (Required)
Creation date in YYYYMMDD format:
- `20250701` = July 1, 2025
- `20250315` = March 15, 2025

### 5. **Version** (Required)
Version number with 'v' prefix:
- `v1` = Initial version
- `v2` = First revision
- `v3` = Second revision

### 6. **Extension** (Required)
Standard file extensions:
- `.md` = Markdown documents
- `.html` = Web pages
- `.yaml` = Configuration files
- `.js` = JavaScript files
- `.py` = Python scripts

## 🗂️ Directory Naming

Directories follow a simpler pattern:
```
<number>-<descriptive-name>/
```

Examples:
- `0-foundation/`
- `2-growth-engine/`
- `2.1-awareness/`
- `3-sales-pipeline/`

## ✅ Good Examples

```
BTBT-2.1-facebook-ads-campaign-20250701-v1.md
BTBT-3.4-contract-template-service-20250615-v2.docx
BTBT-0.3-brand-guidelines-complete-20250601-v4.pdf
BTBT-7.2-hiring-funnel-developer-20250720-v1.md
```

## ❌ Bad Examples

```
landing-page.html                    ← Missing all components
BTBT-landingpage.html               ← Missing domain, date, version
sales script final FINAL.doc        ← Spaces, no structure
New Document (1).docx               ← Default name
Copy of BTBT-2.1-ads-v1.md         ← Unclear versioning
```

## 🔍 Special Cases

### Templates vs. Instances
- **Template**: `BTBT-2.2-email-template-welcome-20250701-v1.md`
- **Instance**: `BTBT-2.2-email-instance-welcome-acme-20250705-v1.md`

### Multi-Part Files
When files are part of a series:
- `BTBT-2.3-email-sequence-part1-awareness-20250701-v1.md`
- `BTBT-2.3-email-sequence-part2-consideration-20250701-v1.md`
- `BTBT-2.3-email-sequence-part3-decision-20250701-v1.md`

### Working Drafts
For files under active development:
- `BTBT-4.1-onboarding-checklist-20250701-v1-DRAFT.md`
- `BTBT-5.2-roadmap-q3-20250701-v1-WIP.md`

## 💡 Quick Decision Tree

1. **Is it a directory?** → Use `number-description/` format
2. **Is it a file?** → Use full naming convention
3. **Is it a template?** → Include "template" in descriptor
4. **Is it an instance?** → Include "instance" and context
5. **Is it a draft?** → Add `-DRAFT` or `-WIP` suffix

## 🚀 Implementation Checklist

When creating a new file:
- [ ] Company abbreviation in CAPS
- [ ] Correct domain number
- [ ] Clear hyphenated descriptor
- [ ] Today's date in YYYYMMDD
- [ ] Version number (start with v1)
- [ ] Appropriate extension
- [ ] No spaces in filename
- [ ] No special characters except hyphens

## 🔧 Bulk Rename Script

For existing files that need renaming:
```bash
# Example usage (in scripts/rename-files.py)
python scripts/rename-files.py --source old-files/ --pattern BTBT
```

---

*A place for everything, and everything in its place. That's how you scale.*