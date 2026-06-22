# Personal Website

Shadow (Tengyang Deng) — AI Researcher personal portfolio site.

## Quick Deploy to GitHub Pages

### Step 1: Create a GitHub repo
```
Repo name: <your-username>.github.io
```
This naming convention automatically enables GitHub Pages at `https://<your-username>.github.io`.

### Step 2: Push the files
```bash
git init
git add .
git commit -m "init: personal site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages (if not auto-enabled)
Go to: Repo → Settings → Pages → Source: Deploy from branch → Branch: main / root → Save

Your site will be live at `https://<your-username>.github.io` within ~1 minute.

## Customization Checklist

- [ ] Replace `tdeng3@jhu.edu` with your actual email
- [ ] Update GitHub/Twitter/Scholar links in the sidebar
- [ ] Add your actual `cv.pdf` to the repo root
- [ ] Update blog post titles/dates with real links
- [ ] Replace `<your-username>` throughout with your actual GitHub handle
- [ ] Add a favicon: `<link rel="icon" ...>` in the `<head>`
- [ ] Add Google Analytics if you want traffic data

## File Structure
```
/
├── index.html     ← everything is here (single file)
├── cv.pdf         ← your CV (place in root)
└── README.md
```

## Local Preview
```bash
# Option 1: Python
python3 -m http.server 8080

# Option 2: Node.js
npx serve .
```
Then open: http://localhost:8080
