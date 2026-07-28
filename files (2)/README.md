# Tracy's Enchanted Storybook — Portfolio

Bilingual (EN/VI) interactive storybook portfolio for Vu Quynh Trang (Tracy),
built for a Sales Logistics job search.

This is a **single self-contained `index.html` file** — no build step, no
dependencies, no `npm install`. The photo, CV, and all three research papers
are embedded directly inside the file, so downloads work immediately with
no extra asset folders to manage.

## Deploy to GitHub Pages (5 minutes)

### 1. Create the repository
1. Sign in to GitHub with your account (`k622314410159-cmd`).
2. Click **New repository**.
   - For a personal homepage at `https://k622314410159-cmd.github.io`,
     name the repo exactly **`k622314410159-cmd.github.io`**.
   - For a project page instead (URL like `.../tracy-portfolio/`), name it
     **`tracy-portfolio`** — anything works, no code changes needed either way.
3. Make it **Public**. You can skip adding a README/template since you already
   have one here.

### 2. Upload the file
Easiest way (no git needed):
1. Open your new repo → **Add file → Upload files**.
2. Drag in `index.html` (and this `README.md` if you want it in the repo).
3. Commit directly to the `main` branch.

Or with git from your computer:
```bash
git init
git add .
git commit -m "Add Tracy's portfolio"
git branch -M main
git remote add origin https://github.com/k622314410159-cmd/REPO_NAME.git
git push -u origin main
```

### 3. Turn on GitHub Pages
1. In the repo, go to **Settings → Pages**.
2. Under **Build and deployment → Source**, choose **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)**. Click **Save**.
4. Wait 1-2 minutes, then open the URL GitHub shows you at the top of that
   page (or refresh it). Test in an incognito window on both desktop and
   mobile.

### 4. Updating later
Just re-upload the file (Add file → Upload files → replace `index.html`) or,
with git:
```bash
git add .
git commit -m "Update portfolio content"
git push
```
GitHub Pages redeploys automatically within a minute or two.

## Notes

- Everything (photo, CV, 3 research paper PDFs) is embedded as data inside
  `index.html`, so the Download / Preview buttons work the moment the page
  loads — nothing else to upload.
- If you ever want to swap the photo or a PDF, ping me with the new file and
  I'll regenerate `index.html` with it embedded.
- Before publishing, double check the Sales Logistics bullet points under
  Cam Thach Import-Export JSC — that role's exact duties should be reviewed
  by you since it isn't on your original CV.
