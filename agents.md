## Codex / Agent Instructions

This repository is deployed using **GitHub Pages (Jekyll + Sass)**.

### Hard constraints (do not violate)
- DO NOT use `clamp()`, `calc()`, or any CSS math that mixes `vw`, `vh`, `%`, and `rem` in `.scss` files.
- Prefer fixed `rem`, `px`, or `%` values.
- Responsive behavior must be handled via media queries only.
- Do NOT introduce modern CSS features that require newer Sass compilers.

### Styling rules
- Keep CSS conservative and compatible with GitHub Pages.
- Avoid refactors unless explicitly requested.
- Small, minimal changes only.

### Workflow rules
- Always open a Pull Request.
- Do NOT commit directly to `main`.
- Explain exactly what changed and why.
- If unsure, ask before modifying styles or configuration.

The goal is **stability first**, not modern CSS experimentation.
