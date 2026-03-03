# Phish-Intel AI – CSS Structure

## Overview
The frontend styling is divided into two CSS files:

- `style.css` → Base/shared styles
- `dashboard.css` → Dashboard-specific styles

Both are located in `frontend/css/`.

---

## style.css (Base Styles)

### Contains:
- CSS variables (`:root`)
- Global reset
- Dark cybersecurity theme
- Top navigation bar
- Panel component
- Buttons (`.btn`, `.btn-primary`, `.btn-secondary`)
- Badges (`.badge-safe`, `.badge-danger`, etc.)
- Footer styling
- Utility animations (glitch, blink)

Used by both HTML pages.

---

## dashboard.css (Dashboard Styles)

### Extends base styles with:
- `.dashboard-grid` layout
- Risk gauge styling
- Metadata table styles
- Flag list styles
- History table styles
- Statistics cards
- Loading spinner

Requires `style.css` to be loaded first.

---

## Notes
- Always link `style.css` before `dashboard.css`
- CSS uses custom properties (variables) defined in `:root`