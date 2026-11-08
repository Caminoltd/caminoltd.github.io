# caminoltd.github.io

Student lab preparation pages, served at https://caminoltd.github.io

| Path | Purpose |
|---|---|
| `/ccse/` | CCSE R82 lab preparation (action plan) |
| `/common/` | Shared Skillable help + PDFs |

## Files to add
- `common/keyboard-timezone.pdf` (was Skillable-Labs-Keyboard-Timezone-Change.pdf)
- `common/navigation.pdf` (was Skillable-Labs-Navigation.pdf)
- `ccse/topology.png` (only if publishing is cleared; then uncomment the section in `ccse/index.md`)

## Adding a course
Copy `ccse/` to e.g. `ccte/`, edit `index.md`, add a row to the table in the root `index.md`.

## Rules
- Never commit Training Keys or student names (the repo is public and git keeps history).
- Keep filenames stable; replace files in place so existing links keep working.
- Pages carry `noindex` so they stay out of search engines.
