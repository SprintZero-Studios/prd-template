# Awas: Product requirements document

<!-- A filled example of PRD.md: the PRD from a real Murmur run, published with
     the owner's permission. Text is as the run wrote it; only the layout
     follows this template. Full run: https://www.trymurmur.studio/examples/aavaas -->

## One-liner

Awas is a mobile-friendly web app that turns a spoken or typed brief about your plot and family into 2–3 floor plans with plainly stated trade-offs and a 3D house you can walk through, before your first architect meeting. Catalogue sellers like Architects House start from pre-designed models, and AI generators like Ideal House start from menu picks, so neither starts from your plot and family.

## Problem

Most Indian families build a house once, on a plot they saved for years to buy. They reach an architect with a plot size, a few Pinterest screenshots and a vague list (four bedrooms, parking, puja room, maybe a lift) and cannot read a floor plan. They approve things they don't understand and find the mistakes on site when a wall is already up. Architects spend the first 3 or 4 meetings working out what the client wants, and revisions are unpaid or disputed. Research shows the gap: Architects House and DBYO start from a pre-designed base model, Ideal House starts from style, size and room menus, and NextAwas ties planning to its construction service. None of the sources states a plot-and-family spoken intake, plainly stated trade-offs per option, or live revision with an instantly rebuilt 3D model, though that absence is not established from the sources reviewed.

## Target user

First-time homeowners building on their own plot in Indian Tier 1 to Tier 3 cities, using Awas in a phone or desktop browser, before they meet an architect. NRIs building back home are served through shared views of the same project.

## Features

### Must have

#### Spoken or typed plot-and-family brief

- **Description:** The user speaks or types one free-form brief covering plot size, road side, family, cars, work-from-home needs and Vastu preference. Awas turns it into a structured design brief.
- **Rationale:** Founder: 'you speak or type: 39 by 60, road to the east... we follow Vastu. That's all.'

#### Design-changing follow-up questions only

- **Description:** Awas asks only the follow-up questions that change the layout, and skips anything that doesn't.
- **Rationale:** Founder: it asks 'only the follow-up questions that change the design.'

#### 2–3 floor plan options for the plot

- **Description:** From the brief, Awas generates 2 or 3 floor plan options fitted to the stated plot, honouring Vastu when the user asks for it.
- **Rationale:** Founder: it 'shows 2 or 3 floor plan options'; Research: Indian context such as Vastu is table stakes.

#### Plain-language trade-offs on every option

- **Description:** Each option states what it costs and gains in plain words, such as the cost of a double-height living room or the car limit of an open drive.
- **Rationale:** Founder: 'every trade-off stated plainly'; Research: no source states per-option trade-off explanations.

#### Instant 3D house with dollhouse floor cut-away

- **Description:** Each plan option builds a furnished 3D model that renders in a phone browser. The user can cut any floor open like a dollhouse.
- **Rationale:** Founder: 'the house builds itself in front of you', cut open like a dollhouse; Research: 3D renders are table stakes.

#### Walkthrough as a little person or at eye level

- **Description:** The user walks through the 3D house in two modes: small-figure view and eye-level view.
- **Rationale:** Founder: the walkthrough is how the family catches decision mistakes, as in the Dehradun story, and a payoff of the product.

#### Revise by talking or typing, with instant 3D rebuild

- **Description:** The user changes the design in plain language ('the staff room is too small, open the kitchen to the dining'). The plan and the 3D model update immediately.
- **Rationale:** Founder: 'you revise by talking... every change rebuilds the 3D house instantly.'

#### Plan export as PDF and image

- **Description:** The user downloads each floor plan as PDF and image to hand to a builder or architect.
- **Rationale:** Research: exports a builder or architect can use are table stakes, offered by Architects House.

#### Saved project with simple sign-in

- **Description:** A project saves to a lightweight account, so briefs, revisions and the 3D model persist across sessions and devices.
- **Rationale:** Recommended: revisions, walkthroughs and exports can't work across sessions without persistence.

### Should have

#### Hindi interface

- **Description:** The UI, prompts and trade-off text work in Hindi as well as English.
- **Rationale:** Research: Ideal House already offers Hindi pages, and the founder's audience is Tier 1–3 families.

#### Vastu as a toggle with stated trade-offs

