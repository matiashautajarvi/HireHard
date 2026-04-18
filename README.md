# HireHard — landing

Static marketing page for HireHard (Tailwind via CDN). Deploy anywhere that serves static files.

## Local preview

Open `index.html` in a browser, or run a static server from this folder (for example `npx serve .`).

## Deploy on Vercel

1. Push this repository to GitHub.
2. In Vercel: **Add New Project** → import the repo.
3. **Framework preset**: Other. Leave **Build Command** empty. **Output directory**: `.` (repository root).
4. Deploy. After you have a production URL, update Open Graph / Twitter `meta` tags in `index.html` if you want correct share previews.
