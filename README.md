# Andrew Totsis — Personal Resume Website

A professional, responsive personal resume website built with vanilla HTML, CSS, and JavaScript. Zero dependencies, zero build step — deploy anywhere in seconds.

## Stack

- **HTML5** — semantic, SEO-ready markup
- **CSS3** — custom properties, Grid, Flexbox, smooth animations
- **Vanilla JS** — IntersectionObserver fade-ins, mobile nav, smooth scroll
- **Fonts** — Inter + Playfair Display via Google Fonts
- **Hosting** — Vercel (static)

## Structure

```
/
├── index.html      # Main page
├── styles.css      # All styles (CSS variables + responsive)
├── script.js       # Interactions (nav, scroll, animations)
├── vercel.json     # Vercel config + security headers
└── README.md
```

## Deploy to Vercel

### Option 1 — Vercel CLI
```bash
npm i -g vercel
vercel
```

### Option 2 — Vercel Dashboard
1. Push this repo to GitHub
2. Go to vercel.com → New Project
3. Import your repo — Vercel auto-detects static HTML
4. Click Deploy — done in ~10 seconds

## Edit Content

All content lives in `index.html`. Find sections by their `id`:

| Section    | ID            |
|------------|---------------|
| Hero       | #hero         |
| Experience | #experience   |
| Education  | #education    |
| Skills     | #skills       |
| About      | #about        |
| Contact    | #contact      |

## Edit Colors

Open `styles.css` and update the CSS variables at the top:

```css
:root {
  --accent:  #7A6B55;  /* warm brown highlight */
  --bg:      #FAFAF7;  /* page background      */
  --bg-alt:  #F3EFE9;  /* alternate sections   */
}
```

## Add a New Job

Copy an `.exp-card` block in `index.html`, update company, dates, role, and bullets.
Add `data-current="true"` to the card for the green left-border on the current role.

---

Built for Andrew Totsis · Aurora, Ontario · 2025
