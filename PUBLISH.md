# Publish your GitHub profile README

GitHub shows `README.md` on your profile only when it lives in a **public** repo named **exactly** your username:

`sashikantcodex/sashikantcodex`

## Option A — GitHub website (fastest)

1. Open https://github.com/new
2. Repository name: `sashikantcodex` (must match username)
3. Set **Public**, check **Add a README**
4. Create repository
5. Replace the default README with the contents of `README.md` in this folder
6. Commit — your profile updates within a minute

## Option B — Git CLI

```bash
cd /Users/sashikantasahoo/Desktop/WorkSpace/sashikantcodex
git init
git add README.md
git commit -m "Add GitHub profile README"
git branch -M main
git remote add origin https://github.com/sashikantcodex/sashikantcodex.git
git push -u origin main
```

If the remote repo does not exist yet, create it on GitHub first (empty, no README), then push.

## Customize later

- Edit the **typing banner** lines in the hero section
- Pin your three labs on GitHub: **Settings → Profile → Pin repositories**
- Add a profile photo and bio on https://github.com/settings/profile
