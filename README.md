# CareFlow 🚑

An AI-powered hospital operations platform concept built for **Hackachusetts 2026** (Healthcare & Biotech Track).

CareFlow helps hospitals identify bottlenecks, coordinate available resources, and reduce unnecessary patient waiting.

## Pages

This is a static multi-page site:

| Page | File | Description |
|------|------|-------------|
| **Home** | `index.html` | Landing page with project overview and navigation |
| **Operations Diagram** | `diagram.html` | Patient-flow research: Little's Law, queueing theory, live dashboard mockup, transfer coordination, and an interactive capacity simulator |
| **App Preview** | `app-preview.html` | Three iPhone screens — Emergency SOS, ambulance tracking, and live hospital capacity data (React Native + Expo mockup) |

Every page shares a common top navigation bar so the whole thing works as one website.

## Deploying to Vercel

This is a zero-config static site. To deploy:

1. Push this repo to GitHub (already done).
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → import this repository.
3. Framework preset: **Other** (no build step needed).
4. Deploy. Vercel serves `index.html` as the homepage automatically.

`vercel.json` enables clean URLs (e.g. `/diagram` instead of `/diagram.html`).

## Local preview

Just open `index.html` in a browser, or run a simple static server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

---

*All data shown is simulated for demo purposes only. Not real hospital, patient, or EMS information.*
