# Plan Mode Guidance (Non-Obvious Only)

* **Architecture Goal**: Keep the codebase monolithic within a single `index.html` to maximize portability and ensure instant deployment to GitHub Pages without server-side resources.
* **Theme Standards**: Color switches should strictly correspond to standard IBM Carbon Design System tokens (e.g. `--interactive` maps to Blue 60 in Light and Blue 30 in Dark; `--bg-primary` maps to Gray 10 in Light and Gray 100 in Dark).
* **Dynamic Tip Cycling**: Tips are hardcoded in the `bobTips` JS array inside `index.html`. Do not fetch external APIs to retrieve tip lists; keep the logic self-contained.
