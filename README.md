# Юлія Кудренко — Landing Page

Static one-page site for psychologist Yuliia Kudrenko, plus a public offer agreement page.

## Files

- `index.html` — the landing page (hero, about, education/certificates, services, MAK card decks, process, approach, testimonials, FAQ, booking/contact, footer). Single self-contained HTML file with inline CSS/JS, no build step.
- `dogovir.html` — Договір публічної оферти + Контракт на клієнт-терапевтичні стосунки (public offer contract and client-therapy agreement), linked from the FAQ and footer of `index.html`.
- `Yuliya.jpg` — profile photo used in the hero and about sections.
- `certs/` — certificate/diploma images shown in the Education section, referenced by `cert1.jpg`–`cert10.jpg`.

## Contact channels

Booking and inquiries go through Telegram (`@indulgenk`) and Instagram (`@pani_psykholohynia`) — no third-party booking platform is referenced on the site.

## Deploying

No build step. Serve the directory as static files (e.g. GitHub Pages, Netlify, or any static host) with `index.html` as the entry point.

To preview locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.
