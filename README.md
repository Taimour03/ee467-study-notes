# EE 467 — Morphological Image Processing study site

A single self-contained `index.html` — no build step, no dependencies to install.
Currently covers slides 1–33 of the "Morphological Image Processing" deck.

## One-time setup (GitHub Pages)

1. Go to https://github.com/new and create a repository (e.g. `ee467-study-notes`). Public repos get free Pages hosting; private works too if you have GitHub Pro/Team/Edu.
2. On the new repo's page, click **Add file → Upload files**, drag in `index.html` (and this `README.md`), then commit.
3. Go to **Settings → Pages** in the repo.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
6. Wait a minute or two, then your site is live at:
   `https://<your-username>.github.io/<repo-name>/`

## Updating it as you go through the course

Whenever you've covered more slides, two options:

**A — via the GitHub web UI (no git needed):**
Go to the file in your repo → pencil icon (Edit) → paste in the updated `index.html` content → commit. Pages redeploys automatically in a minute or two.

**B — via git, if you have it set up locally:**
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
# replace index.html with the updated version
git add index.html
git commit -m "Add slides 34-45"
git push
```

In either case: bring me the current `index.html` plus the new slide content in a chat, ask me to extend it, and I'll hand back an updated file with the new section(s) added — following the same pattern/comment block already at the top of the file — ready to re-upload.
