# The Brew Haven — Milestone 1

A responsive 5-page local business website for a realistic Jaipur café, built to match the Milestone 1 Web Foundation brief.

## Pages
- `index.html` — Home, hero, highlights, Why Choose Us, menu highlights, gallery preview, testimonials and CTA.
- `about.html` — brand story, values, team and CTA.
- `menu.html` — CSS Grid menu/service cards with pricing.
- `gallery.html` — responsive image grid.
- `contact.html` — accessible contact form, business details and embedded map.

## Tech used
- Semantic HTML5
- Tailwind CSS via CDN
- No JavaScript framework, React, Bootstrap or other programming language
- Google Fonts: Inter + Playfair Display
- Responsive, mobile-first layout
- `dark:` Tailwind utilities with `prefers-color-scheme` support
- CSS Grid and Flexbox are both used meaningfully
- No inline styles

## Accessibility
- One `h1` per page
- Semantic `header`, `nav`, `main`, `section`, `article`, `aside`, `footer`
- Skip-to-content link
- Labels connected to every form control
- Correct input types and sensible required fields
- Descriptive image alt text
- Visible keyboard focus states

## Responsive targets
Designed mobile-first and tested conceptually around:
- ~375px mobile
- ~768px tablet
- ~1280px desktop

## Vercel deployment
1. Create a public GitHub repository.
2. Upload these files.
3. Import the repo into Vercel.
4. Deploy with the default static-site settings.
5. Open the generated URL on both Wi-Fi and mobile data.

## Git hygiene checklist
The brief requires 10+ meaningful commits, 2+ branches and at least 1 merged PR. Create these yourself so the history reflects your actual work:

1. `chore: initialize project structure`
2. `feat: build semantic home page`
3. `feat: add responsive navigation`
4. `feat: build menu grid`
5. `feat: build responsive gallery`
6. `feat: add accessible contact form`
7. `feat: add map and business details`
8. `style: add dark mode and focus states`
9. `style: improve mobile and tablet layouts`
10. `docs: add project README`

Suggested branches:
- `main`
- `feature/contact-page`

Open a PR from `feature/contact-page` into `main` and merge it.

## Presentation talking points
- Grid is used for menu/gallery because repeated cards need consistent columns and responsive reflow.
- Flexbox is used for the “Why Choose Us” row and header/CTA alignment because the items need one-dimensional alignment.
- Semantic elements make the structure meaningful and easier to navigate.
- The form uses labels, proper input types and required fields for accessibility.
- Dark mode follows the user's system preference without JavaScript.

## Important
The brief says AI is allowed for learning/debugging, but you must be able to explain every line during Q&A. Read the HTML before submitting and customize the copy, business details and visual choices so the project represents your own work.
