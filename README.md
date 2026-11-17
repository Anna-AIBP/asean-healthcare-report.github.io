# When, Not If

AIBP (ASEAN Innovation Business Platform) report on cybersecurity in ASEAN healthcare, published in partnership with the Healthcare CyberSecurity Technology Alliance (HCTA).

This repository holds the web version of the report as a single self-contained page. All photos, logos and flags are built into `index.html`; the only external files are the Crimson Pro and Lato fonts from Google Fonts.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The full report |
| `.nojekyll` | Tells GitHub Pages to serve the file as it is |
| `robots.txt` | Asks search engines not to index the site while it is a draft |

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `when-not-if`.
2. Upload the three files above (Add file → Upload files), then commit.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
5. After a minute or two, the report is live at `https://<your-account>.github.io/when-not-if/`.

## Use an AIBP web address (optional)

1. In **Settings → Pages → Custom domain**, enter the address, for example `report.industry-platform.com`, and save.
2. Ask whoever manages the domain to add a DNS record: a `CNAME` from `report` to `<your-account>.github.io`.
3. When the check passes, tick **Enforce HTTPS**.

## Before launch

- The page is marked **noindex** and `robots.txt` blocks search engines. When the report is approved for public release, remove the `<meta name="robots" ...>` line from `index.html` and delete `robots.txt`.
- On GitHub's free plan, Pages sites are **public** to anyone with the link, even with noindex. Do not publish until every contributor and HCTA has approved their content, or use a paid plan with access control.

## Updating the report

Replace `index.html` with the new version and commit. The live page updates within a minute or two.
