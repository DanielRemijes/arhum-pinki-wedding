# Arhum & Pinki · Wedding website

Invitation, save the date and travel planner for Arhum & Pinki's wedding,
28–29 January 2027, Gulmohar Royals, Cooch Behar.

## Files

| File | What it is |
|---|---|
| `index.html` | The whole site: page, styles and script |
| `assets/ap-logo-blue.webp` | Blue AP monogram |
| `assets/song-1m06.mp3` | Song loop, starts when the seal is tapped |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are |

No build step and nothing to install.

## Put it on GitHub Pages

1. On github.com, create a new **public** repository (for example `arhum-pinki-wedding`).
2. Click **Add file → Upload files**. Drag in everything inside this folder
   (`index.html`, the `assets` folder, `README.md`, `.nojekyll`), not the folder itself.
   Then click **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment* pick
   **Deploy from a branch**, branch **main**, folder **/ (root)**, and save.
4. After a minute the site is live at `https://<your-username>.github.io/arhum-pinki-wedding/`.

## Use your own domain

1. In **Settings → Pages → Custom domain**, type your domain (for example
   `www.arhumpinki.com`) and save. GitHub adds a `CNAME` file to the repo.
2. At the company where you bought the domain, add DNS records:
   - For `www.yourdomain.com`: a **CNAME** record for `www` pointing to `<your-username>.github.io`
   - For `yourdomain.com` without www: four **A** records pointing to
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
3. Wait for DNS to update (a few minutes to a few hours), then tick
   **Enforce HTTPS** in Settings → Pages. HTTPS is needed for the music and fonts on phones.

## Things you might change

- **WhatsApp number:** travel plans are sent to +91 70638 77923. Search `index.html`
  for `wa.me/917063877923` and replace the digits (country code first, no `+` or spaces).
- **Timetables** were checked in October 2026. Railways and airlines can change them,
  so a quick check before January is worth it.
