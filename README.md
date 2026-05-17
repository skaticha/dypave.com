# DynaPave Consulting Website Template

This is a simple static website template for DynaPave Consulting LLC.

## Files

- `index.html` — main website file
- `styles.css` — website styling

## How to upload to GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and `styles.css` to the repository.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.
6. Add your custom domain under **Settings → Pages → Custom domain**.
7. In Cloudflare DNS, point your domain to GitHub Pages.

## Edit before publishing

Replace:
- `info@dynapave.com` with your real email address.
- About text with your official company bio.
- Services with your exact service offerings.
- Disclaimer language as needed.

## Recommended DNS records for GitHub Pages

A records for root domain:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

CNAME for `www`:

- `yourgithubusername.github.io`

Use **DNS only** in Cloudflare for these records.
