# Shyam Sunder Sahani — Portfolio

Personal portfolio website built with plain HTML/CSS/JS (no build step needed).

## Run locally
Just open `index.html` in a browser, or serve it:
```bash
cd portfolio
python3 -m http.server 8080
# visit http://localhost:8080
```

## Deploy on GitHub Pages
1. Create a new GitHub repo (e.g. `portfolio` or `your-username.github.io`).
2. Push this folder's contents to it.
3. In the repo: **Settings → Pages → Source → Deploy from branch → `main` / root**.
4. Site goes live at `https://your-username.github.io/portfolio/` (or `https://your-username.github.io/` if you named the repo `your-username.github.io`).

## Before deploying — fill these in
- [ ] Replace `github.com/` placeholder links in `index.html` (`#githubLink`, `#githubCard`) with your real GitHub profile URL.
- [ ] Add your resume PDF at `assets/resume.pdf` so the "Download Resume" button works.
- [ ] Optionally add a photo/avatar in `assets/img/` and reference it in the hero section.
