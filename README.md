# NYC Agentforce Vibes Workshop

Workshop site for the Agentforce Vibes workshop (multi-agency NYC-area audience).

- **Date:** November 4, 2026
- **Location:** Salesforce Tower, NYC
- **Live site:** https://tmurphy-sfdc.github.io/nyc-agentforcevibes-workshop-november-2026/workshop-site/

Site shell is structurally modeled on the MTA ServicePulse 360 workshop site
(hero fact tiles, sticky nav, expandable lab-guide cards with step/callout
formatting), adapted for a shorter single half-day format: no Day 2 Verify,
Instructor Team, Internal Prep, or Thank You sections. Branding uses the
standard Salesforce cloud logo and color palette, not MTA branding.

## Structure

- `workshop-site/` — the published site. GitHub Pages is configured to deploy
  from the repo root on the `main` branch, so the live URL above includes the
  `/workshop-site/` path because that's where `index.html` lives, not because
  Pages is pointed at that subfolder directly.
  - `index.html` — main site shell (Agenda, Prerequisites, Workshop Guides)
  - `assets/images/` — logo and other images
