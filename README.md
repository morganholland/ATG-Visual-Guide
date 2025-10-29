# ATG Minimalistic Workout — Visual Guide (GitHub Pages)

Static single-page guide with grouped workouts, checkboxes, and demo links.

## Local preview
Open `index.html` in your browser.

## Deploy to GitHub Pages (project site)
1. Create a new repo on GitHub, e.g., `atg-visual-guide`.
2. Commit these files to the repo's **main** branch.
3. On GitHub: **Settings → Pages → Build and deployment**  
   - Source: **Deploy from a branch**  
   - Branch: **main** and **/(root)**  
   - Click **Save**.  
4. Your site will be live at: `https://<username>.github.io/atg-visual-guide/`

## Deploy as a user/organization site (optional)
- Name the repo exactly: `<username>.github.io`.
- Put `index.html` at the repo root and enable Pages as above.
- URL: `https://<username>.github.io/`

## Custom domain (optional)
1. In **Settings → Pages**, add your domain (e.g., `workouts.morgz.org`).
2. DNS:
   - **CNAME**: `workouts.morgz.org` → `<username>.github.io`
   - For apex domains, use ALIAS/ANAME or A/AAAA to GitHub Pages IPs (see GitHub docs).
3. Commit a `CNAME` file at repo root containing just your domain.
4. Enable **Enforce HTTPS** after the cert is issued.

## Notes
- `.nojekyll` is included to bypass Jekyll processing.
- Thumbnails load from YouTube; internet is required to see them.
- Update by editing `index.html`, commit, and push; Pages redeploys automatically.