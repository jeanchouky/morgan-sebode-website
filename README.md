# Morgan Sebode — Counselling & Psychotherapy

Bilingual (FR/EN) counselling website for Morgan Sebode, a humanistic counsellor based in Vannes, Brittany, France.

## Tech Stack

- **Astro 6** — static site generator
- **Tailwind CSS v4** — utility-first styling via Vite plugin
- **i18n** — French (primary) + English, with Astro's built-in i18n routing
- **GitHub Pages** — deployed via GitHub Actions

## Project Structure

```
src/
  i18n/translations.ts   # All FR/EN content
  layouts/BaseLayout.astro # Base HTML layout with SEO/OG/Schema.org
  components/
    Header.astro          # Responsive nav with language toggle
    Footer.astro          # Site footer
    Section.astro         # Reusable section wrapper
  pages/
    index.astro           # FR Home
    about.astro           # FR About
    services.astro        # FR Services
    testimonials.astro    # FR Testimonials
    booking.astro         # FR Booking
    contact.astro         # FR Contact
    en/                   # English versions of all pages
```

## Pages

| French (default) | English       | Content                          |
|:-----------------|:------------- |:---------------------------------|
| `/`              | `/en/`        | Home — hero, services, issues    |
| `/about/`        | `/en/about/`  | Bio, qualifications, approach    |
| `/services/`     | `/en/services/` | All 6 service types + info     |
| `/testimonials/` | `/en/testimonials/` | 5 client testimonials      |
| `/booking/`      | `/en/booking/` | Psychologue.net CTA + FAQ       |
| `/contact/`      | `/en/contact/` | Contact info + form             |

## Development

```bash
npm install        # Install dependencies
npm run dev        # Start dev server at localhost:4321
npm run build      # Build to ./dist/
npm run preview    # Preview production build
```

## Deployment

The site deploys automatically to GitHub Pages when pushing to `main`, via the workflow in `.github/workflows/deploy.yml`.

To use a custom domain later, update `site` and `base` in `astro.config.mjs`.

## Features

- Mobile-first responsive design
- WCAG AA accessibility (skip links, semantic HTML, ARIA labels, focus management)
- Schema.org structured data (LocalBusiness, Person)
- Open Graph + Twitter Card meta tags
- Bilingual SEO with hreflang alternate links
- Sitemap generation
- Language toggle (FR/EN) in header
