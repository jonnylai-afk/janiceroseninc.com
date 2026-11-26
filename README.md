# janiceroseninc.com

Website for Janice Rosen Inc., Vancouver, BC. A single static page hosted on GitHub Pages.

## Files
- `index.html`: the whole site (styles and script inline)
- `img/`: photos (free Unsplash images; photographers credited in the footer)
- `logo/`: logo files (SVG)
- `favicon.svg`, `CNAME` (custom domain), `.nojekyll`

## Contact form
The enquiry form posts to Formspree. The form ID is in the form `action` in `index.html`
(`https://formspree.io/f/<form-id>`). Submissions are emailed to the address set in Formspree.

## Updating the site
Edit `index.html` (or replace a photo in `img/`), commit to `main`, and GitHub Pages republishes within a minute or two.

## Hosting
- GitHub Pages: Settings > Pages > Deploy from branch `main` / root, custom domain `janiceroseninc.com`, Enforce HTTPS on.
- DNS at GoDaddy: A `@` to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; CNAME `www` to `jonnylai-afk.github.io`.
