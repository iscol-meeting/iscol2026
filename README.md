ISCOL 2026 — Static Site

This is a simple static website for ISCOL 2026 (Israel Seminar on Computational Linguistics), modeled after the ISCOL 2025 site. The event is planned to take place at Hebrew University of Jerusalem, organized by the NLP group at the Hebrew University.

- Live reference (previous year): https://iscol-meeting.github.io/iscol2025/

Files
- `index.html` — Main page with sections: Home, Call for Papers, Organizing Committee, FAQ, Sponsors
- `program.html` — Program page (TBD placeholder)
- `posters.html` — Posters page (TBD placeholder)
- `styles.css` — Minimal responsive styling and navigation

Local Development
No build step is required. Open the `index.html` file in any modern browser.

```bash
open index.html
```

For a quick local server (optional):

```bash
python3 -m http.server 8080
# then visit http://localhost:8080
```

Deployment
Any static hosting solution works (e.g., GitHub Pages, Netlify, Vercel, S3/CloudFront). Upload the HTML and CSS files.

Content Status
This is an initial 2026 placeholder site. Replace the following as details become available:
- Exact date of the event
- Venue and location details within Hebrew University of Jerusalem
- Organizing committee members (currently Person 1–8)
- Submission deadline and notification dates
- Submission site link (OpenReview)
- Program schedule and invited talks
- Poster session assignments and guidelines
- Sponsors and logos
- Registration form link

License
MIT
