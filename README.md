# EvidenceOps (one-page site)

A minimal, professional one-page site for the SOC2 Type I + (Google Workspace + GitHub + Jira) PoV offer.

## Deploy with GitHub Pages (free)

### 1) Create a new GitHub account (you)
Open https://github.com/signup and create the new account.

### 2) Create a repo (you)
Create a public repo named either:
- `<username>.github.io` (recommended), or
- any repo name (e.g. `evidenceops-site`)

### 3) Push the files (you)
From this folder:

```bash
cd evidenceops-site

git init
git add .
git commit -m "Initial EvidenceOps site"

git branch -M main
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

### 4) Enable GitHub Pages (you)
In GitHub repo settings:
- Settings → Pages
- Build and deployment: **Deploy from a branch**
- Branch: `main` / `/ (root)`

Your site will be available at the Pages URL GitHub shows.

## Customize

- `index.html`
  - Replace the booking link in the CTA.
  - Replace `hello@example.com` with your real email.

- `styles.css`
  - Styling only.
