# Yatharth Hospital Information Guide — Static Web 2.0 starter

## Pages
- `index.html`: Home page with four main content sections (specialities, patient preparation, facilities/care journey, next steps) plus hero.
- `about.html`: About page with three main sections (purpose, principles, editorial/medical disclaimer).
- `blog.html`: Blog landing-page structure only. It has category placeholders and an empty state; no blog posts are published.
- `style.css`: Responsive shared styling.
- `script.js`: Mobile navigation.

## Important publishing note
This is an independent information resource, not the official Yatharth Hospitals website. Verify all hospital-specific details, services, doctors, locations, timings, pricing and contact information with official sources. Do not imply affiliation or use hospital logos/brand assets without permission. Medical information should be reviewed by a qualified professional.

## Deploy with GitHub + Netlify
1. Upload the project files to the root of a GitHub repository. Keep `index.html` at the root.
2. In Netlify choose Add new project → Import an existing project → GitHub.
3. Select your repository and branch (`main`).
4. Leave Build command blank and set Publish directory to `.`.
5. Deploy. Future pushes to the connected branch trigger automatic redeployment.

## Before launch
- Replace `hello@example.com` with a monitored editorial contact, or remove that sample email link.
- Replace placeholder social links.
- Confirm image usage/licensing for your intended publication; images are remote Unsplash URLs.
- Replace generic copy with fact-checked hospital-specific information only where you have reliable sources and permission.
- Add privacy/consent handling before collecting personal data.

Icons load through Font Awesome CDN; images load from Unsplash and require internet access.


## Updated supplied assets
- `assets/yatharth-logo.png` — logo supplied by the site owner, used in the header and footer.
- `assets/yatharth-hospital-building.jpg` — hospital exterior photo supplied by the site owner, used instead of unrelated stock photography.
- The footer's “Useful information” column has been removed as requested.


## Latest image placement update
- Home page hero: unchanged.
- Home page patient-information section: `assets/patient-doctor-consultation.png` (provided image 1).
- About Us hero: `assets/medical-team.jpg` (provided image 2).
- About Us “Our purpose” image: `assets/patient-care.jpg` (provided image 3).
- Blog hero: `assets/healthcare-services.jpg` (provided image 4).
- Removed the “Article categories coming soon” section; retained the empty state for future posts.
