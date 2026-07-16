# maid-in-indy-landing-
Responsive landing page for Maid in Indy, an Indianapolis-area residential cleaning company — built with plain HTML/CSS/JS, no dependencies.
# Maid in Indy — Landing Page

A single-page marketing site for **Maid in Indy**, a residential cleaning business serving Indianapolis and Zionsville, Indiana.

🔗 Live demo: *(add your GitHub Pages / hosting URL here once deployed)*

## About

This landing page was built to give the business a professional, welcoming web presence — introducing their services, building trust with prospective customers, and making it easy to get in touch for a quote.

**Highlights:**
- Custom hero animation: a foggy-to-clean "squeegee wipe" reveal that reflects the "cleaning you can see" brand line
- Full breakdown of core services (standard, deep, spring cleaning) and specialty services (move-in/move-out, post-construction, event cleanup, appliance and window/wall washing)
- Trust-building sections: why-choose-us, testimonial, and service area
- Fully responsive layout, accessible focus states, and reduced-motion support
- No build tools or frameworks required — plain HTML, CSS, and JS

## Project Structure

```
maid-in-indy-site/
├── index.html      # Page markup and content
├── css/
│   └── styles.css  # All styling, layout, and animation
└── js/
    └── script.js    # Reserved for future interactivity (currently a stub)
```

## Getting Started

No build step needed — it's a static site.

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
2. Open `index.html` directly in a browser, or serve it locally:
   ```bash
   python3 -m http.server 8000
   ```
   then visit `http://localhost:8000`.

## Deployment

This site can be hosted for free with **GitHub Pages**:

1. Go to the repo's **Settings → Pages**.
2. Under "Build and deployment," set the source to the `main` branch (`/root`).
3. Save — GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/`.

## Customization

- **Content:** edit the text directly in `index.html`.
- **Colors and type:** all design tokens (colors, fonts) are defined as CSS variables at the top of `css/styles.css`.
- **Contact info:** update the phone number and email in the header, hero, CTA, and footer sections of `index.html`.

## Credits

Built with care for Maid in Indy. Fonts via Google Fonts (Fraunces, Inter, JetBrains Mono).
