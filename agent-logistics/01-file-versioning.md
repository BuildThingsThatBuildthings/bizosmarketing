---
owner_name: "Ryan Wanner"
company_name: "Build Things That Build Things"
primary_market: "Business Operating Systems / Solo Entrepreneur Tools"
tone_of_voice: "Direct, systematic, Alex Hormozi-inspired"
last_updated: "2025-07-01"
tags: ["agent-logistics", "versioning", "file-management", "workflow"]
---

# File Versioning Guidelines

*Never lose progress, always move forward*

## 🎯 Core Principle

Every file has a lifecycle: Create → Update → Fork → Archive. Understanding when to use each action prevents chaos and preserves progress.

## 📊 Decision Matrix

| Scenario | Action | Example |
|----------|--------|---------|
| **New asset, nothing similar exists** | Create | First landing page ever |
| **Minor fixes (<20% changes)** | Update | Fix typo, update metric |
| **Major revision (>20% changes)** | New version | v1 → v2 |
| **Different use case** | Fork | Template → Client-specific |
| **No longer needed** | Archive | Move to `/_archive/` |

## 🔄 Version Numbering

### Standard Progression
- `v1` - Initial release
- `v2` - Major revision (structure change)
- `v3` - Another major revision
- `v1.1` - Minor update to v1
- `v2.1` - Minor update to v2

### When to Increment

**Major Version (v1 → v2)**
- Structural changes
- New sections added
- Purpose shift
- Breaking changes

**Minor Version (v1 → v1.1)**
- Content updates
- Small fixes
- Metric refreshes
- Typo corrections

---

*Version control isn't about perfection - it's about progress without fear.*