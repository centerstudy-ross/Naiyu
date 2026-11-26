# Nai Yu Doula Care

One-page website for Nai Yu Doula Care (Gabrielle Bass).

## Files

- `index.html` – the whole page (styles included)
- `favicon.svg` – browser tab icon
- `assets/nai-yu-logo.svg` – color logo (hero)
- `assets/nai-yu-logo-footer.svg` – light logo for the dark footer
- `assets/gabrielle.jpg` – portrait
- `assets/drawn/*.svg` – hand-drawn icons, vine divider, underline and portrait frame
- `assets/nai-yu-logo-black.svg`, `assets/nai-yu-logo-white.svg` – print / dark-background versions
- `assets/herbs/*.svg` – hand-drawn herb illustrations
- `CNAME` – custom domain for GitHub Pages (currently `naiyudoula.com`; edit or delete if you use a different domain)

## Editing

Everything you might want to change (text, rates, email, Instagram) is plain text in `index.html`. Open it in any text editor (or edit directly on GitHub), search for the words you want to change, and save.

To swap the portrait, replace `assets/gabrielle.jpg` with a new photo of the same name.

## Publish on GitHub Pages

1. Create a new repository on GitHub and upload everything in this folder (keep the folder structure).
2. In the repository go to **Settings → Pages**, set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
3. For the custom domain: at your domain registrar, point the domain to GitHub Pages
   (A records for the apex domain: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; and a CNAME record for `www` pointing to `<your-github-username>.github.io`).
   Then enter the domain under **Settings → Pages → Custom domain** and tick **Enforce HTTPS** once it's available.
