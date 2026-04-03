# Morgan Sebode Counselling — Website Brief

## Overview
Build a modern, bilingual counselling website for Morgan Sebode, a humanistic counsellor relocating from London to Vannes, Brittany, France. The site must serve both French and UK clients.

## Target: GitHub Pages (free hosting)
- Static site, no server-side rendering needed
- Use a modern static site approach (HTML/CSS/JS or a lightweight framework like Astro)
- Must work on GitHub Pages with custom domain later

## Key Requirements

### 1. Bilingual (French primary, English section)
- French is the PRIMARY language (landing page in French)
- English version accessible via language toggle
- Clean URL structure: `/` (French), `/en/` (English)

### 2. Pages / Sections
- **Home** — Hero with professional photo placeholder, tagline, CTA to book
- **About / À propos** — Bio (adapt from current site), qualifications, BACP membership
- **Services / Prestations**:
  - Individual therapy (adults)
  - Children & adolescents
  - Autistic individuals
  - 🆕 Family therapy
  - 🆕 Couple therapy
  - Online counselling (for UK clients)
- **Testimonials / Témoignages** — Adapt existing testimonials
- **Booking / Rendez-vous** — Embed or link to Psychologue.net booking + standalone booking option
- **Contact** — Location in Vannes + online availability for UK, contact form or email link

### 3. Online Booking
- Embed Psychologue.net profile/booking widget if available
- OR provide a prominent "Book on Psychologue.net" button linking to: https://www.psychologue.net/cabinets/morgan-sebode
- Future: may add Calendly or custom booking

### 4. Design
- Modern, warm, professional — think calm therapy vibes
- Colour palette: soft, calming tones (sage green, warm beige, soft blue — suggest options)
- Mobile-first responsive
- Accessibility: WCAG AA compliant
- Clean typography (Google Fonts — something warm and readable)

### 5. SEO
- Bilingual meta tags and Open Graph
- Schema.org structured data for local business (Vannes) + online service (London)
- Target keywords:
  - FR: "psychologue Vannes", "thérapie Vannes", "counselling en ligne", "thérapeute Bretagne"
  - EN: "counsellor online London", "English speaking therapist France", "counselling online UK"

### 6. Content from existing site
Adapt from https://morgansebodecounselling.co.uk/:
- Bio and qualifications
- Humanistic approach description
- Children/adolescents section
- Autistic individuals section
- Testimonials (5 existing ones)
- Issues list (anxiety, depression, grief, etc.)

### 7. Session details
- Standard 50-minute sessions
- In-person: Vannes, Brittany
- Online: Available for UK and international clients
- Bilingual: Sessions available in English and French

## Tech Stack
- Static HTML/CSS/JS (or Astro if it helps with i18n)
- Tailwind CSS for styling
- No build step required for GitHub Pages OR use GitHub Actions for build
- Responsive, mobile-first
- Fast loading, minimal dependencies

## Deliverables
1. Complete working site in this repo
2. GitHub Actions workflow for GitHub Pages deployment
3. All content in both French and English
4. README with setup instructions

## Domain (future)
- Target: morgansebode.com (not purchased yet)
- For now: will be served from GitHub Pages default URL
