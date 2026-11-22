byMekkamaru — Portfolio V3
==========================

A responsive, static HTML/CSS/JavaScript portfolio for Achyuta.

PROJECT STRUCTURE
- index.html                 Main portfolio homepage
- projects/worknexus.html    WorkNexus case study
- projects/agrisathi.html    AgriSathi case study
- projects/finsaathi.html    FinSaathi case study
- assets/profile-photo.webp  Portfolio portrait
- assets/favicon.svg         Browser icon
- assets/og-preview.svg      Social-sharing preview artwork
- 404.html                   Custom not-found page
- robots.txt                 Basic crawler access rules

DESIGN & INTERACTIONS
- Dark premium visual system with blue primary (#3478F6) and red support (#EF4444)
- Responsive navigation with mobile menu on homepage and case-study pages
- Scroll reveal, reading progress indicator, active section navigation,
  pointer spotlight on project cards, hover lift, and back-to-top control
- Reduced-motion preferences are respected
- Individual project pages include Figma embeds and direct Figma links
- No React build step or paid UI library is required

PROJECT STATUS ACCURACY
- WorkNexus is presented as a concept / interface project in progress.
- AgriSathi is presented as a concept / interface project; no unverified outcomes are claimed.
- FinSaathi explicitly separates completed onboarding, login and dashboard screens
  from the transactions and remaining sections still in progress. Demo-only
  transaction interactions are not described as live payment functionality.

LOCAL PREVIEW
1. Extract the ZIP.
2. Open index.html in a modern browser, or run a local static server:
   python -m http.server 8000
3. Visit http://localhost:8000

PUBLISHING (FREE STATIC HOSTING)
- GitHub Pages: create a public or private repository, upload the contents of
  this folder, then enable Pages from the repository's Settings.
- Netlify / Cloudflare Pages: create a new static site and deploy this folder.
  The publish directory is the folder containing index.html; no build command
  is required.
- Do not publish until the Figma source file's sharing permissions allow the
  intended visitors to view the embedded screens.
- After a public domain is assigned, update og:image to an absolute URL and add
  a canonical URL / sitemap if desired.

QA NOTES
- Static HTML parsing, internal link/anchor/image-path checks, duplicate-ID
  checks and inline JavaScript syntax checks were run on this package.
- The embedded Figma frames require network access and suitable Figma sharing
  permissions. Verify the embeds in a normal browser after publishing.
- Email and LinkedIn links are syntactically present; final click-through checks
  should be done in a browser with the user's email client / LinkedIn session.
- Live deployment is not included in this ZIP. A connected GitHub account or
  hosting account is required to publish and verify a public URL.


V5 visual update (22 Nov 2026): refreshed the homepage into an asymmetric Bento Grid with glassmorphism surfaces, applied matching glass panels to all three project case studies, and replaced the profile portrait asset with the latest supplied professional portrait. The site remains a static HTML/CSS/JS portfolio.
