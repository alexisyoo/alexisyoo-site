# alexisyoo.com — static site

Plain HTML/CSS, no build step. Deploy free on GitHub Pages.

## Files
- `index.html` — home
- `about.html` — about
- `contact.html` — contact (email link works now; the form needs a free Formspree account — see comment in contact.html)
- `style.css` — shared styles

## Deploy on GitHub Pages (free)
1. Create a new repo on GitHub (e.g. `alexisyoo-site`).
2. Upload these files to the repo root (drag-and-drop on github.com works, or `git push`).
3. In the repo: **Settings → Pages → Source → Deploy from a branch → main / (root)**.
4. Save. Your site goes live at `https://<username>.github.io/<repo-name>/` within a minute or two.

## Connecting alexisyoo.com later
Once you're ready to point your domain here instead of GitHub's default URL,
add a `CNAME` file (no extension) to the repo root containing just:

```
alexisyoo.com
```

Then in Hostinger's DNS zone editor, point the domain at GitHub Pages' IPs
and a CNAME for `www`. Ask Claude for the exact records when you get there.
