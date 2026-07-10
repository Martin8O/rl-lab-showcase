# RL Lab — showcase site

Static marketing / showcase site for **[RL Lab](https://github.com/Martin8O/RL-Lab)**, served via GitHub Pages.

- `index.html` — for learners (watch / play / teach)
- `technical.html` — engineering deep-dive
- `assets/` — GIFs, screenshots, hero art

No build step: plain HTML + CSS + media. `.nojekyll` disables Jekyll processing so asset
folders are served verbatim.

## Deploy (GitHub Pages)

1. Create a repo named `rl-lab-showcase` on GitHub (empty, no README).
2. `git remote add origin https://github.com/Martin8O/rl-lab-showcase.git`
3. `git push -u origin main`
4. Repo → **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)`**.

Live at **https://martin8o.github.io/rl-lab-showcase/**.

> The "Sponsor on GitHub" button starts working once GitHub Sponsors is enabled on the account.
