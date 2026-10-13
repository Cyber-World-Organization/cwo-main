# Cyber World Organisation — multi-page static website

Responsive hacker-style CWO website built with plain HTML, CSS and JavaScript. No build step or dependencies required.

## Files
- `index.html` — home
- `about.html`, `faq.html`, `divisions.html`
- `report-cyber-crime.html`, `events.html`, `partners.html`
- `volunteer.html`, `contact.html`, `projects-services.html`
- Six dedicated division pages, each with course outlines and service areas
- `assets/` — supplied CWO and division logos
- `styles.css`, `script.js`, `404.html`

## Preview locally
Run `python -m http.server 8000` from this directory, then open http://localhost:8000.

## Cloudflare Pages deployment
For files placed at the root of your connected Git repository:
- Framework preset: `None`
- Build command: leave blank
- Build output directory: `/` (root)
- Ensure `index.html` and `styles.css` are directly in the selected output directory, not nested under an extra folder.

## Before publishing
- Confirm the preferred social media URLs and public contact details.
- Add approved official partner logo artwork from official brand resource pages, following their logo usage guidelines.
- A listing on the partner page does not assert a formal partnership or endorsement.
- The DMCA label is decorative only and does not represent an active DMCA registration/service.
- Course topics are proposed catalog outlines; confirm schedule, instructors, fees, prerequisites and availability before advertising enrolment.
- The contact form opens an email client; it does not send data to a server or store submissions.
- Google Fonts are loaded remotely.
