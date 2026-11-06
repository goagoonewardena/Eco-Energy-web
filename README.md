"# Eco Energy

Eco Energy is a static educational website about sustainable power and the transition
to cleaner energy. It explains renewable, non-renewable, nuclear, and emerging energy
sources, and provides interactive pages for comparing energy technologies, learning
about the project team, giving feedback, and getting involved in sustainability
activities.

## What the site includes

- **Splash and home pages** with the Eco Energy mission, renewable-energy highlights,
  sponsor logos, featured articles, and animated statistics.
- **Energy articles** covering:
  - Renewable energy, including solar, wind, hydropower, wave, and biogas.
  - Non-renewable energy, including coal, natural gas, and petroleum.
  - Nuclear energy and why it is considered a low-carbon source despite not being renewable.
  - Emerging and alternative technologies, including geothermal, hydrogen, biofuels,
    tidal, wave, and fusion energy.
- **Energy comparison table** showing efficiency, cost, emissions, reliability, and
  infrastructure lifespan.
- **Volunteer page** promoting participation in renewable-energy events and outreach.
- **Feedback form** with client-side validation for email, phone number, comments, and
  satisfaction ratings.
- **Team, profile, sitemap, and page-editor pages** documenting the contributors and
  the site structure.
- **Responsive navigation** with mobile menus and article links shared across the site.

## Project structure

The website is contained in [`CW_Final_Merge`](./CW_Final_Merge):

| Path | Purpose |
| --- | --- |
| `home.html` | Main landing page |
| `splash.html` | Introductory splash screen |
| `content_ST1.html` – `content_ST4.html` | Energy articles |
| `table.html` | Energy-source comparison table |
| `volunteer.html` | Volunteer and event page |
| `feedback.html` | Feedback form |
| `team.html` | Project team |
| `profile.html` | Example user profile/dashboard |
| `sitemap.html` | Visual site map |
| `pageEditor_ST1.html` – `pageEditor_ST4.html` | Contributor page documentation |
| `validation_ST1.html` – `validation_ST4.html` | HTML validation evidence |
| `assets/` | Images, icons, and background videos |
| `*.css` | Shared and page-specific styling |
| `*.js` | Navigation, counters, team interactions, and form validation |

## Running locally

No build tools or package installation are required. Open
[`CW_Final_Merge/splash.html`](./CW_Final_Merge/splash.html) directly in a modern
browser, or serve the folder with a local HTTP server for the most reliable handling
of videos, assets, and browser security rules.

For example, from the repository root:

```text
cd CW_Final_Merge
python -m http.server 8000
```

Then visit <http://localhost:8000/splash.html>. If Python is unavailable, any static
file server can be used; there is no server-side application or database.

## Technology

- Semantic HTML5
- CSS3 with responsive layouts
- Vanilla JavaScript
- Local image and video assets
- Google Fonts and Material Icons loaded by selected pages

## Notes

- The feedback form validates input in the browser and displays a confirmation
  message; it does not send data to a backend.
- The profile and dashboard content is illustrative static content.
- Some external fonts, icons, and sustainability links require an internet connection.

## Contributors

The project was developed by four contributors, whose roles and page ownership are
listed on [`CW_Final_Merge/team.html`](./CW_Final_Merge/team.html).
