---
name: Portfolio Revamp
description: Prabgun Mokha's personal portfolio — AI/Backend Engineer focus
type: project
---

# Portfolio Revamp — CLAUDE.md

## User Goals
- Senior UI designer perspective — wants the portfolio to be **highly interactive and visually striking**
- Keep colors **bright and colourful**
- **Remove LangGraph Issue Solver** from projects (currently not present — may have been already removed or was planned)
- **Add a new relevant project** — must be communicated to user before adding
- All changes must be **reported** to the user

## Current Portfolio State (as of 2026-04-12)

### Already Implemented
- **Dark/Light mode toggle** with localStorage persistence
- **Animated canvas background** — floating star particles + radial gradient orbs that update per theme
- **Cursor trail effect** — glowing particle trail following mouse movement
- **Terminal-style hero** — animated bash-style typing sequence cycling through aspirations
- **Typed role effect** — cycles through role titles with delete/type animation
- **Scroll progress bar** — gradient bar at top tracking page scroll
- **Animated gradient border** on cards — conic gradient rotates on hover
- **3D card tilt** on project cards — mousemove parallax effect
- **Fade-up scroll animations** via IntersectionObserver
- **Project spotlight** — sticky sidebar that updates when cards are clicked
- **Project filtering** — filter buttons by category (All/AI-ML/Backend/Cybersecurity/Data)
- **Skills proficiency bars** — animated fill bars per skill
- **Contact form** — mailto-based submission with success state
- **Responsive breakpoints** — 960px and 600px
- Google Fonts: Syne (display), DM Mono (body), Instrument Serif (italic accents)

### Sections
1. **Hero** — name, role typer, bio, CTA buttons, terminal card + stat cards
2. **About** — narrative text, stat boxes (9 projects, 5+ certs, 16+ security patterns, 1 publication), focus tags, publication card
3. **Experience** — Sukrit Technologies AI Internship (Feb 2 2026 - Jul 17 2026), guided by Mr Rajeev Kumar, with certificate PDF link
4. **Skills** — technical skills with proficiency bars, certifications list with Sukrit certificate PDF link
5. **Projects** — 9 projects: CyberTwin, Fortify Docs API, SecureScan AI, E-commerce Pipeline, Nmap Port Scanner GUI, File Reader, Price Guard, Axon Core, Orion Client Lifecycle AI
6. **Education** — GGSIPU AIDS (2023-27), Bal Bharati Public School (2017-23)
7. **Contact** — email/GitHub/LinkedIn links + contact form
8. **Footer**

### Projects Data (`projects` array in JS)
| ID | Title | Categories |
|---|---|---|
| cybertwin | CyberTwin | AI/ML, Backend, Cybersecurity |
| fortify-docs-api | Fortify Docs API | AI/ML, Backend |
| securescans | SecureScan AI | Cybersecurity |
| ecommerce | E-commerce Data Pipeline | Data |
| portscan-gui | Nmap Port Scanner GUI | Cybersecurity |
| file-reader | File Reader | Backend, Cybersecurity |
| price-guard | Price Guard | Backend, Data |
| axon-core | Axon Core | AI/ML, Backend |
| orion-client-lifecycle-ai | Orion Client Lifecycle AI | AI/ML, Data |

## What I Understand About This Project
- Owner: **Prabgun Mokha** — Aspiring Backend & AI Engineer, GGSIPU AIDS student
- Current role: AI Intern at Sukrit Technologies (Feb 2026–present)
- LinkedIn: https://in.linkedin.com/in/prabgun-mokha-538477291
- Email: prabgunmokha@gmail.com
- GitHub: github.com/prabgunmokha

## Guidelines for This Project
1. **Always report changes before making them** — user explicitly requires pre-approval reporting
2. **Keep colors bright and colourful** — avoid desaturating the palette
3. **Focus on interactivity** — the portfolio already has solid foundations; amplify the micro-interactions
4. **No new projects without telling the user first** — get explicit confirmation
5. **Test responsive behavior** after any layout changes
6. **Maintain the dark mode** — it must work correctly for all sections