- **Description:** The user can turn Vastu on or off in the same flow, and Awas states what the choice costs in layout terms. Unlike DBYO, which lists Vastu as N/A on its Vastu-independent surface, nothing forces a surface switch.
- **Rationale:** Research: DBYO and Architects House split Vastu and non-Vastu paths; Founder: Vastu is handled as a design constraint.

#### Decision rationale page

- **Description:** A one-page summary gives the reason for each major design decision.
- **Rationale:** Founder: the user leaves with 'a page of reasons for every decision.'

#### Architect brief and architect-openable files

- **Description:** Awas exports a structured brief plus plan files an architect can open, so the first meeting starts from the model. Competitors export plans, but none states a brief that cuts meetings.
- **Rationale:** Founder: 'files your architect can open' and the aim of skipping 2 meetings of guesswork.

#### Setback and coverage guard rails for one launch region

- **Description:** For one launch city, plan options flag obvious setback and built-up-area limits. These are flags, not a compliance check.
- **Rationale:** Recommended: NextAwas states bylaw awareness in planning, and the founder lists encoded bylaws as part of the moat.

#### Send any view to family on WhatsApp

- **Description:** The user shares a screenshot or link of any 3D view straight to WhatsApp.
- **Rationale:** Founder: 'send any view to your family on WhatsApp.'

#### Home Pass one-time checkout

- **Description:** A one-time per-plot payment of about ₹2,999 to ₹4,999 unlocks the paid features.
- **Rationale:** Founder: Home Pass is the first revenue line, a one-time per-plot payment.

### Could have

#### Sun study for the user's city

- **Description:** The user checks sunlight on their plot in their own city, such as in December.
- **Rationale:** Founder: 'check sunlight in your city in December'; Research: whitespace, not stated by any competitor.

#### Dusk-lit view

- **Description:** The user sees the house lit at dusk using real-time lighting in the browser.
- **Rationale:** Founder: 'see it lit at dusk.'

#### View-only live model link for remote family

- **Description:** A shareable link opens the live 3D model for family or NRIs who can't visit the site.
- **Rationale:** Founder: NRIs building back home 'need to see the house remotely.'

#### Consent-based city-wise choice logging

- **Description:** With user consent, anonymised design choices are logged by city to train the plan generator.
- **Rationale:** Founder: every project teaches the generator what families choose city by city, and that data is the moat.

### Won't have (this release)

#### Studio edition for architects

- **Description:** No team seats, branded client intake links, project comments or 'onviews'.
- **Rationale:** Founder: Studio is a later variant after the Home version for one family on one plot.

#### Developer edition and plan libraries

- **Description:** No plan libraries per plot type embedded on a colony developer's site.
- **Rationale:** Founder: the Developer variant comes after Home.

#### Plot seller and broker listings

- **Description:** No 'here's what you could build' walkthroughs attached to plot listings.
- **Rationale:** Founder: sellers and brokers are a later audience beyond homeowners.

#### Cost estimate or BoQ from the model

- **Description:** No budget or cost breakdown, even though Architects House and DBYO offer one.
- **Rationale:** Founder: cost estimate comes after the plan, 3D model and bylaw check; Research lists budgets as table stakes, so this is a deliberate gap.

#### Bylaw compliance check and stamped approval drawings

- **Description:** No formal compliance verdict and no approval-ready or stamped drawings, which Architects House offers.
- **Rationale:** Founder: the bylaw check is a later stage after the 3D model.

#### Structural, electrical and plumbing drawings

- **Description:** No services or working drawings of the kind NextAwas provides.
- **Rationale:** Research: NextAwas competes on execution-ready drawings; Awas is the step before the architect.

#### Contractor quotes and construction tracking

- **Description:** No contractor marketplace and no tracking of construction against the model.
- **Rationale:** Founder: these are late stages of the larger vision.

#### Partner referrals, brand partnerships and photo-real render add-on

- **Description:** No paid architect referrals, materials or furniture brand deals, or paid photo-real renders.
- **Rationale:** Founder: these are listed as 'later' revenue lines.

#### Pre-designed model catalogue

- **Description:** No browsable library of ready-made home designs by archetype.
- **Rationale:** Research: Architects House sells 1,000+ catalogue designs; Awas starts from the user's plot and family instead.

#### Native app store apps and irregular or corner plots

