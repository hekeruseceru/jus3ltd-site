# JUS3 LTD — Simple Static Site
This is a minimal static site ready for GitHub Pages.

## Quick start
1. Create a new GitHub repository (any name).
2. Upload these files to the repository.
3. In **Settings → Pages**, choose **Build and deployment: Deploy from a branch** and select the `main` branch, folder `/root`.
4. Add your custom domain (recommended: `www.jus3ltd.com`) and enable **Enforce HTTPS**.

## Custom domain
- If you plan to serve at **www.jus3ltd.com**, keep the `CNAME` file as-is.  
- If you prefer a different subdomain, update the `CNAME` file with that subdomain.
- If you use the **apex** (root) domain `jus3ltd.com`, you can either:
  - Point A records to GitHub’s IPs (see guide), or
  - Use a URL redirect from `jus3ltd.com` → `www.jus3ltd.com` at your registrar.

Edit `index.html` and `assets/style.css` to customize content and styles.
