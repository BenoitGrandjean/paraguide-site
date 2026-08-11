# paraguide-site

Public pages for the Paraguide iOS app, served by GitHub Pages.

**This repo is public on purpose. The app's source stays private in `paraguide`.**

| Page | Why it exists |
|---|---|
| `index.md` | Landing page |
| `privacy.md` | Privacy policy — a **hard requirement** for App Store submission |
| `support.md` | Support URL — required on the App Store listing |

## Rules

- **Nothing but these pages goes in here.** No source, no backups, no logbook data. The reason this repo exists at all is so `paraguide` can stay private: `tools/mike_backup.json` in that repo contains a real pilot's 124 flights, and publishing it is not ours to undo.
- Content is edited **here**, not in the app repo. Keeping a second copy in `paraguide/docs/` would let the published policy drift from the one in the repo, and the published one is what users and Apple read.
- Re-check `privacy.md` whenever the app changes what it stores or which services it contacts. The date at the top is what tells a reader whether the policy still describes the app.
