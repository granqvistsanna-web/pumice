# Pumice

A soft, warm-grey design system for component libraries and product
showcases. Pill controls, 28px cards, ink washes instead of borders,
and motion that springs a little. Light and dark.

**Live reference (tokens, type scale, button motion, phone patterns, panels, live components):**
https://granqvistsanna-web.github.io/pumice/

## Use it in a project

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@300..700&display=swap">
<link rel="stylesheet" href="https://granqvistsanna-web.github.io/pumice/tokens.css">
```

Then build on the variables: `var(--ink)`, `var(--wash)`, `var(--r-pill)`,
`var(--spring)`, `var(--press)`, … Dark mode follows the system, or set
`data-theme="dark"` / `"light"` on `<html>`.

## Core rules

- Two shapes: pills (999px) for controls, 28px for cards, 12px for small inner panels
- Fills are ink at 6% alpha; borders are rare and drawn as a 1px inset ring
- The near-black ink pill is the only accent; signal colors are for content
- Inter at 400 and 500 only; hierarchy from size and ink
- Press shrinks by size: .96 buttons, .95 chips and hero CTA, .92 icons, .985 links
- Moves use a spring with slight overshoot; open/close uses the settle curve
- Phone: three-part bar that compacts on scroll, full-screen menu, 44px touch targets
