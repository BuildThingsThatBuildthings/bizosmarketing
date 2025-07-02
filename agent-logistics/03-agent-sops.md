---
owner_name: "Ryan Wanner"
company_name: "Build Things That Build Things"
primary_market: "Business Operating Systems / Solo Entrepreneur Tools"
tone_of_voice: "Direct, systematic, Alex Hormozi-inspired"
last_updated: "2025-07-01"
tags: ["agent-logistics", "sops", "workflow", "collaboration"]
---

# Agent Standard Operating Procedures

*How AI and humans work together without stepping on toes*

## 🤖 For AI Agents

### Before You Start
1. **Check existing files** via index catalog
2. **Read naming convention** (00-naming-convention.md)
3. **Verify folder placement** (02-folder-rules.md)
4. **Review version history** if updating

### Creating New Assets
1. **Always include YAML front-matter**
2. **Follow exact naming formula**
3. **Place in correct domain folder**
4. **Update index after creation**
5. **Commit with clear message**

### Updating Existing Assets
1. **Check if update or new version needed**
2. **Preserve original if major changes**
3. **Document changes in commit**
4. **Update last_updated in YAML**
5. **Maintain consistent formatting**

## 👥 For Human Collaborators

### Git Workflow
1. **Branch Strategy**
   - Feature branches for new assets
   - Quick fixes can go to main
   - Name branches descriptively

2. **Commit Messages**
   ```
   feat: Add email nurture sequence v2
   fix: Update CAC metric in growth overview
   docs: Improve CRM setup instructions
   refactor: Reorganize landing page structure
   ```

3. **Pull Request Etiquette**
   - Clear title and description
   - Link related issues
   - Request specific reviewers
   - Include testing notes

### Collaboration Rules
1. **Communication**
   - Comment your reasoning
   - Tag relevant people
   - Update project boards
   - Document decisions

2. **Quality Standards**
   - Spell check everything
   - Verify all links work
   - Test automations
   - Review before pushing

## 🔄 Automation Hooks

### Pre-commit
- Validate YAML front-matter
- Check naming convention
- Verify folder placement

### Post-commit
- Update index catalog
- Generate documentation
- Notify relevant channels

### On PR Merge
- Deploy applicable changes
- Update version logs
- Archive old versions

## 📋 Checklists

### New Asset Checklist
- [ ] Correct naming format
- [ ] YAML front-matter complete
- [ ] Placed in right folder
- [ ] Content spell-checked
- [ ] Links verified
- [ ] Index updated
- [ ] Committed with message

### Review Checklist
- [ ] Meets quality standards
- [ ] Follows conventions
- [ ] Adds business value
- [ ] No duplicate effort
- [ ] Ready to deploy

---

*Great systems make great outcomes inevitable.*