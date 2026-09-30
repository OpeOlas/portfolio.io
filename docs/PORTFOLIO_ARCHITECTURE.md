# Portfolio architecture

Static HTML and CSS for GitHub Pages. No build step, external font service or JavaScript content dependency.

## Homepage

Introduction and approach → credentials strip → six case studies → governance capabilities and illustrative rule → about → technical lab → credentials → contact.

## Case study pages

Six readable, independently linked HTML pages. Each has context, contribution, output and evidence, and a governance lesson. Navigation returns to homepage sections. All assets use relative paths compatible with the /portfolio.io/ deployment prefix.

## Design

Warm ivory, forest green and muted gold. Editorial typography, generous spacing, restrained geometric CSS illustrations. These illustrations describe themes and are not dashboards or project evidence. Responsive grids, visible keyboard focus, skip link, native navigation, and progressive enhancement for the mobile menu.

## Evidence policy

Distinguish professional experience, advisory work, academic research and capstone work. Do not attach research claims to production outcomes. Professional metrics are reported experience outcomes, not independently audited results. Confidential operational datasets and documents are omitted. Governance example is explicitly recreated and illustrative.

## Content gaps

CV button currently requests the current CV by email. Replace it with a download only when the approved current CV is supplied. Add approved sanitised screenshots, reports and glossary extracts when available. No stock imagery is presented as original work. Technical lab summaries are deliberately limited; detailed model metrics need inspection and validation of the underlying notebooks.

## Maintenance

Edit the HTML directly. Shared styles live in assets/css/portfolio.css and menu behaviour in assets/js/portfolio.js. Add new page URLs to sitemap.xml. Existing theme files remain in the repository for recovery, but the new pages do not load them.
