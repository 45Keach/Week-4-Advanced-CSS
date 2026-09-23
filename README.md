# SpendWise Dashboard Shell

A responsive **SpendWise** finance dashboard shell built for Week 4 using modern CSS Grid, Flexbox, custom properties, responsive media queries, and subtle card micro-interactions.

## Files

- **index.html** — Semantic dashboard structure: sidebar navigation, header, spending summary, six category cards, transactions, and savings goal.
- **style.css** — Complete visual system and layout. CSS Grid handles the page/card/panel structure, while Flexbox handles navigation, header controls, summary content, and card internals.

## Requirements covered

- CSS Grid for the overall two-column dashboard and card layouts.
- Flexbox for header, sidebar/navigation, summary, and dashboard card content.
- Six realistic categories: Food, Transport, Rent, Entertainment, Savings, and Utilities.
- CSS custom properties on `:root` for brand, accent, surfaces/background, primary text, secondary text, borders, and other theme values.
- Responsive breakpoint below **768px** collapses the dashboard to a single-column layout.
- Card hover and keyboard `:focus-visible` micro-interactions use `transform` and `box-shadow` with transitions under 250ms.
- No absolute positioning is used for page layout.
- Dark theme implemented with `@media (prefers-color-scheme: dark)`, overriding the theme variables only.

## Responsive verification

Open the project in a browser and use **DevTools → Device Toolbar** to test widths below 768px (for example, 390px and 430px). The sidebar/navigation becomes a horizontal scrollable navigation row and the main dashboard uses a single-column layout.

## Run locally

No build tools or dependencies are required. Open `index.html` directly in a browser.
