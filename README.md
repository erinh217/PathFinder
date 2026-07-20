# PathFinder

**You know the destination. PathFinder gets you there.**

AI-driven meeting intelligence that auto-extracts decisions, ranks priorities, and syncs deliverables in real time. A Project Manager dashboard for full visibility. A Team Member view built for focused execution. No noise, just the next move.

> This repository contains a front-end prototype/demo of the PathFinder concept — a single, self-contained HTML file with no backend. It's meant for demoing the UX and product concept, not as a production application.

---

## Preview

*(Add a screenshot or GIF of the dashboard here — e.g. `docs/screenshot-dashboard.png`)*

```md
![PathFinder dashboard](docs/screenshot-dashboard.png)
```

## What's inside

- **Project Manager view** — project dashboard with live stat cards, task distribution and completion charts, a ranked Top 5 Priorities list, meeting notes, deliverables, team progress, and system preferences.
- **Team Member view** — a personal dashboard with notifications, upcoming deadlines, a personal task breakdown chart, and a task list that can be filtered between personal and team tasks.
- **Interactive detail modals** — clicking a task, notification, priority, or deadline opens a detail popup with full context.
- **Live status sync** — marking a task complete updates its badge everywhere it appears (task lists, priorities, deadlines) and recalculates the relevant stat-card numbers and charts on both the PM and Team Member views, computed directly from the task data rather than hardcoded.

## Tech stack

- Plain HTML, CSS, and vanilla JavaScript — no build step, no framework, no dependencies to install
- [Chart.js](https://www.chartjs.org/) (via CDN) for the dashboard charts
- [Inter](https://fonts.google.com/specimen/Inter) (via Google Fonts CDN) for typography

All data in the demo (meeting notes, tasks, team members, deliverables) is sample/placeholder content.

## Running it locally

No installation required — it's a single static file.

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```
2. Open `index.html` directly in your browser, **or** serve it locally:
   ```bash
   python3 -m http.server 8000
   ```
   then visit `http://localhost:8000`.

## Viewing it live (GitHub Pages)

This repo is set up to work with GitHub Pages out of the box:

1. Push this repo to GitHub (see below).
2. In the repo, go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder, then **Save**.
4. GitHub will publish it at `https://<your-username>.github.io/<your-repo>/` within a minute or two.

## License

MIT — see [LICENSE](LICENSE).
