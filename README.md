# My_Portfolio

This is my portfolio website — a static site with HTML, CSS, JS and assets.

Contents:
- `index.html` — main page
- `assets/` — CSS, JS and fonts
- `images/` — images used on the site

How to use locally:
1. Open `index.html` in a browser.

How to add to GitHub (example commands):

```powershell
# initialize repo (if not already done)
git init
# create a branch called main if your Git defaults to master
git branch -M main
# add files and commit
git add .
git commit -m "Initial commit"
# create remote repository on GitHub and push (replace <owner> and <repo>)
# Option A: using gh CLI (interactive)
# gh repo create <owner>/<repo> --public --source=. --remote=origin --push
# Option B: create repo in GitHub web UI, then:
# git remote add origin https://github.com/<owner>/<repo>.git
# git push -u origin main
```

If you want, I can try to create the remote repo for you (I can use the `gh` CLI if it's installed and you're authenticated), or I can give step-by-step instructions.
