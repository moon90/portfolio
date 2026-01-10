# Deploy Options

## GitHub Pages
1. Create a repo named `portfolio` (or any name).
2. Commit `index.html`, `style.css`, and the `assets/` folder.
3. In **Settings → Pages**, set:
   - Source: `Deploy from a branch`
   - Branch: `main` (root)
4. Wait for the page to build. Your site will be served from the Pages URL shown there.

## GitLab Pages
1. Commit `index.html`, `style.css`, `assets/` and `.gitlab-ci.yml` to your GitLab repo.
2. Use `main` or `master` branch. The pipeline will publish under `https://<group>.gitlab.io/<project>/`.

## Custom Domain
- Add a CNAME file with your domain name and configure DNS to point to GitHub/GitLab Pages.
