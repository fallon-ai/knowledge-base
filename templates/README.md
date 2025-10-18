# 📋 Charlotte's Template Library

**Copy-paste templates for building systems 10x faster**

---

## What's In Here

### Session Documentation (`session-docs/`)
- **session-template.md** - Comprehensive session doc structure
- AI-optimized header + human-readable narrative
- Use with `/doc-session` command or manually

### Plugins (`plugins/`)
- **plugin-template.md** - Claude Code plugin scaffold
- Complete structure with all required sections
- Copy, fill in, deploy

### Workflows (`workflows/`)
- **workflow-blueprint.json** - Machine-readable workflow structure
- JSON format for Make/Zapier/n8n
- Includes testing, deployment, cost tracking

### Projects (`projects/`)
- **project-setup-template.md** - Client project setup
- Scope, deliverables, timeline, budget
- Quick Win (£297) or Deep Dive (£750/day) templates

---

## How To Use

### Quick Start
```bash
# 1. Copy the template you need
cp templates/plugins/plugin-template.md ~/.claude/commands/my-new-plugin.md

# 2. Fill in the [brackets]
# 3. Test it
# 4. Ship it
```

### For Session Docs
```bash
# Already integrated with /doc-session command
# Just run: /doc-session
# Template is automatically used
```

### For Workflows
```bash
# 1. Copy JSON template
cp templates/workflows/workflow-blueprint.json my-workflow.json

# 2. Fill in all fields
# 3. Import to Make/Zapier/n8n
# 4. Test and deploy
```

### For Projects
```bash
# 1. Copy project template
cp templates/projects/project-setup-template.md ~/projects/client-name/README.md

# 2. Fill in client details
# 3. Use as project hub
```

---

## Template Philosophy

**Every template includes:**
- ✅ Complete structure (nothing missing)
- ✅ Clear instructions ([bracketed placeholders])
- ✅ Examples for every section
- ✅ Success criteria
- ✅ Error handling guidance

**Why templates matter:**
- 🚀 10x faster than building from scratch
- 🎯 Consistency across all projects
- 🧠 Don't have to remember structure every time
- 📈 Scales to 100 projects without thinking

**Charlotte's rule:** "If I build it twice, it becomes a template."

---

## Customizing Templates

### For Your Business
1. Open template file
2. Change [bracketed] defaults to your standards
3. Save as your version
4. Use your version every time

### For Specific Clients
1. Copy base template
2. Add client-specific sections
3. Save as `client-name-template.md`
4. Reuse for that client's projects

---

## Template Checklist

Before using a template, verify:
- [ ] All [brackets] are filled in
- [ ] Dates are correct (YYYY-MM-DD format)
- [ ] File paths are accurate
- [ ] Client-specific info is updated
- [ ] Success criteria are clear

---

## Adding New Templates

### When to create a new template:
- ✅ You've built the same thing 2+ times
- ✅ There's a repeatable structure
- ✅ It saves 15+ minutes next time

### How to create a template:
1. Build the thing once (real project)
2. Copy the structure
3. Replace specific values with [brackets]
4. Add instructions/examples
5. Save to appropriate templates/ folder
6. Update this README

---

## Future Templates (Coming Soon)

**Planned additions:**
- [ ] Email sequence template
- [ ] LinkedIn post template
- [ ] Blog post structure
- [ ] Client onboarding checklist
- [ ] Weekly summary template
- [ ] NotebookLM source template

**Suggest a template:** Open an issue on GitHub

---

## Examples

**See real examples of these templates in action:**
- Session docs: `knowledge-systems/obsidian-vault/90-Sessions/`
- Plugins: `charlotte-claude-plugins/doc-session/`
- Workflows: `automation-workflows/` (coming soon)
- Projects: `projects/` (coming soon)

---

## Template Metrics

**Time saved per use:**
- Session doc: ~20 mins (vs starting from blank)
- Plugin: ~45 mins (vs figuring out structure)
- Workflow: ~30 mins (vs trial and error)
- Project: ~60 mins (vs creating from scratch)

**Total time saved after 10 uses:**
- Session doc: 3.3 hours
- Plugin: 7.5 hours
- Workflow: 5 hours
- Project: 10 hours

**ROI:** Spend 30 mins making template → Save 25+ hours over time

---

## Questions?

**"Do I have to use these exact templates?"**
No - customize them! They're starting points.

**"Can I create my own templates?"**
YES! Follow the same structure and add to this folder.

**"Which template should I use for [X]?"**
- Building a new command → Plugin template
- Documenting work → Session doc template
- Automating a process → Workflow template
- Client project → Project template

**"Can I share these?"**
Yes - they're all open source (MIT license). Share freely!

---

**Built by:** Charlotte Fallon
**Last updated:** October 18, 2025
**Version:** 1.0.0

**Philosophy:** "Build once, template it, never rebuild." 🚀
