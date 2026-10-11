# ZGDS — CASPAM Chapter single-file website

This website is self-contained: HTML, CSS, JavaScript, and the three provided logos are embedded in `index.html`. No database, Node.js, separate stylesheet, or JavaScript files are required.

## Preview locally
Open `index.html` directly in a modern browser. For GitHub/Vercel, keep `index.html` at the repository root.

## Included
- Bahauddin Zakariya University logo in a circular frame at the top-left
- CASPAM logo in a circular frame at the top-right
- ZGDS logo beside the society name in the header
- Director's Message section with clearly marked editable sample text
- Dark/light mode toggle; remembers the preference in the current browser
- Subtle scroll reveal, floating logo and background animations, and reading progress bar
- Responsive layout and prefers-reduced-motion support

## Edit the Director's Message
Search `EDITABLE DIRECTOR MESSAGE` in `index.html`, then replace the sample paragraphs, `[Director's Full Name]`, and `Director, CASPAM` with the approved content.

## Edit society data
The `SITE`, `events`, `projects`, and `team` arrays are near the bottom inside the inline JavaScript. Replace placeholders before publishing. The contact form uses a `mailto:` link and does not store messages.

## Deploy on Vercel
Import the GitHub repository into Vercel, use Framework Preset `Other`, leave the build command blank, and set the output directory to `.`.
