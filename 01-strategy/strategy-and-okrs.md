# Product Strategy & OKRs: Meridian Foundations

> Module 1 · Write a Strategy That Can Survive a Test

## 1. Playing to Win cascade

| Question | Your choice |
|---|---|
| **Winning aspiration** | Foremen and superintendents choose Meridian over their group text because it takes less effort than texting and does their daily reporting for them. PMs and finance get field updates within hours, tagged to project and cost code, in the system of record. |
| **Where to play** | Unchanged for now. Flagged: “more than 2 active sites” doesn’t match where you’re churning ($5M–$50M projects). Revisit after #3. |
| **How to win** | Replace the foreman’s daily paperwork and photo-and-text handoff with zero-friction, offline-capable capture that feeds the system of record automatically. The foreman does less work and the office gets more data. Closing the loop to the ERP follows from that, but it isn’t the way to win. |
| **Capabilities required** | Offline-first capture (photo, voice note, quick status), auto-tagged to project, site and cost code Daily log generated from what the foreman already sends Low-friction access (minimal login steps) and messages that reach the office Additive to the existing data model and APIs, with no changes to the enterprise features finance and compliance use Open, to be decided in #4: the form factor of the field client |
| **Management systems** | - North-star: % of field updates reaching the PM, correctly tagged to project, site and cost code, within 4 hours. - Foreman adoption (leading): 1. Channel share: % of a site’s field updates sent through Meridian instead of the group text 2. Working-day active foremen at activated accounts 3. Foreman retention: % still active at week 4 after first use. - Guardrails: 1. No decline in finance/PM usage, and no enterprise feature removed 2. Auto-tag accuracy: share of tags the PM has to correct 3. No required fields in the field client (the hard no) - Lagging (quarterly):  1. Gross retention and churn in the $5M–$50M segment 2. Expansion in accounts with active field use 3. Enterprise acquisition, tracked but secondary |

## 2. Your one hard no

> **Hard no:** We will not ask foremen to fill in forms or required fields. Field capture is limited to photos, voice notes and one-tap status, which the system auto-tags to site, project and cost code and turns into the daily log and other records the office needs. If a feature adds friction for the foreman, it doesn’t ship in the field client, even when finance or compliance asks for it.

## 3. OKR cascade

> **Objective:** Foremen choose Meridian over the group text, and the office trusts what it sees from the field.
>
> - **KR1:** Adoption: Channel share at pilot sites rises from [baseline] to 50%, meaning half of field updates go through Meridian instead of the group text.
> - **KR2:** Outcome: 80% of those updates reach the PM correctly tagged to project, site and cost code within 4 hours.
> - **KR3:** Office value: 70% of daily logs at pilot sites are generated automatically and accepted by the PM without edits.

## 4. AI pressure-test

**Most valid challenge:** It challenged my assumption that building a mobile app would save the adoption issue. My initial draft gave the benefit (traceability, real-time data) to the office and the cost (extra steps) to the foreman, and it never explained why he’d choose it over a group text that costs him nothing.

**What I will change and what I will defend:** I updated the strategy to focus on the problem and less about the solution itself. I also over indexed on the enterprise benefit that I added costs to the foreman persona, who currently represents the main blocker. I updated the strategy accordingly.
