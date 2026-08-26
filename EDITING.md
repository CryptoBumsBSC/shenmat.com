# Editing the Shen Academy site

This is a plain static website. There is no WordPress, database or plugin layer.

## Main files

| Page | File |
| --- | --- |
| Home | `index.html` |
| All classes | `classes.html` |
| Kids karate | `classes/karate-kids.html` |
| Adult karate | `classes/karate-adults.html` |
| Boxing | `classes/boxing.html` |
| Boxing fitness | `classes/boxing-fitness.html` |
| MMA | `classes/mma.html` |
| Self-defence | `classes/self-defence.html` |
| Personal training | `classes/personal-training.html` |
| Timetable and fees | `timetable.html` |
| School programs | `school-programs.html` |
| About | `about.html` |
| FAQ | `faq.html` |
| Contact | `contact.html` |
| Areas hub | `areas.html` |
| Area pages | `areas/*.html` |
| Styling | `assets/site.css` |
| Images | `assets/img/` |

## Important data to keep consistent

When a class time or fee changes, update the relevant class page, `timetable.html`, any matching FAQ answer, structured data on that page and `llms.txt`.

Current core contact details used across the site:

- Shen Academy: 0409 858 304
- Venue: 63A Mount Street, Burnie TAS 7320
- MMA / Duelling Dragons enquiries: Franki or Callan — 0436 026 111

## Images supplied in this build

- `shen-academy-logo.webp` — main Shen Academy logo
- `hero-family.webp` — homepage hero artwork
- `shen-family-banner.webp` — full campaign banner
- `maa-accredited-2026.webp` — 2026 Martial Arts Australia Accredited School badge
- `og-cover.jpg` — Facebook/X/social share image
- `apple-touch-icon.png` — mobile home-screen icon
- `favicon.svg` — browser icon

Always keep useful alt text on meaningful images. Decorative images should use an empty alt attribute.

## SEO / AEO files

- `sitemap.xml` — public page list for search engines
- `robots.txt` — crawler rules
- `llms.txt` — concise academy facts for AI/search systems
- JSON-LD inside each HTML page — structured entity, FAQ, service and breadcrumb information

If factual details change, update the visible page and the matching structured/AI-readable copy so they never disagree.
