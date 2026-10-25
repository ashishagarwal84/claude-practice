---
description: "Build a new feature end-to-end: spec first, code second, verify third."
---

Feature to build: $ARGUMENTS

Step 1 — SPEC (do this first, stop after):
Write a SPEC.md file with:
- What this feature does (plain English)
- What files need to be created or changed
- Any database or API changes needed
- Security considerations
- How to test it manually

STOP after writing SPEC.md. Wait for me to review and say "Go".

Step 2 — Only after I say "Go":
- Implement the feature following CLAUDE.md rules
- One file at a time, explain each change
- After all changes: tell me exactly how to run and test it

Step 3 — Verify:
- Run npm run lint (if available)
- Run npm test (if available)  
- Fix any errors found
- Suggest a git commit message

If $ARGUMENTS is empty, ask me: "What feature do you want to build?"
