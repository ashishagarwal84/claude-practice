---
description: "Save current progress with a meaningful git commit message."
---

1. Run `git status` and show me what has changed.
2. Run `git diff --stat` to summarize the changes.
3. Suggest a clear, descriptive commit message in this format:
   `type(scope): short description`
   - type: feat / fix / refactor / docs / style / chore
   - Example: `feat(auth): add login page with email/password`
4. Ask me to confirm the message before running `git add . && git commit -m "..."`.
5. After committing, confirm success and show the commit hash.
