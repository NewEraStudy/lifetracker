# ⚡ Ayush · 90-Day Life Tracker

A personal daily task tracker built around a **3-month transformation plan** covering Health, Love, Happiness, and Money. All 91 days of tasks are pre-loaded from the action plan — just open it and start checking things off.

**Live demo:** `https://YOUR-USERNAME.github.io/life-tracker`

---

## What's Inside

- **Today Tab** — Week calendar strip, daily progress ring, filterable task list, add custom tasks
- **Overview Tab** — Completion stats, category progress bars, 7-day bar chart
- **Plan Tab** — Full 3-month phase breakdown (Weeks 1–13), click any week to jump to it
- **Streak counter** — Tracks consecutive days of 100% completion
- **Pre-seeded tasks** — All tasks from the 3-month plan are pre-loaded per date, covering:
  - Daily routine (guitar, journal, workout, study, business, sleep)
  - Day-of-week specific tasks (PPL workout split, A-Level study blocks, business sessions)
  - Week-specific focus tasks for all 13 weeks
- **localStorage persistence** — Your progress (checked tasks) is saved in the browser

---

## Deploy to GitHub Pages (3 steps)

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and click **New repository**
2. Name it `life-tracker` (or anything you want)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload the file

**Option A — GitHub Web (easiest):**
1. In your new repo, click **Add file → Upload files**
2. Drag and drop `index.html`
3. Click **Commit changes**

**Option B — Git command line:**
```bash
git init
git add index.html
git commit -m "Add life tracker"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/life-tracker.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. In your repo, go to **Settings → Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Under **Branch**, select `main` and `/ (root)`
4. Click **Save**
5. Wait 1–2 minutes, then visit: `https://YOUR-USERNAME.github.io/life-tracker`

That's it. Your tracker is live. 🚀

---

## How to Use

### Checking off tasks
Click the checkbox on the left of any task to mark it complete. Tasks grey out and strike through. Click again to uncheck.

### Navigating dates
Use the **week strip** at the top to move between days. Gold outline = selected day. Green dot = all tasks done. Gold dot = some tasks done.

### Adding custom tasks
Scroll to the bottom of **Today** tab → pick a category → type your task → press Enter or click **Add →**.

### Deleting tasks
Hover over any task → click the **×** button that appears on the right.

### Viewing your plan
Go to the **Plan** tab to see all 13 weeks. Click any week row to jump to that week in the Today view.

---

## Data & Privacy

All data is stored **locally in your browser** using `localStorage`. Nothing is sent to any server. Your progress is saved automatically on every interaction.

> ⚠️ Clearing your browser's localStorage or browsing in Incognito mode will reset progress. To back up, open browser DevTools → Application → Local Storage → copy the `ayush_tasks_v2` value.

---

## Plan Period

| Phase | Weeks | Dates | Theme |
|-------|-------|-------|-------|
| Foundation | 1–4 | Mar 9 – Apr 5 | Build the systems |
| Momentum | 5–8 | Apr 6 – May 3 | Stack wins, go deeper |
| Acceleration | 9–13 | May 4 – Jun 8 | Peak performance |

---

## Tech Stack

Single HTML file. No build tools. No frameworks to install.

- **React 18** via unpkg CDN
- **Babel Standalone** for JSX compilation
- **Google Fonts** (Cormorant Garamond, Syne, DM Mono)
- **localStorage** for data persistence

---

*Built for a 90-day transformation starting March 9, 2026.*
