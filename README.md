# Beaver Guild website

Static website for Beaver Guild: practical learning and trainer development for AI and technology through apprenticeship, starting with Notion.

Plain HTML and CSS, with no build step. Netlify serves this folder as it is.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Home |
| `pathways.html` | Tutorial Island, the practitioner and trainer pathways, and achievement badges |
| `challenges.html` | Industry challenges and buildathons |
| `about.html` | About Beaver Guild and the founder |
| `get-involved.html` | Audiences, interest form (mock-up) and FAQs |
| `404.html` | Not-found page |

## Assets

- `assets/css/site.css`: fonts and base styles. Page layouts use inline styles.
- `assets/fonts/`: Fraunces SemiBold, Figtree Regular and SemiBold, Pixelify Sans Regular, with their SIL Open Font Licence files.
- `assets/img/`: logo (Figtree SemiBold master), Guild Artisan poses, RPG world art and achievement badges from the Beaver Guild brand asset library.

## Deploy on Netlify

1. In Netlify, choose **Add new site → Import an existing project**, then pick this GitHub repository.
2. Leave the build command empty. The publish directory is the repository root (`netlify.toml` sets it).
3. Deploy. Every push to the main branch redeploys the site.

## Before launch

- The interest form on `get-involved.html` is a mock-up and sends nothing. Connect it to Netlify Forms or another destination, and add privacy wording.
- Confirm permission from everyone in `assets/img/ttt-batch-1.jpg` before publishing.
- Brand rules: Beaver Guild | Visual Identity & Writing Guide (Notion).
