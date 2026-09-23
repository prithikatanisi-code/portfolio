# Portfolio Website

A simple static portfolio (HTML, CSS, JS). No build step, no Node needed.

## 1. Edit your details
Open `index.html` and replace:
- `Your Name`, `Your City`, `you@example.com`
- `YOUR-USERNAME` in the GitHub and LinkedIn links
- The three project entries and the About text
Change colors at the top of `style.css`.

## 2. Test locally
Double-click `index.html` to open it in your browser.

## 3. Upload to GitHub
1. Create a **Public** repo on github.com (for example `portfolio`). Leave "Add README" unchecked.
2. In this folder run:

```bash
git init
git branch -M main
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git push -u origin main
```

Use a Personal Access Token as the password if asked (GitHub > Settings > Developer settings > Personal access tokens).

## 4. Turn on GitHub Pages
Repo > **Settings > Pages > Build and deployment > Source: GitHub Actions**.

The included workflow in `.github/workflows/deploy.yml` deploys on every push to `main`. Watch it in the **Actions** tab.

Your site: `https://YOUR-USERNAME.github.io/portfolio/`

Want it at `https://YOUR-USERNAME.github.io/`? Name the repo exactly `YOUR-USERNAME.github.io`.

## 5. Update later
```bash
git add .
git commit -m "Update portfolio"
git push
```

## Troubleshooting
- 404: `index.html` must be in the repo root.
- No styling: check file names and letter case.
- Deploy fails with a Pages error: set Source to **GitHub Actions** (step 4).
- Old version showing: wait 2 minutes, then Ctrl+Shift+R.
