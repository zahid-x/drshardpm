# Dr. Shar's Foot & Ankle — project rules

Website for Dr. Shar's Foot & Ankle, a concierge membership podiatry practice in
New York run by Dr. Sharaara Rahman, DPM. Static site: one `index.html` with
inline CSS and JS, plus an `img/` folder. Published with GitHub Pages at
https://zahid-x.github.io/drshardpm/ from the `main` branch.

## Design system

- **Palette:** linen `#F7F3EE`, paper `#FBF9F5`, sand `#ECE3D4`, navy `#12223F`,
  gold `#B8935A` / deep gold `#84622E` / light gold `#C9A46B`, slate `#5E6270`,
  lines `#E2D8C6`. Nothing outside this palette.
- **Fonts:** Cormorant Garamond (headings), Jost (body), Cinzel (small caps
  wordmarks like FOOT & ANKLE).
- **Spacing:** use this scale only: 8, 16, 24, 40, 64, 96px. Sections are 96px
  apart on desktop, 40px on phones.
- **Type:** five sizes only (display, heading, subhead, body, small). Nothing
  under 13px. Every tap target at least 44px.
- **Breakpoints:** tablet at 1024px or less, phone at 700px or less. All phone
  rules live in ONE media query block. Don't add overrides on top of
  overrides; edit the existing rule.
- **Photos:** each photo has its own crop and focal point per device. Never
  crop through a face. On phones, Conditions and How to join show no photo.

## Content rules

- Section names, used identically in nav, menu, labels and footer:
  **Membership, Conditions, About Dr. Shar, How to join, FAQ, Contact.**
- The "Request an introduction" button appears only in the header, the hero
  and the phone bottom bar. Elsewhere use a text link to `#contact`.
- Never invent copy in Dr. Shar's voice, testimonials, credentials or claims.
  Use only approved text or a clearly marked placeholder like
  `[One line in Dr. Shar's words]`.
- Every AI-generated image keeps its "AI-generated image · replace before
  launch" label until replaced with real photography.
- Required disclaimers stay word for word: membership is not health
  insurance; services by Sharaara Rahman Podiatry P.C.; in an emergency
  call 911.

## Before every push

- Check no horizontal scroll at 320, 375, 393, 430, 768 and 1440px wide.
- Check the phone bottom bar sits directly under the footer with no gap.
- Preview the page on desktop and phone widths and look at it.

## Working with the owner

When asked for changes, show what changed and preview it before pushing.

## Still pending (placeholders on the live site)

- Hero line in Dr. Shar's words; first-person About paragraph
- Office address and hours
- Official one-color logo files from each institution
- Real photography to replace AI-generated images
- Contact form sends nothing yet; needs a form service before launch
- Shoe brand logos in the running photo need retouching before launch
- FAQ answers need Dr. Shar's sign-off
