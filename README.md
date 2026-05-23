# Saxbys Coffee

Saxbys is a Philadelphia-headquartered hospitality company founded in 2005 by Nick Bayer. It operates a small chain of cafes across the U.S. East Coast and Midwest and is best known for its **Experiential Learning Platform (E.L.P.)** — 100% student-run cafes embedded inside college and university campuses.

This repository is the API Evangelist network catalog entry for Saxbys. It documents the company as a **non-API hospitality + education brand**: there is no public REST API, OpenAPI, SDK, developer portal, or partner integration program to index. The artifact recorded here is therefore the `apis.yml` profile, the E.L.P. model, and the public-facing common properties (cafe locator, menus, ordering, blog, careers, social).

## What Saxbys Is

> "Saxbys is a hospitality company with a mission: Make Life Better. Brewing real change in the communities it serves, Saxbys champions education and opportunity to empower the next generation of changemakers." — [saxbyscoffee.com](https://www.saxbyscoffee.com)

- **Founded**: 2005
- **Founder / CEO**: Nick Bayer
- **Headquarters**: Center City, Philadelphia, PA
- **Type**: Privately held
- **Format**: Hybrid of traditional retail cafes and student-run campus cafes
- **Active states / markets**: PA, NJ, NY, MA, MD, VA, OH, GA, IN, WV, TX, Washington D.C.

## The Experiential Learning Platform (E.L.P.)

The E.L.P. is what makes Saxbys structurally different from every other regional coffee chain. Rather than franchising or operating campus locations through a corporate manager, Saxbys hands the entire cafe — P&L, staff, hiring, hospitality, community programming — to a single undergraduate.

> "Saxbys is a national education company and For Students, By Students." — [saxbyscoffee.com/the-saxbys-elp/](https://www.saxbyscoffee.com/the-saxbys-elp/)

> "We build individualized academic partnerships with universities to provide exceptional, paid, experiential learning opportunities." — [saxbyscoffee.com/the-saxbys-elp/](https://www.saxbyscoffee.com/the-saxbys-elp/)

### How it works

1. **Academic partnership** — Saxbys signs an individualized agreement with a university or college. The cafe lives in a central campus building (student union, library, business school).
2. **Student Cafe Executive Officer (SCEO)** — One undergraduate is selected to run the cafe full-time for a semester. They take "full responsibility for running their own dynamic, bustling cafe in the center of campus."
3. **All-student team** — Every team member is a student at the partner institution. Cafes are 100% student-run.
4. **Paid + credit** — Students are paid for their work and the experience is structured as an academic, for-credit experiential learning opportunity.
5. **Faculty integration** — Faculty can "demonstrate classroom concepts and partner with students developing research projects" inside a live operating business.
6. **Experiential Learning Badges** — Saxbys layers corporate microcredentials on top of the in-cafe experience, covering field-specific skills such as Supply Chain Management, Talent Acquisition, and Training & Development.

### Named E.L.P. partners

From the E.L.P. landing page and the Saxbys Stories blog:

- Penn State University
- Bowie State University
- Temple University
- Drexel University
- Georgia State University
- Rider University
- Wellesley College
- Fordham University
- University of Mount Saint Vincent
- Virginia Commonwealth University
- University of Texas at Arlington
- Siena University
- University at Albany
- Fairmont State University
- SUNY Plattsburgh
- Northeastern University

## Digital Surface

Saxbys' digital footprint is intentionally narrow and consumer-facing.

| Surface | URL | Notes |
| --- | --- | --- |
| Marketing site | https://www.saxbyscoffee.com | Powered by BentoBox |
| E.L.P. program page | https://www.saxbyscoffee.com/the-saxbys-elp/ | "Bring to Your Campus" inbound channel |
| Cafe locator | https://www.saxbyscoffee.com/locations/ | ~27+ open cafes; mix of retail and E.L.P. |
| Menus | https://www.saxbyscoffee.com/menus/ | Per-cafe menus; no single SKU list |
| Order Ahead | https://www.saxbyscoffee.com/locations/ | Per-cafe ordering via BentoBox |
| Catering | https://www.saxbyscoffee.com/catering/ | Office and event catering |
| Online Shop | https://www.saxbyscoffee.com/shop/ | Branded merch and packaged coffee |
| Blog | https://www.saxbyscoffee.com/saxbys-stories/ | Mostly E.L.P. launch announcements; no RSS detected |
| Impact | https://www.saxbyscoffee.com/impact/ | Education + opportunity mission |
| Careers | https://www.saxbyscoffee.com/careers/ | O.D.D. values, Recruiting@HelloSaxbys.com |
| Press | https://www.saxbyscoffee.com/press/ | marketing@saxbyscoffee.com |
| GitHub | https://github.com/Saxbys | One internal repo: `Saxbys-Inventory-Analyzer-v2` |
| X / Twitter | https://twitter.com/saxbyscoffee | |
| LinkedIn | https://www.linkedin.com/company/saxbys-coffee | |
| Instagram | https://www.instagram.com/saxbyscoffee/ | |
| TikTok | https://www.tiktok.com/@saxbyscoffee | |

## Notable Absences (API Evangelist Lens)

- **No public REST or GraphQL API** — no developer portal, no `developer.`, `api.`, or `docs.` subdomain.
- **No OpenAPI, AsyncAPI, or JSON Schema** anywhere on the public site or in GitHub.
- **No SDKs, no CLI, no integration marketplace.**
- **No public pricing API or location feed** — the cafe locator is HTML-only, not JSON.
- **No RSS / Atom feed** on Saxbys Stories.
- **No status page** — operational status communicated per-cafe through Order Ahead availability.
- **Mobile ordering and rewards** historically ran through a Saxbys app, but no public API contract is published for it.

The single piece of public engineering output from Saxbys — `Saxbys-Inventory-Analyzer-v2` on GitHub — is an HTML/JS internal tool published via GitHub Pages, not a developer-facing artifact.

## Why Saxbys Matters Even Without APIs

Saxbys is included in the API Evangelist network because the **E.L.P. model itself** is the interesting "interface" — a turn-key academic partnership contract that converts a campus cafe into a live, paid, for-credit business classroom. If Saxbys ever exposes that model as a programmable surface (partner onboarding, SCEO application pipeline, cafe operations telemetry, real-time location and menu feeds), it would become one of the few hospitality brands whose API surface is shaped by an education product, not a retail product.

## Repository Contents

- [`apis.yml`](./apis.yml) — APIs.yml 0.20 profile for Saxbys with all common properties, the E.L.P. program, named partner universities, and digital surfaces.
- `README.md` — this file.

## Maintainer

- Kin Lane / API Evangelist — https://apievangelist.com
