# BD Pipeline Console

An interactive business-development pipeline dashboard for a tech / software-services sales motion. Built as a single self-contained web page to show where revenue sits in the pipeline, how leads convert through the funnel, and which acquisition channels actually perform.

**Live demo:** https://jiyatejwani.github.io/bd-pipeline-console/

## What it shows

- **KPI rail** — open pipeline value, forecast-weighted pipeline, win rate, average deal size, qualified leads, and revenue vs target.
- **Conversion funnel** — lead → contacted → qualified → proposal → negotiation → won, with stage-by-stage drop-off so you can see where deals stall.
- **Forecast-weighted pipeline** — open pipeline adjusted by each stage's close probability (Lead 10% · Qualified 30% · Proposal 50% · Negotiation 75%), so the headline reflects likely revenue rather than gross pipeline.
- **Pipeline by service line** — open deal value across IT / software service lines (AI/ML, Cybersecurity, Cloud & DevOps, Custom Software, ERP/CRM, Digital Transformation, and more).
- **Channel ROI** — win rate by lead source (cold calling, email, LinkedIn, referrals, networking, inbound); referrals and inbound convert best despite lower volume.
- **Priority deals & follow-ups** — a deal table filterable by stage, sorted by follow-up date, with overdue and due-soon flags on every open deal.
- **Light / dark theme** toggle.

## Tech

- Vanilla HTML, CSS and JavaScript — no build step, no framework.
- [Chart.js](https://www.chartjs.org/) for the funnel, service-line, revenue and channel charts.
- All KPIs are computed in-page from a single deals dataset, so the headline numbers always reconcile with the table.

## Data

All companies, deals and figures are **synthetic and illustrative**, modelled on a mid-size IT / software-services sales motion. No real client data is used.

## Run locally

Open `index.html` in any browser — there is nothing to install or build.

## Author

Jiya Tejwani — [LinkedIn](https://linkedin.com/in/jiyatejwani015) · [GitHub](https://github.com/jiyatejwani)
