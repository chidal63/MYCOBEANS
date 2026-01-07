# MYCOBEANS website — STATUS FREEZE

Last update: 2026-01-07

## Scope and purpose
Public website and repository ecosystem for the MYCOBEANS project (Marie Skłodowska-Curie Actions — Staff Exchange).

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
  → above-the-fold layout refined for readability and hierarchy
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
  → card height and vertical alignment stabilised
- Events  
  → working listing page  
  → refined two-column layout with responsive behaviour  
  → standardised post template for meetings, workshops and project activities
- Secondments  
  → structured overview of mobility patterns (interdisciplinary, intersectoral, applied research)  
  → “At a glance” summary block  
  → representative, non-exhaustive examples expressed as typological patterns  
  → no individual-level storytelling
- Resources  
  → structured index of public outputs  
  → clear L1/L2/L3 typographic hierarchy  
  → featured resource (video) linked via DOI  
  → publications and invited communications listed  
  → Zenodo community linked as canonical repository  
  → governance criteria stated once and concisely
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
  → identifier: `mycobeans`  
  → review required enabled  
  → About page and Curation policy completed  
  → EU funding disclaimer included
- **Zenodo records published (DOIs assigned):**
  - Video: secondments experiences and knowledge transfer
  - Poster: PSU → UNIPR secondment output
  - Workshop (programme only): nanopore sequencing training (v1)
  - Additional dissemination and data records managed via Zenodo

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

## Future updates (content-only)
From this freeze onward, updates are limited to:
- new **Events** posts (meetings, workshops, milestones)
- additions to **Resources** (new Zenodo DOIs, accepted publications)

No further structural, layout or CSS changes are planned.

---

## Current status
The MYCOBEANS website and Zenodo community are **live, stable and governance-compliant**.

Core web content, visual hierarchy, privacy, compliance, email infrastructure and repository setup are complete.  
The site is now in **maintenance mode**, with future changes restricted to content updates only.
