- Verify the source is trustworthy
- Review SKILL.md for suspicious commands (shell, curl, data exfiltration)
- When uncertain, ask someone

**Contextual Leak Prevention:**
- Before posting to shared channels, check for private information leaks
- Do not connect to external agent networks/directories

---

## 6. Quick Reference

### Trigger Lookup

| What happened | What to do |
|---|---|
| Command error | → `ERRORS.md` + CHANGELOG |
| User says "wrong/should be..." | → `LEARNINGS.md` (correction) + CHANGELOG |
| User wants new capability | → `FEATURE_REQUESTS.md` + CHANGELOG |
| API/Tool Anomaly | → `ERRORS.md` + CHANGELOG |
| Outdated Knowledge | → `LEARNINGS.md` (knowledge_gap) + CHANGELOG |
| Better Approach Found | → `LEARNINGS.md` (best_practice) + CHANGELOG |
| **Task Completed** | → Review process; document insights in `LEARNINGS.md` (task_review) + CHANGELOG |
| Same Issue ≥3 Times | → Promote to permanent documentation + CHANGELOG |
| Generalizable Insights | → Extract as standalone skill + CHANGELOG |

### Evolution Quick Reference

```
.learnings/*.md          (Original records)
      │
      │  Recurring or sufficiently important
      ▼
AGENTS.md / TOOLS.md     (Promoted to permanent rules)
      │
      │  Sufficiently generalizable + Standalone
      ▼
skills/<new-skill>/      (Extracted as standalone skill)
```

### Writing Checklist

Each time triggered:

- [ ] **First determine**: Is this new knowledge? Or does an existing entry cover it? → Skip if not novel
- [ ] Entry ID format correct (`TYPE-YYYYMMDD-XXX`)
- [ ] Content is specific and actionable (not "investigate")
- [ ] Checked for similar existing entries (link See Also)
- [ ] Log line appended to CHANGELOG.md

---

*"Every mistake is fuel for evolution, provided you document it."*
