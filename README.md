# Yanwen Huang — Personal Homepage

Static personal site hosted on [GitHub Pages](https://pages.github.com/).

## Live site

After deployment, the site will be available at:

- **User site (recommended):** `https://winniehyww.github.io/`
- **Project site:** `https://winniehyww.github.io/<repo-name>/`

## Deploy to GitHub Pages

### 1. Create a GitHub repository

**Option A — Personal site (clean URL)**

1. On GitHub, create a new public repository named **`Winniehyww.github.io`** (must match your username exactly).
2. Do not add a README, `.gitignore`, or license when creating the repo.

**Option B — Project site**

1. Create any public repo (e.g. `homepage`).
2. The site URL will be `https://winniehyww.github.io/homepage/`.

### 2. Push this folder to GitHub

In PowerShell, from this directory:

```powershell
cd "e:\Course Material\2026SPRING\Homepage"
git remote add origin https://github.com/Winniehyww/Winniehyww.github.io.git
git branch -M main
git push -u origin main
```

Use your actual repo URL if you chose Option B.

### 3. Enable GitHub Pages

1. Open the repository on GitHub → **Settings** → **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Branch: **`main`**, folder: **`/ (root)`**.
4. Click **Save**. After 1–2 minutes, the site goes live.

### 4. Update the site later

```powershell
git add .
git commit -m "Update homepage"
git push
```

## Files published

- `index.html` — main page
- `styles.css`, `script.js` — styling and navigation
- `photo.jpg` — profile photo
- `.nojekyll` — disables Jekyll so static files are served as-is
