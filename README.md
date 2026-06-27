Portfolio — Oluwapelumi Omikunle
Clean, minimal, data-analysis-focused portfolio site. Plain HTML/CSS/JS —
no build step, loads fast, deploys straight to GitHub Pages.
Before you push
Open `index.html` and update these placeholders:
`mailto:youremail@example.com` → your real email
`https://linkedin.com/in/your-handle` → your LinkedIn URL
The four `href="#"` on "View case study →" links → links to your live
dashboards, PDFs, or write-ups (or remove the link if a project has none yet)
Deploy to GitHub Pages
Create a new repo on GitHub (e.g. `portfolio` or `yourname.github.io`).
From this folder:
```
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
On GitHub: go to Settings → Pages.
Under "Build and deployment", set Source to `Deploy from a branch`,
branch `main`, folder `/ (root)`. Save.
Your site goes live at:
`https://<your-username>.github.io/<repo-name>/` (normal repo), or
`https://<your-username>.github.io/` (if the repo is named
`<your-username>.github.io`)
Pages usually goes live within a minute or two of the first deploy.
Files
`index.html` — structure and content
`style.css` — all styling (design tokens at the top of the file)
`script.js` — typed terminal line + scroll-reveal animation
