# HiOneOnly — hioneonly.com

Static marketing site (HTML + CSS) for the **HiOneOnly** platform.
Its purpose is to describe the platform and host the **Privacy Policy** and
**Terms & Conditions** required for the **TikTok Developer** app review.

The site is written in **English** because TikTok reviewers evaluate submissions
in English.

## Structure
```
hioneonly-site/
├── index.html      # home + platform description + "How we use TikTok"
├── privacy.html    # Privacy Policy (GDPR + TikTok requirements)
├── terms.html      # Terms & Conditions
├── css/
│   └── style.css   # shared styles for all pages
├── img/            # images (logo, photos...)
└── README.md
```

## URLs for the TikTok Developer Console
Once published on the production domain:

- Terms of Service: `https://hioneonly.com/terms.html`
- Privacy Policy:   `https://hioneonly.com/privacy.html`

## Company details (in the legal pages)
- **Operator:** Hidoly s.r.l.
- **Registered office:** Via Alessandro Riberi n. 4, 10124 Torino (TO), Italy
- **VAT / Tax code:** IT10678120014 — **REA:** TO-1153153
- **Court of jurisdiction:** Turin (Torino)
- **Contact email used on the site:** `areait@hidoly.com`
  (public alternatives from hidoly.com: `welcome@hidoly.com`, PEC `hidoly@legalmail.it`)

## View locally
Open `index.html` directly, or run a small local server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publishing
The site is fully static (no JS, no build step): publish on Netlify, Vercel,
GitHub Pages or the domain host, then point the `hioneonly.com` DNS to it.
