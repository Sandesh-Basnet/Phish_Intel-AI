# Phish-Intel AI – HTML Structure

## Overview
The frontend contains two main HTML files:

- `index.html` → URL scanning page  
- `dashboard.html` → Scan results dashboard  

Both files are located inside the `frontend/` directory.

---

## index.html

### Purpose
Provides a form where users submit a URL for phishing analysis.

### Key Elements
- Links to `css/style.css`
- Uses `.topbar`, `.page-wrap`, and `.panel`
- Form submits to `dashboard.html`
- Styled using shared CSS components

---

## dashboard.html

### Purpose
Displays phishing scan results and metadata.

### Key Elements
- Links to `css/style.css` and `css/dashboard.css`
- Uses `.dashboard-grid` layout
- Contains:
  - Risk Summary panel
  - Detailed explanation section
  - URL metadata table
  - Scan history table
  - Action buttons

---

## Notes
- CSS paths must be relative:
  - `href="css/style.css"`