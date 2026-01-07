# MYCOBEANS website — STATUS FREEZE

Last update: 2026-01-07

## Scope and purpose
Public website and repository ecosystem for the MYCOBEANS project (Marie Skłodowska-Curie Staff Exchange).

The website and associated repositories serve as **project showcase and transparency tools**, not as stakeholder engagement or communication platforms.
No marketing funnel, no newsletter, no user profiling.

Primary functions:
- public visibility of the project
- clarity of objectives, structure and consortium roles
- audit- and review-proof dissemination

---

## Technical stack
- GitHub Pages
- Jekyll (Minimal Mistakes theme)
- Static site (no backend)

Domain & deployment:
- Custom domain: **www.mycobeans.eu**
- HTTPS enabled
- Site served from root domain (no subdirectory)

Analytics:
- GoatCounter (privacy-friendly, cookieless)
- No Google Analytics
- No tracking cookies set by the website

Email:
- Project mailbox active: **info@mycobeans.eu**
- Hosted on Zoho Mail
- SPF, DKIM and DMARC configured
- No forwarding-dependent setup

---

## Pages — COMPLETED
- Home  
  → institutional landing page with clear MSCA Staff Exchange framing  
  → “above the fold” layout tightened for readability
- The Project  
  → concise, mobility-centred narrative aligned with Staff Exchange objectives
- Objectives  
  → objectives framed as functions of staff mobility, not RIA-style deliverables
- Consortium  
  → cards with logos, short descriptions and PI / Industry contact  
  → differentiated grids (EU/UK vs Thailand)  
  → UNIPR and NSTDA-BIOTEC displayed as full-width single cards  
  → coordinating institution visually emphasised  
  → PI/contact information visually subordinate to institutions  
  → grid/card vertical alignment stabilised via flex layout
- Events  
  → working listing page  
  → refined two-column rows layout + responsive behaviour  
  → standardised post template for meetings, workshops and project activities
- Resources  
  → structured page for public outputs  
  → publications + oral communications reformatted as clean lists  
  → featured resource (video) linked via DOI and contextualised in Zenodo governance  
  → Zenodo community linked as canonical repository  
  → “About this page” governance note present but visually subordinate  
  → consistent `info-box` styling applied
- Secondments  
  → structured overview of mobility patterns (interdisciplinary, intersectoral, applied research)  
  → “At a glance” summary block  
  → representative, non-exhaustive examples  
  → no individual-level storytelling
- Contact  
  → standalone page  
  → project email published (**info@mycobeans.eu**)  
  → no forms, no personal emails exposed
- Privacy & Imprint  
  → minimal, GDPR-safe  
  → updated for GoatCounter, external resources and email contact

---

## Repository & dissemination infrastructure — COMPLETED
- **Zenodo community created:** MYCOBEANS  
  → review required enabled  
  → governance pages (About, Curation policy) completed  
  → EU funding disclaimer included
- **Zenodo records published (DOIs assigned):**
  - Video: secondments experiences and knowledge transfer
  - Poster: PSU → UNIPR secondment output
  - Workshop (programme only): nanopore sequencing training (v1)

Zenodo is established as the **canonical repository** for public project resources.  
The website links to Zenodo records and community but does not host files directly.

---

## Editorial, design and governance principles
- Short, dense texts (no proposal-style verbosity)
- No exaggerated claims or promised impacts
- Clear separation between:
  - academic partners
  - non-academic public research organisations
  - industrial partners
- Intersectoral dimension described as practice, not slogan
- Outputs framed as *relevant to the scientific scope* rather than claimed as direct project deliverables
- Logos visually standardised via layout and controlled scaling, not file manipulation
- Industry uses “Industry contact”, not PI
- No publication of confidential or IP-sensitive material

---

## Accessibility baseline — IMPLEMENTED
- Visible keyboard focus states
- Body links clearly identifiable (underline + hover thickness)
- Reduced-motion preference respected (`prefers-reduced-motion`)

---

## Explicit decisions (do not revisit unless necessary)
- No newsletter
- No stakeholder engagement mechanisms
- No Google Analytics or equivalent profiling tools
- No premature open science claims
- No individual-level storytelling on the website
- Zenodo is the sole hosting platform for public files
- Quality takes precedence over speed for dissemination artefacts

---

## Deferred / next steps
- Publish additional Zenodo records (workshops, posters, slides) once **public/non-confidential** versions are available
- Lightweight updates to **Resources** as new Zenodo records go live
- Optional: one-page PDF project overview (only when content stabilises)
- Optional: further accessibility fine-tuning (contrast checks, aria labels if needed)

---

## Current status
The MYCOBEANS website and Zenodo community are **live, stable and governance-compliant**.

Core web content, privacy, compliance, email infrastructure and repository setup are complete.  
Dissemination outputs will expand via Zenodo as quality-assured public materials become available.
