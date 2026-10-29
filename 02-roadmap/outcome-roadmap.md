# Outcome Roadmap & Trade-off Memo: [Fable / Meridian / your initiative]

> Module 2 · Turn Your Strategy into an Outcome Roadmap, ★ Deliverable 2

## 1. Outcome roadmap

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| Now (0 to 3 mo) | _test____ | __test___ | __test___ |
| Next (3 to 6 mo) | __test___ | ___etes__ | __test___ |
| Later (6 to 12 mo) | __test___ | __test___ | __test___ |

Roadmap visual: _____

## 2. Trade-off memo

> **Rock #1:** Rock #1: #1 Offline-first mobile experience. Site leads won’t log 3+ days a week if the app fails on a site with no signal, so this is the base for KR1. Our capacity rule also makes it a prerequisite for everything in Q2.
>
> **Rock #2:** Rock #2: #4 Simplify the daily log from 14 fields to 4. Daily logs are our first Q1 use case. Cutting the fields is the cheapest, most direct way to raise how often site leads log (KR1) and to make logging quicker than a group text.
>
> **Rock #3:** Rock #3: #2 Photo markup and annotation, scoped to include tagging existing subcontractors on an issue. Issues and snags with photos are our other Q1 use case, so this moves the share of issues raised in the field app (KR2). Tagging subs routes issues to the right person sooner, which also helps KR3.
>
> **Hard No #1:** Hard No #1: #10 Executive reporting dashboard with custom KPIs. Our one hard no is new enterprise analytics during Foundations, and dashboards built on data the field never enters just build on the gap. Customer success will manage the two at-risk renewals using existing reporting.
>
> **Hard No #2:** Hard No #2: #7 Separate foreman app. Our strategy is one capture layer added to the core platform, and a second app would split our 5 mobile engineers and the data. The field need is real, and Rocks 1–3 meet it inside the core product.
>
> **Hard No #3:** Hard No #3: #12 Time-tracking module. It’s a new module for 3 deals in negotiation, it does nothing for field adoption, and its effort is as high as offline sync. That would break our capacity rule.

## Link to full artifact

_[link to this deliverable in your repo]_

## Lab notes

**Show and swap**

- **Do the Rock selections feel traceable to a clear strategy, or do they read like a feature list?:** _____
- **Pick one Hard No and make the case for why it should actually be a Rock.:** _____

**Review and refine**

