# Setup, asset list, and launch checklist

Everything needed to publish the new `aman-720/aman-720` profile README.

---

## Files in this folder

| File                | Purpose                                                     |
| ------------------- | ----------------------------------------------------------- |
| `README.md`         | The literal markdown to ship as your profile README.        |
| `BANNER_PROMPT.md`  | Image-generation prompts and palette for the banner asset.  |
| `SETUP.md`          | This file — instructions, asset list, checklist.            |
| `assets/`           | Drop the rendered `banner.png` here before pushing.         |

---

## Assets to produce

- [ ] **`assets/banner.png`** — 1500×500 PNG rendered from `BANNER_PROMPT.md`. The only custom asset required.
- All other visuals (stats, top-langs, shields badges) are remote SVGs and need no local files.

## Badges + widgets used (already wired in `README.md`)

**Shields.io badges** (pre-filled for your handles):
- Website → `amanpandey.ai`
- LinkedIn → `amanpandeyy`
- X → `@aman_720`
- Email → `ping.aman720@gmail.com`

**github-readme-stats widgets** (theme: `tokyonight`, borderless):
- Stats card: `https://github-readme-stats.vercel.app/api?username=aman-720&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true`
- Top languages: `https://github-readme-stats.vercel.app/api/top-langs/?username=aman-720&hide_border=true&theme=tokyonight&layout=compact&langs_count=8`

If you want a different theme later, swap `theme=tokyonight` for one of: `dark`, `radical`, `nord`, `dracula`, `gruvbox`, `onedark`. Test in an incognito tab.

---

## Steps to go live

### 1. Render the banner
Follow `BANNER_PROMPT.md`. Save the final image to `assets/banner.png` in this folder. (If you'd rather launch without the banner, delete the `<img src="./assets/banner.png">` line from `README.md` — the rest works fine.)

### 2. Create the profile repo on GitHub
1. Go to `https://github.com/new`.
2. Repository name: **exactly `aman-720`** (must match your username — GitHub auto-detects this as the profile README repo).
3. Public. No README, no .gitignore, no license — empty.

### 3. Push from this folder
```bash
cd /Users/Aman/Documents/Projects/GitHub_profile
git init
git add README.md assets/
git commit -m "feat: initial profile README"
git branch -M main
git remote add origin git@github.com:aman-720/aman-720.git
git push -u origin main
```

If you use HTTPS instead of SSH, swap the `remote add` line for `git remote add origin https://github.com/aman-720/aman-720.git`.

### 4. Verify
Open `https://github.com/aman-720` in an incognito window. The README should be the first thing on the page, above the repo list.

---

## Pinned repository recommendations

### Pin these 4 (in this order)

1. **freqshield-vit** — push to public if it isn't already (`gh repo edit freqshield-vit --visibility public`). This is your strongest research signal.
2. **sp500-tft-forecasting**
3. **BasketIQ**
4. **Analysing-Personality-from-LinkedIn-Profile**

How to pin: profile page → "Customize your pins" → check exactly these four → Save.

### One-line README polish per pinned repo (do before pinning)

For each repo, edit the README's first line so a recruiter skim grasps the project instantly:

- **freqshield-vit** → first line: *"Frequency-domain adversarial defenses for Vision Transformers — reproducible pipeline with spectral diagnostics, ablations, and patch-attack evaluation."*
- **sp500-tft-forecasting** → first line: *"Temporal Fusion Transformers vs ARIMAX/LSTM baselines on S&P 500 returns — 450+ runs across 11 experiment phases, honest failure analysis."*
- **BasketIQ** → first line: *"Recommendation-system foundations on 32.4M Instacart transactions — Apriori association rules, RFM segmentation, K-Means, interactive dashboard."*
- **Analysing-Personality-from-LinkedIn-Profile** → first line: *"BERT fine-tuning for multi-label text classification (Big Five trait prediction) — multi-author project with comparative baselines."*

### Archive these (don't delete — archive preserves history but removes from active view)

Stale HTML learning sites (2022–2023):
- `WickedWheels-car-rentals`
- `aman-720-Norse-Gods_website`
- `ShoppingSite`
- `AutoProject_CarRentals`
- `Web-Development_CheetSheet-Site`

Toy / minimal projects:
- `Bagels-Game`
- `Python_RockPaperScissors`
- `number_guesser`
- `Python_`

**How to archive each one**: repo page → Settings → scroll to "Danger Zone" → "Archive this repository" → confirm. The repo stays visible with a clear `[Archived]` ribbon and stops counting as active work.

---

## Medium-term plan (next 2–4 weeks) — to back up the "Agentic AI / RAG" claim

The README currently makes honest forward-looking statements in the "Currently · Building" row. Harden them by shipping:

1. **One small RAG repo** — e.g., `rag-eval-harness` (a retrieval-evaluation toolkit for long-context QA). LangChain or LlamaIndex + a vector store + 3–4 evaluation metrics + a tiny test corpus. README should focus on what failed and why, not just what worked.
2. **One small agent repo** — e.g., `tool-use-playground` (a clean LangGraph or Claude tool-use demo with 2–3 real tools — calculator, web-search, code-exec — and an honest README about prompt-engineering tradeoffs).

Once either repo exists, demote one of the four current pins to make room and update the "Currently · Building" row to point at the actual repo.

---

## Pre-launch polish checklist

Before pushing the new README live:

- [ ] `assets/banner.png` exists at 1500×500 (or you've removed the `<img>` line if launching without a banner)
- [ ] All four contact badges click through to working destinations (open each in incognito)
- [ ] Stats card and top-langs card both load on `https://github-readme-stats.vercel.app/...` (the vercel endpoint occasionally cold-starts — refresh once)
- [ ] No broken image squares anywhere in the rendered README
- [ ] No typos (paste the markdown into a grammar checker once)
- [ ] `freqshield-vit` repo is public (otherwise the FreqShield-ViT featured section link is misleading)
- [ ] All nine stale repos in the "Archive these" list are archived
- [ ] Pinned repos are the four in the recommendation, in order

## Post-launch verification

- [ ] Open `https://github.com/aman-720` in two browsers (one logged out) — confirm README renders at the top
- [ ] Open on a phone — banner shouldn't crop strangely, tables shouldn't overflow
- [ ] **Recruiter 10-second test**: show the profile to one trusted friend for 10 seconds and ask what you do. Expected: "AI / RAG / agents / ML research." Failure mode: "data science student" or "web developer." If they say "passionate developer," something's wrong — iterate.
- [ ] LinkedIn headline updated to roughly match the README role line ("AI Systems Engineer · Agentic AI · RAG · Production ML · MS DSAE @ ASU") — cross-surface consistency matters more than people think

---

## Things to deliberately NOT do later

- Don't add a snake contribution graph, trophy widget, or visitor counter. They undo the minimal aesthetic and signal "junior portfolio."
- Don't invent metrics. Every number in the README must trace to a real result in a real repo.
- Don't rename existing repos to make the README look cleaner — the README handles display names (e.g., "Trait-BERT"); the repos stay as-is.
- Don't pile on more shields.io badges. Four contact badges is the cap.
- Don't stretch the "Currently · Building" row beyond what's actually in flight. Keep it honest; update it when reality changes.
