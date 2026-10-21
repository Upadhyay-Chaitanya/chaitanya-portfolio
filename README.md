# Chaitanya Kumar Upadhyay Professional Portfolio

A static professional portfolio for a Senior Program Manager with a cloud engineering background. It contains a career overview, three anonymised case studies, qualifications and a public resume.

## Files

- `index.html`: professional overview, selected work, career progression and credentials.
- `cloud-governance.html`, `security-delivery.html`, `platform-ai.html`: case studies.
- `styles.css`: shared desktop, mobile, print and accessibility styles.
- `assets/Chaitanya_Upadhyay_Public_Resume.pdf`: public resume with direct contact details, employer names, internal spending and security counts omitted.
- `disclaimer.html`: personal portfolio disclosure.
- `case-study.css`: compatibility file retained for earlier page references; current case styles are in `styles.css`.

## Local preview

From this directory, run `python3 -m http.server 8765 --bind 127.0.0.1` and open `http://127.0.0.1:8765/`.

## Publishing

This site uses GitHub Pages from the repository root. Keep relative links so the site works beneath the `/chaitanya-portfolio/` project path. Publishing the production branch updates the live site.

Before publishing, review statements for accuracy. Continue omitting employer and client names, private links, environment identifiers, internal spending and security counts. Link only the public resume from this repository; the application resume is a separate private artifact.

## Content maintenance

Keep the role title, dates, education and qualifications consistent with the candidate's confirmed information. Describe personal contribution separately from team implementation and approval authority. Do not add unsupported metrics or imply ownership of work performed by other teams.

## Validation

The October 2026 revision was checked for local link and anchor resolution, a single top-level heading on each page, public-resume exclusions, and horizontal overflow on all five HTML pages at a 390px viewport. The homepage and security case study were visually reviewed on desktop and mobile. The public resume was rendered and visually reviewed as a one-page PDF.
