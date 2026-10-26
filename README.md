# Miracle Ugokwe — Portfolio

Personal site of **Miracle C. Ugokwe (Mimisco)**, CEO & Lead Engineer at Mimisco Technologies & Resources.
Stablecoin payments, AI agents, data analytics, project & procurement management, and IT systems.

Live: https://miracle-ugokwe.vercel.app

## Structure

- `index.html` — the whole site in one file (styles, scripts and photos are embedded). Three.js loads from cdnjs for the hero scene.
- `favicon.png` — the Mimisco "M" mark.
- `public/` — CV (PDF) and older images.

## Contact form

The form works without setup: it prepares the visitor's note and sends it through WhatsApp or email.
To have notes delivered straight to your inbox, get a free access key at https://web3forms.com
(enter sirmimisco@gmail.com) and paste it into `const FORM_KEY = '';` in `index.html`.

## Run locally

```bash
python3 -m http.server 3000
```

## Deploy

Pushing to `main` redeploys on Vercel. To use a custom domain, add it under
Vercel → Project → Settings → Domains and follow the DNS instructions there.
