# Katherine Cohen — personal website

Plain HTML and CSS, with no build step.

- `index.html`: About page (bio, photo, contact)
- `research.html`: papers
- `style.css`: shared styles for every page
- `assets/`: headshot and CV

## Publishing on GitHub Pages (free)

1. Create a GitHub account. Then create a new public repository named `<your-username>.github.io`.
2. Upload every file in this folder to the repository's main branch, keeping the same folder structure. The "Add file → Upload files" button works for this.
3. The site goes live at `https://<your-username>.github.io` within a minute or two.

## Custom domain (optional)

1. Buy a domain (for example, katherinecohen.com) from a registrar such as Cloudflare or Namecheap.
2. In the repository, open Settings → Pages → Custom domain, enter the domain, and check "Enforce HTTPS".
3. At the registrar, add the DNS records GitHub lists on that page: four A records for the root domain and a CNAME for `www`.

## Common updates

- **New CV:** replace `assets/Cohen_CV.pdf`, keeping the same file name.
- **New paper:** copy an existing `<div class="paper">` block in `research.html` and edit it.
- **Hobbies page:** copy `research.html` to `hobbies.html`, replace what's inside `<main>`, and uncomment the Hobbies link in the nav of every page.
