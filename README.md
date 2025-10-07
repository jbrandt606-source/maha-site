# MothersAgainstHerbalAbuse.org

This repo hosts the MAHA advocacy landing page on **GitHub Pages**.

## Quick Start

1. Create a new GitHub repository (public) and upload these files.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Set **Branch** to `main` and **/ (root)`**. Save.
5. In **Custom domain**, enter `MothersAgainstHerbalAbuse.org` (or `www.MothersAgainstHerbalAbuse.org`). Save.
6. In your domain registrar's DNS:
   - **Recommended**: Use the `www` subdomain.
     - Create a CNAME: `www` → `<your-username>.github.io`.
     - Set your apex domain to redirect/forward to `www` in your registrar dashboard.
   - **Advanced (apex only)**: Add A/AAAA records for GitHub Pages as documented by GitHub.
7. Back in GitHub Pages, ensure **Enforce HTTPS** is checked once the certificate is ready.

That's it! The site will be live on your custom domain.
