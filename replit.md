# Portfolio Template

A modern, responsive static portfolio website for web developers and designers.

## Tech Stack

- Pure HTML5, CSS, and vanilla JavaScript
- Tailwind CSS (via CDN)
- Lucide Icons (via CDN)
- Simple Icons (via CDN)
- PostHog analytics (optional, requires API key)

## Project Structure

```
/
├── index.html                    # Main portfolio page
├── css/main.css                  # Custom styles
├── img/hero.jpg                  # Hero image
└── case-study/
    └── email-campaign/
        └── email.html            # Sample case study page
```

## Running the App

The app is served via Python's built-in HTTP server:

```bash
python3 -m http.server 5000 --bind 0.0.0.0
```

This serves the static files on port 5000.

## Deployment

Configured as a **static** deployment with `publicDir: "."`.

## Customization

- Update personal info, meta tags, and structured data in `index.html`
- Replace `img/hero.jpg` with your own hero image
- Add project images to the `img/` folder
- Configure PostHog analytics key in `index.html` (line ~138)
- See `readme.md` for full customization guide
