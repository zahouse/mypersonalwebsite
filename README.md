# Zach Houseman Personal Website

This is a static personal website built with plain HTML and CSS. It's designed to be hosted on GitHub Pages.

## Structure

- `index.html` – home page
- `about.html`, `projects.html`, `contact.html` – other site pages
- `css/named_grid2.css` – site stylesheet
- `images/` – visual assets used throughout the site

All links are relative, so the site can be served from the repository root or a project subpath.

## Preparing for GitHub Pages

1. **Repository setup**
   - Create a new GitHub repository (e.g. `username.github.io` for user/organization pages, or any name for project pages).
   - Push all files from this folder into the repository.

2. **Disable Jekyll (optional)**
   - If you don't plan to use Jekyll processing, add an empty file named `.nojekyll` at the repository root. This repository already includes one.

3. **Deployment**
   - For a user/organization site, the content should live on the `main` (or `master`) branch's root.
   - For a project site, you can publish from the `gh-pages` branch or from `main`/`master` via the repository settings (Settings > Pages).

4. **Custom domain (optional)**
   - Add a `CNAME` file containing your custom domain if you have one.

5. **Testing locally**
   - You can use a simple HTTP server to preview the site before pushing:
     ```bash
     cd path/to/mypersonalwebsite
     python -m http.server 8000
     # or:  npx http-server .
     ```

The site is now ready to be pushed and activated on GitHub Pages when you're ready. Enjoy!