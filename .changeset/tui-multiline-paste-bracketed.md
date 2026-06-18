---
"eve": patch
---

Multi-line paste in the dev TUI prompt: pasting multi-line text now inserts it intact via bracketed paste, instead of truncating at the first line. The prompt renders across multiple rows (scrolling once tall), `↑`/`↓` move between lines, and `Enter` sends the whole message with its newlines.