- **Does every Now item read as a strategic bet, or does it sound like a feature description?:** Partly. Each one is written as “if X, then Y”, but the brackets name features (offline-first, 4 fields, photo markup), so the eye lands on the solution. None says how we’d know the bet has failed, so they read more like hopes than testable bets. Bet 2 also puts the solution (“4 fields”) in the bet itself.
- **Can you trace every Now item back to one of your OKRs?:** Yes. Two map to KR1 and one to KR2. KR3 has no Now item, which is deliberate: it’s measured this quarter and committed in Q2, and the column says so. The weak spot is that two of the three bets sit on KR1, so if KR1 stalls, most of the quarter stalls with it.
- **If someone who had never seen your strategy read the Now column, would they know what problem you are solving this quarter?:** No. It explains what we’re betting on but not the problem behind it: field teams record site work in phone cameras and WhatsApp, and the office re-keys it late or never. “Site leads”, “sub” and “re-keyed” also assume you already know the context.
[outcome-roadmap.md](https://github.com/user-attachments/files/34129441/outcome-roadmap.md)
# Outcome Roadmap & Trade-off Memo: [Fable / Meridian / your initiative]

> Module 2 · Prioritization & Roadmapping for Product Leaders, ★ Deliverable 2
>
> Translate your strategy into a multi-team, outcome-driven roadmap, and a memo defending the hard prioritization calls behind it.

## 1. Outcome roadmap

_A multi-team roadmap organized by **outcomes**, not feature lists. Show how near-term revenue pressure is balanced against long-term platform bets._

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| Now (0 to 3 mo) | _____ | _____ | _____ |
| Next (3 to 6 mo) | _____ | _____ | _____ |
| Later (6 to 12 mo) | _____ | _____ | _____ |

_[screenshot or shareable link to your roadmap visual]_

## 2. Trade-off memo

_What did you sequence first, what did you push out, and what did you cut entirely, and why? Use WSJF / cost of delay reasoning where it helps._

> I chose to sequence … first because …
>
> I pushed out … because …
>
> I cut … entirely because …

## Link to full artifact

_[link to this deliverable in your repo]_

# Meridian Foundations: Now / Next / Later Roadmap

_As of 15 October 2026_

## The problem this quarter

Field teams record site work in phone cameras and group texts, so the office re-keys it late or never. This quarter we prove that site leads on our $50M+ enterprise accounts will choose Meridian instead, without being told to.

- **Objective:** Make Meridian the way field teams record site work on our $50M+ enterprise accounts, replacing phone cameras and group texts.
- **North star:** % of site leads (superintendents and foremen) logging in Meridian 3+ days a week on pilot projects.
- **Gate from Now to Next:** nothing in Next starts until offline sync is stable on pilot sites.
- **Guardrails:** enterprise renewal rates, office admin NPS and office use of enterprise features hold steady.

## Now: Q1 bets

Three bets, each tied to an OKR and each with a signal that tells us whether it is working.

| Bet | We'll know it's working if… | OKR |
| --- | --- | --- |
| **Field teams will only rely on Meridian daily if it never fails them on site, even with no signal.** | Pilot site leads logging 3+ days a week rises towards 50%, and low-signal sites keep pace with the rest | KR1 |
| **A daily log that's quicker than a group text will win foremen over on its own merits.** | At least one pilot site reaches 40% with no head-office mandate | KR1 |
| **If raising an issue with a photo and the right subcontractor takes seconds, the field will raise it in Meridian, not WhatsApp.** | Share of issues raised in the app rises from 20% towards 70%, and pulse surveys show group-chat use falling | KR2 |

> **KR3** (median time from an issue raised on site to first office action) is measured this quarter, not committed. We set its baseline from issues raised in the app on pilot sites, then commit to the under-4-hours target in Q2.

## Next: Q2, once the gate is met

These start only when offline sync is stable on pilot sites.

| Item | Why it comes after Now |
| --- | --- |
| **Route field issues to a named office owner, with alerts** | Only pays off once issues are flowing through the app. This is where KR3 becomes a committed target. |
| **RFI capture in the field, with AI-assisted drafting** | A Q2 use case. The capacity rule holds it until offline sync is stable. |
| **One route from field change orders to ERP cost codes** (pilot accounts' ERPs only) | The single exception to our hard no. Only worth building once the field is actually capturing change orders. |
| **Voice capture** (speech-to-text partner) | Extends the capture layer, but only after photo and log capture are proven and stable. |
| **Validate per-active-project pricing with pilot accounts** | Pricing for expansion needs adoption evidence first, which the quarterly pilot review produces. |

## Later: bets, not commitments

These are right for the strategy but not resourceable yet. Each is a bet we'll revisit at the quarterly pilot review.

| Bet | What we'd need to believe |
| --- | --- |
| **Win back mid-market**, using the field experience as the wedge | Field UX, not price or implementation burden, is what's driving that churn (untested) |
| **Auto-tagging to drawings and BIM** through partners | Tagging to location and drawing deepens our system-of-record advantage |
| **Deeper subcontractor collaboration** | Subs pulled into field threads will want more than issue tags |
| **Compliance checklists generated from field data** | Once site data is real, compliance can be generated rather than built by hand |
| **Enterprise analytics on field data** | Analytics are worth building only once the data reflects what's actually happening on site |

## What we're not doing

| Item | Why not this quarter |
| --- | --- |
| Executive reporting dashboard with custom KPIs | Breaks our one hard no on new enterprise analytics. Customer success protects the two at-risk renewals using existing reporting. |
| Separate foreman app | Our strategy is one capture layer in the core platform. A second app would split the mobile team and the data. |
| Time-tracking module | A new module for 3 deals in negotiation that doesn't move field adoption, at the same effort as offline sync. |
| Web UI refresh | Desktop is out of scope during Foundations. |
| Weather integration | Low impact on field adoption. |

**Maintenance, outside the roadmap:** the Procore import/export fix goes ahead, because existing features stay fully supported as contracts require.
