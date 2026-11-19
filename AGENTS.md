# AGENTS.md

## Cursor Cloud specific instructions

### What this repo is

This is a **GitHub profile README** repository (the repo name matches the account, so
GitHub renders `readme.md` on the profile page). It contains only static content:

- `readme.md` — the profile README that GitHub renders.
- `README.bak` — a backup of an earlier README version (not rendered).
- `slh-brand.png` — an image asset referenced by `README.bak`.

There is **no application source code, package manifest, test suite, build step, or CI**.
"Building/running the app" here means rendering the Markdown and confirming it looks correct.

### Previewing the README (the "app")

`grip` renders GitHub-flavored Markdown exactly as GitHub does. It is installed by the
update script (`pip install --user grip`) and lives at `~/.local/bin/grip`.

Run a live preview server:

```
export PATH="$HOME/.local/bin:$PATH"
grip readme.md 0.0.0.0:6419
```

Then open `http://localhost:6419/`.

Notes / gotchas:
- `grip` reaches out to GitHub's Markdown API for rendering; if the network is blocked it
  falls back to offline rendering, which is still fine for a visual check.
- Some badges (shields.io) and the GitHub-stats images load from external hosts, so they
  only appear when outbound network is available. Missing external images are not a repo bug.
- There is nothing to lint/test/build. To "verify a change", just re-render `readme.md` with
  `grip` and eyeball the affected section.
