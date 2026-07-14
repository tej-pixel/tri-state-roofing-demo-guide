# Tri-State Commercial Roofing — Sales Cloud Demo Guide

Internal AE playbook for walking the Tri-State Roofing team through their relationship-driven Sales Cloud POC.

**Live:** https://tej-pixel.github.io/tri-state-roofing-demo-guide/

## What's in here

- `index.html` — 4-step demo guide with screenshots, click paths, talking points, a "What we heard" opener, the Sales Path reference, a what's-live table, quick-reference, and an objection-handling appendix
- `screenshots/` — full captures from the live trial org against seeded demo data

## Build context

- Commercial roofing contractor moving off Dropbox + Company Cam to a real CRM; relationship-driven sales from bidding platforms (BuildingConnected, BlueBook), networking, and referrals
- Model: **Lead** = bidding-platform/networking prospect, **Account** = building/owner, **Opportunity** = roof project, **Owner** = Conor (VP Estimation)
- Sales Path (Opportunity, "Tri-State Roofing" record type): **Prospecting → Evaluation → Proposal Sent → Negotiation → Closed Won**
- Opportunity fields: Roof Condition, Scope Notes, Evaluation Date, Photo Reference, Proposed Solution, Est. Project Value, Proposal Sent Date, Days Since Proposal (formula)
- Lead fields: Prospect Type, Bidding Platform, Lead Source Detail, Evaluation Status
- Quick actions (Log Roof Evaluation, Send Proposal) + record-triggered flows (auto follow-up & stale-deal tasks)
- 8 reports + the **Tri-State Leadership Dashboard** (pipeline/forecast by month, new leads, conversion, win rate, avg days in proposal, closed-won trend)
- Seeded demo data: Conor Jones + Dana Cole · 9 building/owner accounts · 17 deals across all stages (~$3.1M open, ~$3.7M total) · 11 bidding-platform leads · roof evaluations & logged activity

> Note for the build team: the two Lead reports (Lead Source Effectiveness, Lead-to-Opportunity Conversion) were switched from `user` scope to `org` ("All leads") so the dashboard tiles populate for the running user. Trial org expires 2026-07-21.

Built by SaaScend.
