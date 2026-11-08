# caminoltd.github.io

Student lab preparation pages, served at https://caminoltd.github.io

| Path | Purpose |
|---|---|
| `/lab-preparation/` | Lab preparation checklist (all courses) |
| `/<course>/` | Course page (cpda, ccsa, ccse, ccta, ccte, ctps, cces, cpvs, ccma); list files under `resources:` |
| `/common/` | Shared Skillable help + PDFs |

## Files to add
- `common/keyboard-timezone.pdf` (was Skillable-Labs-Keyboard-Timezone-Change.pdf)
- `common/navigation.pdf` (was Skillable-Labs-Navigation.pdf)
- `ccse/topology.png` (only if publishing is cleared; then uncomment the section in `ccse/index.md`)

## Adding a course
Edit the `steps:` list at the top of `lab-preparation/index.md`. Put course-specific files (e.g. topology.pdf) in a course folder such as `ccte/` and link them from the Reference section.

## Rules
- Never commit Training Keys or student names (the repo is public and git keeps history).
- Keep filenames stable; replace files in place so existing links keep working.
- Pages carry `noindex` so they stay out of search engines.

## Course pages
Course names/order live in `_data/courses.yml`. Each course folder has `index.md` with a `resources:` list (label + url). Drop the file (e.g. `topology.pdf`) into the course folder and add it to the list.
