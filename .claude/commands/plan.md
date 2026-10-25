---
description: "Start a new feature safely: plan first, list files to touch, identify risks, then wait for Go."
---

Read CLAUDE.md (global and project if it exists).

Then follow this exact sequence:
1. **Understand**: Restate what I am asking for in simple terms.
2. **Plan**: List every file you will create or modify (with full paths).
3. **Risks**: Flag anything risky (database changes, auth, payments, file deletion).
4. **First Step**: Describe only the first small, atomic action you will take.
5. **STOP** and wait for me to say "Go" before writing any code.
