# Inviteory by harshh

Landing page for Inviteory: animated e-invites, graphics, illustrations, caricatures and SaaS projects.

Plain HTML and CSS. No build step and no dependencies (fonts load from Google Fonts).

## Structure

```
index.html        page content
styles.css        all styling (colors are CSS variables at the top)
assets/avatar.webp  profile picture in the About section
```

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deploy on GitHub Pages

1. Push this folder to a GitHub repo.
2. Repo Settings > Pages > Source: `main` branch, `/ (root)`.
3. Your site will be live at `https://<username>.github.io/<repo>/`.

## Common edits

- **Price:** search `799` in `index.html` (hero note and pricing section).
- **WhatsApp number:** search `919341781839` in `index.html`. Links use `https://wa.me/<country code + number>`.
- **Email:** search `street2search@gmail.com`.
- **Portfolio:** edit the three `.work` cards in the `#work` section. Add a link by wrapping the card in an `<a href="...">`.
- **Colors:** change the variables in the first `:root` block of `styles.css`.
