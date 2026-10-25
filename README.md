# Abdiwali Yasin — Portfolio

A responsive White + Soft Blue portfolio, with a **local-only** dashboard.

## Start
1. Extract the ZIP.
2. Open `index.html` in Chrome or Edge.
3. Click **My Dashboard** to add public contact details, projects, short notes and a learning plan.
4. Open `index.html` again to see the changes **in the same browser**.

## Important limitations
- Dashboard uses browser `localStorage`, not a cloud database. No login, authentication or secure private storage is included.
- Do not store passwords, identity documents, sensitive financial data or secrets.
- Data does not automatically sync between devices or to GitHub Pages. Export a JSON backup regularly. If you deploy the website, manually update public content in source files and redeploy.
- Replace the placeholder contact email before publishing. Default email button is disabled until configured in the local browser.
- Sample projects are descriptions, not claims of deployed working demos. Add real links when available.

## Publish public portfolio on GitHub Pages
Create a public GitHub repository, upload `index.html`, `style.css`, `script.js` (and other public assets you choose), then go to Settings → Pages → Deploy from a branch → main / root. Do **not** publish `dashboard.html`/`dashboard.js` as a secure private area; these files provide no authentication. For a true online admin dashboard, a backend, user authentication, database and authorization rules are needed.

## Customize
Edit `index.html` for your biography, skill level, education and sample projects. Edit CSS variables at top of `style.css` to change colors. The AY monogram is a placeholder for a profile image.
