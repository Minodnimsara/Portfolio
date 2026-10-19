# Minod Nimsara — Motion & Graphic Design

Portfolio website. Plain HTML, CSS and JavaScript, no build step.

- `index.html` is the whole page
- `assets/` holds the profile photo, project videos and client feedback screenshots
- `.nojekyll` tells GitHub Pages to serve the files as they are

## Publish on GitHub Pages (free)

1. Create a new public repository on github.com. Name it `YOURUSERNAME.github.io` to get the address `https://YOURUSERNAME.github.io`, or any other name to get `https://YOURUSERNAME.github.io/REPO-NAME/`.
2. Open the repository, choose **Add file → Upload files**, and drag in everything from this folder: `index.html`, `.nojekyll`, `README.md` and the whole `assets` folder. Commit the upload.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, pick the `main` branch and the `/ (root)` folder, then save.
4. Wait one to two minutes, then open your address.

Every path in the site is relative, so it works at either address.

## Add or remove videos and screenshots later

Open `/admin.html` on your live site (for example `https://YOURUSERNAME.github.io/admin.html`).

1. Create a fine-grained token at https://github.com/settings/personal-access-tokens/new. Choose only this repository, and set Repository permissions → Contents to Read and write.
2. Paste the token into the admin page once and press Connect.
3. Add projects and screenshots, or delete old ones. Each change is saved to the repository, and the live site updates in one to two minutes.

The admin page does nothing without your token, so visitors cannot change the site.
