
# Subramanya K N — Portfolio (GitHub Pages Ready)

This directory contains a ready-to-deploy static portfolio website for **Subramanya K N**.
The site is dark/navy themed and includes sections for About, Projects, Skills, Dashboard Gallery, and Contact.
The user's CV (Subramanya_S5.pdf) is included in the root for the "Download CV" button to work.

---

## Files
- `index.html` — Main website page
- `styles.css` — Styles for the site
- `Subramanya_S5.pdf` — CV (used by the Download CV button)
- `README.md` — This file

---

## How to publish on GitHub Pages (one-click)
1. Create a new GitHub repository named exactly: `Subramanya5.github.io` under your GitHub account `Subramanya5`.
2. In the new repo, upload all files from this folder (index.html, styles.css, Subramanya_S5.pdf, README.md).
   - You can drag-and-drop the files on the GitHub web UI or push via git.
3. Once files are on the `main` branch, visit: `https://subramanya5.github.io`
   - GitHub Pages will serve the site automatically from the repository root.
4. (Optional) To update content, edit `index.html` locally and push changes to the repo — the site will auto-update.

### Quick deploy via git (local)
```bash
# in your local machine
git init
git remote add origin https://github.com/Subramanya5/Subramanya5.github.io.git
git add .
git commit -m "Add portfolio site"
git branch -M main
git push -u origin main
```

---

## Replace placeholders
- Replace `avatar` placeholder in `index.html` with your profile image (filename and path) and re-deploy.
- Replace dashboard thumbnail(s) with high-resolution screenshots saved in the root and update `index.html` accordingly.

If you want, I can also guide you step-by-step while you deploy the site to your GitHub repository.
