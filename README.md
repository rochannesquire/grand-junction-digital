# Grand Junction — Digital Experience & Strategy

**Project:** Grand Junction website redesign and digital strategy  
**Venue:** St Mary Magdalene Church, Rowington Close, London W2 5TF  
**Website:** [grandjunction.org.uk](https://grandjunction.org.uk)  
**Consultant:** Rochanne Squire  

---

## Repository Structure
grand-junction-digital/
├── prototypes/          ← Interactive HTML prototypes (open in browser)
├── assets/              ← Photography and brand images (added when available)
└── README.md            ← This file

---

## Interactive HTML Prototypes

Latest prototype (v14) and the original five design directions across three pages. Open directly in a browser — no build step required.

### Live URLs

| Prototypes | URL |
|-----------|-----|
| Homepage - current variation | https://rochannesquire.github.io/grand-junction-digital/prototypes/GJ_Homepage_Variations_v3.html |
| Homepage - all 5 variations | https://rochannesquire.github.io/grand-junction-digital/prototypes/GJ_Homepage_Variations_v3.html |
| What's On - all 5 variations | https://rochannesquire.github.io/grand-junction-digital/prototypes/GJ_WhatsOn_Variations.html |
| Heritage Hub - all 5 variations | https://rochannesquire.github.io/grand-junction-digital/prototypes/GJ_HeritageHub_Variations.html |

### Original Variation Reference

| ID | Name | Concept |
|----|------|---------|
| A | Editorial Ink | Dark editorial, DM Serif Display italic, Southbank/Barbican reference |
| B | Living Stone | Warm institutional, Libre Baskerville, BAC/Rich Mix reference |
| C | Modernist Nave | White page, Playfair Display 700, Tate/MoMA reference |
| D | Open Access | High contrast, accessibility-first, Cormorant Garamond, community-led |
| E | Stained Glass Bold | Bold colour palette, Bebas Neue, BAC overlay navigation |

### How to use the prototypes

- Open any URL above directly in a browser (Chrome or Firefox recommended)
- Use the **toolbar at the top** to switch between variations A–E of original
- Variation E: click the **burger icon top left** to open the overlay navigation
- All interactive elements (filters, toggles, overlays, tabs) are live — click to explore
- Source code is fully inspectable — open browser DevTools to review CSS and JS

---

## Proposed Navigation Structure

Primary nav: **What's On · Visit · Hire · Get Involved**  
Persistent CTAs (all pages): **Donate · Join as Member**  
Footer only: About · Privacy · Safeguarding · Accessibility · Terms · Contact

---

## Working on the Prototypes

**To edit a prototype:**
1. Clone the repository locally
2. Edit the HTML file in any code editor (VS Code recommended)
3. Open the file in a browser to preview changes
4. Commit and push — GitHub Pages updates automatically within ~60 seconds

**Branch convention:**
- `main` — current approved version (what the live URLs serve)
- Use feature branches for significant changes: `git checkout -b update-var-e-nav`

**Image placeholders:**  
All 107 image slots use `.ph-dk` (dark) or `.ph-lt` (light) placeholder divs with
`data-label` attributes describing the intended photography. Replace with `<img>` 
tags or CSS `background-image` as real photography arrives.

---

## Key contacts

| Role | Name |
|------|------|
| Consultant | Rochanne Squire |
| Venue | Grand Junction / Paddington Development Trust |
