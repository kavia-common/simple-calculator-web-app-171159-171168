# Ocean Calculator (Astro)

A simple, modern calculator web app built with Astro. It supports addition, subtraction, multiplication, and division. The UI follows the Ocean Professional theme with blue (#2563EB) and amber (#F59E0B) accents, minimalist surfaces, rounded corners, subtle shadows, and smooth transitions.

## Quickstart

From this folder:

- Install: `npm install`
- Run dev: `npm run dev` (served at localhost:3000 or as configured)
- Build: `npm run build`
- Preview: `npm run preview`

## Features

- Core operations: +, −, ×, ÷
- Responsive layout with a central calculator panel
- Keyboard support: digits, operators (+ − * /), Enter/Equals, Escape to clear, % for percent, and `.` for decimal
- Graceful divide-by-zero handling

## Structure

- `src/pages/index.astro` — App entry; renders the calculator within the site layout
- `src/components/Calculator.astro` — Calculator UI, styles, and logic
- `src/layouts/Layout.astro` — Base HTML, theme variables, and optional dark mode toggle

## Theming

- Background: #f9fafb
- Surface: #ffffff
- Text: #111827
- Primary: #2563EB
- Secondary: #F59E0B

All styles are embedded and require no external CSS frameworks.
