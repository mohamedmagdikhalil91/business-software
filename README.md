# Business Software — SRH Hochschule · IBA

A static course website for the **Business Software** module at SRH Hochschule (IBA programme). The course guides teams of two through a 7-day, project-based journey covering the essential business tools used after graduation — MS Office, data analysis, and Gemini AI.

## Live Course Page

The site is deployed via **GitHub Pages**. After every commit to the main branch it is automatically published at:

```
https://<your-github-username>.github.io/<repository-name>/
```

Replace `<your-github-username>` and `<repository-name>` with your actual GitHub username and repo name. You can also find the URL under **Settings → Pages** in your GitHub repository.

---

## Repository Structure

```
business-software/
│
├── index.html          # Landing page — company selection / course overview
├── style.css           # Shared stylesheet for all pages
├── _notes.md           # Instructor notes (content & data change reminders)
│
├── content/            # Day-by-day lesson pages
│   ├── day1.html       # Day 1 — Identity & Vision
│   ├── day2.html       # Day 2 — Professional Communications
│   ├── day3.html       # Day 3 — From Raw Data to P&L
│   ├── day4.html       # Day 4 — Business Math II
│   ├── day5.html       # Day 5 — The Virtual Office
│   ├── day6.html       # Day 6 — The Big Pitch
│   └── day7.html       # Day 7 — Final Pitch Day 🎤
│
└── portfolios/         # Fictional company profiles (one per team)
    ├── aura_motion.html
    ├── bytebite.html
    ├── green_threads.html
    ├── nomad_bean.html
    ├── urban_canopy.html
    ├── wordwise_global.html
    └── zenith_wellness.html
```

### Key pages

| Path                | Purpose                                                       |
| ------------------- | ------------------------------------------------------------- |
| `index.html`        | Course home — students pick their company to begin            |
| `content/day*.html` | Step-by-step lesson content for each session                  |
| `portfolios/*.html` | Company brief that each team works from throughout the course |

---

## Local Preview

Open `index.html` directly in any browser

---

## Deployment (GitHub Pages)

1. Push this repository to GitHub.
2. Go to **Settings → Pages** in the repo.
3. Under *Source*, select **Deploy from a branch** → `main` → `/ (root)`.
4. Click **Save**. GitHub will build and publish the site within a minute.
5. Every subsequent `git push` to `main` triggers an automatic redeploy.