- **Description:** No iOS or Android store apps, and no irregular-shaped or multi-road plots.
- **Rationale:** Recommended: the founder describes a browser-on-phone product and a plot with one road side, and these are the likeliest scope traps.

## Success metrics

| Metric | Target |
| --- | --- |
| Share of generated plan options a licensed architect panel rates 'buildable with minor changes' (review of at least 30 plans on a 3-point scale) | ≥70% within 60 days of beta [assumption] |
| Share of started briefs that reach a completed walkthrough | ≥50% within 30 days of launch [assumption] |
| Share of users who change at least one design decision (logged revision) after starting a walkthrough | ≥40% within 90 days of launch [assumption] |
| 90th-percentile time from a revision to the rebuilt 3D model on a reference mid-range Android phone in browser | ≤5 seconds, verified within 60 days of beta [assumption] |
| CSAT on 'the trade-offs were easy to understand' (1–5 scale, post-session survey) | mean ≥4.0 from at least 100 responses within 90 days [assumption] |
| Share of surveyed users who gave exports to an architect and said the brief saved at least one meeting | ≥50% of at least 20 respondents within 90 days [assumption] |
| Conversion of users who complete a walkthrough to Home Pass (one-time purchase) | ≥5% within 90 days of checkout launch [assumption] |
| Model and compute cost per completed project, which with the conversion target above keeps Home Pass gross margin at ≥70% on a ₹2,999 price | ≤₹40 per project in the first 90 days [assumption] |

## Non-goals

- Not a replacement for the architect: output is a draft plan and a brief, not construction or approval drawings.
- Not a catalogue or marketplace of pre-made designs.
- Not a cost, bylaw-approval or construction-management tool in the first version.
- Not a B2B product: no architect, developer or broker workspaces in the first version.
- Not a native app: it runs in a phone or desktop browser.

## Risks

- Plan quality: generated layouts may be unbuildable or poor, since architectural judgment must be encoded, and this is the biggest risk to trust.
- Performance: furnished 3D rebuilds and walkthroughs may be too slow or heavy on mid-range phone browsers.
- Name conflict: 'Awas' closely resembles competitor NextAwas and the common Hindi word for housing, and the founder also uses 'Aavaaz' and 'Ava'.
- Language and bylaw coverage: spoken Hindi and mixed-language briefs may be misparsed, and local rules vary by city, so a wrong guard rail erodes credibility.

## Open questions

- Name: transcript uses 'Awas', 'Aavaaz' and 'Ava' (and opens with 'आवाज़ from the Hindi for training'); Awas is used here. Founder to confirm the final name.
- Which features are free and which sit behind Home Pass? The transcript lists the walkthrough, sun study, share links, exports and architect brief as paid, but priority here is set by importance, not by plan.
- The transcript says both 'free revisions' and 'unlimited revisions for 3 months' under Home Pass. Which is intended?
- Which single launch city's rules should the guard rails cover? Recommended: Dehradun (the founder's own plot, easy to validate); founder to confirm.
- Which spoken languages must the first version support? Recommended: Hindi and English, including mixed speech (the model is Hindi-first in the transcript, but languages are not stated); founder to confirm.
- What does 'files your architect can open' mean? Recommended: PDF plus DXF, the common architect format (it opens in AutoCAD and most design tools); founder to confirm.
- What is 'onviews' in the Studio variant? It is unclear in the transcript and is deferred with Studio.
- Should city-wise choice logging be opt-in at signup or in-session, and how is consent worded?

## Competitive landscape

| Competitor | Positioning delta |
| --- | --- |
| Architects House (AHO / AstroSpeaks) | Sells 1,000+ architect-drawn catalogue designs with Vastu certification and budgets; Awas generates from the user's own plot and family brief with stated trade-offs. |
| DBYO (Design By Your Own) by Architects House | Customises a chosen base model with a Vastu-independent surface; Awas keeps Vastu a toggle in one conversational flow. |
| NextAwas | A construction company whose design service is tied to its build; Awas is a self-serve step before any architect or builder, with no cost or compliance claims. |
| Ideal House | Fast menu-driven AI plans with Hindi pages; Awas starts from a spoken plot-and-family brief and adds trade-offs, revision by talking and walkthroughs. |
| AIDesignHouse | Broad visual and renovation tools from photos and sketches; Awas focuses on plot-based new-build planning and architect handoff. |
