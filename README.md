# ₹15 — The Mumbai Vada Pav Story

A love letter to Mumbai's soul food. Born on a railway platform in 1966. Served on newspaper. Eaten standing up. The ₹15 revolution that feeds twenty million people every day.

## Live Demo

🔗 **[https://mumbai-vada-pav.vercel.app](https://mumbai-vada-pav.vercel.app)**

## What This Is

A submission for [Frontend Challenge - Comfort Food Edition, Perfect Landing](https://dev.to/challenges/frontend-2026-07-29).

A scroll-driven landing page that tells the story of vada pav through:
- The 1966 origin story (textile mill workers, Dadar station)
- Mumbai's railway map (every station has a stall)
- An interactive assembler (build your own, step by step)
- A working recipe with servings scaler
- The unwritten rules of eating vada pav

## Tech Stack

- Single `index.html` + `styles.css` (no framework, no build step)
- Vanilla JavaScript for interactions
- ARIA roles + keyboard navigation
- `prefers-reduced-motion` respected
- Responsive (320px to 2560px)
- Google Fonts (Playfair Display + Inter)

## Accessibility

- Semantic HTML5 sections with `aria-label`
- ARIA tablist pattern for the assembler
- Keyboard navigation (arrow keys between steps)
- `aria-live="polite"` for dynamic content
- `lang="mr"` for Marathi text
- Reduced-motion fallback
- All images have descriptive `alt` text
- Color contrast verified (WCAG AA)

## Run Locally

```bash
# No build step needed — just open the file
open index.html

# Or use a local server
npx serve .
```

## License

MIT
