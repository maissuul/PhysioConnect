# PhysioConnect

Static HTML demo (Arabic, RTL). Start at **login** → Patient goes to **Home**; Specialist locked to **Specialist** page.

## Run locally
Open `index.html` in your browser (double-click).

## Deploy to GitHub Pages
1. Create repo `PhysioConnect` on GitHub.
2. Upload `index.html` (or push via git).
3. Settings → Pages → Source: *Deploy from a branch*, Branch: `main` (root).
4. Visit: `https://<username>.github.io/PhysioConnect/`

## Push via Git
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<username>/PhysioConnect.git
git push -u origin main
```
