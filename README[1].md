# Nebhan P — Portfolio Site

Personal BI/Data Analyst portfolio, built as a static site for GitHub Pages.

🔗 Live at: `https://your-github-handle.github.io/portfolio/` (once published — see steps below)

## What's inside

- `index.html` — all content (About, Projects, Skills, Contact)
- `style.css` — all styling
- `assets/` — put project screenshots here (e.g. `project-1.png`, `project-2.png`)
- `resume/` — put your resume PDF here (e.g. `Nebhan_P_Resume.pdf`)

## To customize

1. **Projects**: open `index.html`, search for `project-card`. Replace the title, tools, description, bullet points, and `<img src="assets/...">` paths for each of the 3 project slots.
2. **Screenshots**: drop PNG/JPG files into `assets/`, named to match what's referenced in `index.html`.
3. **Resume**: drop your PDF into `resume/` and make sure the filename matches the link in the nav bar (`Nebhan_P_Resume.pdf`).
4. **Contact links**: update the LinkedIn and GitHub URLs in the Contact section (currently placeholders — search for `your-linkedin-handle` and `your-github-handle`).

## To publish on GitHub Pages

See the step-by-step guide Claude gave you in chat. Short version:

```
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git push -u origin main
```

Then in the GitHub repo: **Settings → Pages → Source: Deploy from branch → main → /(root) → Save**.

Your site goes live at `https://YOUR-USERNAME.github.io/portfolio/` within a minute or two.
