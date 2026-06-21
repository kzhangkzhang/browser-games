# Kevin.AI — Portfolio Site Spec

## Overview
- **Brand:** "Kevin.AI" — dark, techy/AI-themed personal portfolio
- **Goal:** Personal brand / showcase (not strictly recruiter-optimized, but should still communicate experience and skills clearly)
- **Structure:** Single-page scroll site with anchor navigation
- **Tech:** Plain HTML/CSS/JS, single self-contained file (`portfolio.html`), no build step — same pattern as the rest of this repo (`tic-tac-toe.html`, `shooter.html`)
- **Animation level:** Subtle — fade-ins on scroll, hover effects, maybe a subtle gradient/grid background. No heavy particle effects or typing animations.
- **Hosting:** GitHub Pages

## Visual Style
- Dark background (near-black, e.g. `#0a0a0f` / `#0d1117` range)
- Glowing accent color (suggest electric blue or violet — to be confirmed) for links, headings, hover states
- Monospace or geometric sans-serif font pairing to lean into the "AI/techy" feel (e.g. a sans for body, monospace for code-like accents/labels)
- Subtle grid or gradient texture in the hero background
- Generous whitespace/padding between sections despite the dark theme — should not feel cluttered

## Navigation
Sticky top nav bar with anchor links to:
- Home
- About
- Experience
- Contact

(No separate Projects/Skills nav items planned yet for v1 — skills folded into About, projects deferred — confirm before build.)

## Sections

### 1. Hero / Home
- Big "Kevin.AI" wordmark/logo as the primary heading
- Tagline: **TBD — need a one-liner from Kevin** (placeholder: "Building enterprise systems with two decades of Oracle, big data, and full-stack craftsmanship.")
- Subtle call-to-action / scroll cue down to About

### 2. About
- Short bio paragraph (placeholder — to be written, can draw from experience below: 20 years at Knowles Corporation, Oracle APEX & EBS specialist, big data/analytics work, self-taught in modern web tech)
- **Technical skills** (grouped):
  - Oracle Platform: APEX (4.x/5.x/19.x), Oracle EBS R12/11i (Finance, Discrete & OPM Mfg, HR, Order-to-Cash, Procure-to-Pay), Oracle Cloud Infrastructure (OCI)
  - Big Data & Analytics: Cloudera CDH5.x, Hadoop, Hive, Sqoop, Apache Airflow, Apache Nifi, Anaconda/Python, cx_Oracle, R
  - Web: HTML5, CSS3, jQuery, AJAX
  - BI: IBM Cognos BI v8.4.1, OBIEE, Oracle HCM, Demantra
  - Tools: VSCode, Git/GitHub, Git Bash, Cygwin, Cmder, Windows Terminal, Oracle VM, Unix/Shell scripting
  - Integration: B2B (E2Open, sFTP), application/cloud integration architecture
- **Characteristics / why hire me** (derived from experience, confirm wording):
  - Self-taught and fast learner — picked up modern web/mobile and big data stacks without formal training
  - Technical mentor — leads and mentors offshore development teams, "go-to" person for the team
  - Bridges silos — works across dev, DBA, and functional/business teams as the connective technical lead
  - Process-driven — defined SDLC and contributed the majority of the team's coding framework
  - Delivery track record — led multiple EBS version upgrades (11.5.10 → 12.1.3 → R12.2), M&A integrations, and ITAR compliance implementation
  - Curious / forward-looking — proactively explores new tech (OCI, big data, predictive analytics for "smart manufacturing")

### 3. Experience
Reverse-chronological list/timeline, all under **Knowles Corporation** (Itasca, IL), 20 yrs 1 mo total:

1. **Application Development Manager** — Full-time — Jan 2026–Present (6 mo)
   - *Details/bullets: TBD — role just started, confirm what to highlight*

2. **Sr. Application Technical Lead & Solution Architect** — Full-time — Jun 2014–Jan 2026 (11 yr 8 mo)
   - Designed and built 13+ modern, business-critical internal web applications using Oracle APEX (4.x/5.x/19.x), HTML5, CSS3, jQuery, AJAX, integrated with the EBS workflow engine and BlackBerry Access secure browser container
   - Led big data initiative converting manufacturing to "smart" manufacturing using Cloudera BDA (Hadoop, Hive, Sqoop, Airflow, Nifi, Python, R) for predictive analytics
   - Technically led and mentored an offshore Oracle ERP (R12) development team; defined SDLC and authored ~60% of the team's shared coding framework
   - Designed and managed Oracle EBS upgrades (11.5.10 → 12.1.3 → R12.2)
   - Led ITAR compliance implementation and EBS rollouts for acquired and divested business units
   - Built B2B integrations with customers/suppliers (E2Open, sFTP) and cross-application/cloud integration architecture
   - Working knowledge of Oracle HCM, Demantra, OBIEE, and OCI

3. **Oracle Apps Technical Lead** — Feb 2012–Jun 2014 (2 yr 5 mo)
   - Investigated and advocated new technology solutions, defining team standards
   - Served as primary technical gateway between developer, DBA, and functional teams
   - Lead developer/system analyst for Manufacturing, Finance, and HRMS modules on Oracle EBS 11i (11.5.8–11.5.10) and IBM Cognos v8.4.1 (BI)
   - Coached the global development team on SDLC, coding standards, performance tuning, and integration architecture

4. **Sr. Programmer/Business Analyst** — Jun 2006–Feb 2012 (5 yr 9 mo)
   - Technical/architecture lead across Oracle EBS R12/11i (OPM Mfg, Discrete Mfg, Finance, HR, SOA, B2B, APEX)
   - Worked with IBM Cognos BI v8.4.1 and Oracle APEX

*Note: bullets for roles 2–4 are adapted directly from Kevin's LinkedIn copy; role 1 bullets still needed.*

### 4. Projects
- **Deferred for v1** — placeholder section/cards to be added later once specific GitHub repos are chosen for showcase (browser-games repo, e.g. `tic-tac-toe.html` / `shooter.html`, was discussed as one candidate).

### 5. Contact / Footer
- LinkedIn: https://www.linkedin.com/in/kevin-zhang-apex-ebs-bigdata/
- Email: **TBD — placeholder, Kevin to provide**
- No GitHub link confirmed for this section yet (optional add later)

## Open Items Before Build
- [ ] Final tagline for hero
- [ ] Bullets/highlights for "Application Development Manager" role (started Jan 2026)
- [ ] Confirm accent color choice
- [ ] Decide whether to add Projects/Skills as separate nav items
- [ ] Provide email address for contact section
- [ ] Decide on GitHub projects to showcase (or confirm deferring to v2)
- [ ] Review/approve "characteristics" wording (currently inferred from experience text, not Kevin's own words)
