# Living Legacy Programme — Mockup

Static HTML mockup for the **Living Legacy Programme** landing page, prepared for the IIT Bombay Development Relationship Foundation (IITB-DRF) Office of the Dean, ACR.

**Design variant:** Option A — Gold & Navy

## Live preview

GitHub Pages: `https://blustreamin.github.io/living-legacy-mockup/`
*(URL becomes active a minute or two after Pages is enabled in repo settings.)*

## Structure

```
.
├── index.html              # Single-page mockup
├── assets/
│   ├── logo.svg            # IIT Bombay logo
│   └── fonts.css           # Google Fonts (Cormorant Garamond + Jost)
└── README.md
```

## Notes

- Hero background image is hotlinked from the live `acr.iitbombay.org` site. Replace with a local asset before going to production.
- Fonts (Cormorant Garamond, Jost) load from Google Fonts CDN.
- No build step — pure HTML/CSS, opens directly in any browser.

## Local preview

```bash
# From the repo root
python3 -m http.server 8000
# then open http://localhost:8000
```

---

Prepared by **Blustream Marketing Solutions** for IITB-DRF.
