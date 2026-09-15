# Brief — frozen premise

Confirmed 2026-09-15. Every research section is judged against this document and may cite it
as `brief §<heading>`.

## Concept

An iOS + Android app for parents to securely share photos of their kids with family,
especially grandparents. Today this happens through Google Photos and WhatsApp groups; the
app centralises it and makes fan-out to WhatsApp / Signal / Facebook Messenger / iMessage
groups easy.

Differentiators against Apple Photos, Google Photos, and the existing family-photo category:

- **Auto-albums from multi-attendee events** — e.g. a child's birthday party: pool photos
  from every attendee's device, including grandparents', into one album.
- **Print-prep, not print fulfilment** — export to lab standards, connectors, email to labs.
  No physical fulfilment by us.
- **Self-hosted storage** as a product feature; roadmap position open (05 evaluates).
- Further features mined from user reviews of competing products (X4).

## Persona

- **Primary**: US parents with kids of any age (0–X, no upper cap). Tech-savvy and
  privacy-savvy. Currently on Google Photos / WhatsApp groups. Section 01 tests whether
  demand concentrates in the 0–5 band, where competitors cluster.
- **Secondary**: grandparents and extended family as **both viewers and contributors**.
  Whether they need a simplified UI at all is an open hypothesis, not a premise (X5).

## Business model

Paid-only family subscription. Parents pay; all other family members are free regardless
of role. No free tier — the product must be self-sustaining from launch. Indicative price
band to test: ~$5–8/month or ~$50–70/year. Print-prep is a feature, not a revenue line.

Rejected alternative: freemium. Reason: costs for the non-paying majority (storage, egress)
are a loss leader until scale, which contradicts self-sustaining from day one.

## Success bar

$3–5k/month net profit.

## Platform

iOS + Android. Self-hosting as a feature; roadmap position to be decided by 05.

## Constraints

Solo builder. Main project, not a side project.

## Known risks

- Apple Photos / Google Photos shipping shared-family features.
- Crowded category: FamilyAlbum, Tinybeans, Lifecake (dead), 23snaps (dead), Notabli, others.
- Grandparent adoption friction and abandonment.
- Kids' biometric / COPPA law constraining face grouping (X2).

## Idea-specific sections

| ID | Question | Blocker |
|---|---|---|
| X1 | Cross-messenger share-out: what can an app push into WhatsApp/Signal/Messenger/iMessage groups beyond the OS share sheet? | no |
| X2 | Auto-album from events: multi-device pooling from all attendees incl. grandparents, face grouping, COPPA / biometric law | no |
| X3 | Print-prep: lab standards, connector APIs, evidence of demand | no |
| X4 | Review mining: recurring pain points in FamilyAlbum / Tinybeans / Google Photos reviews | no |
| X5 | Grandparent role: do they contribute or only consume? Adoption and abandonment evidence; does a simplified mode help or hurt? | no |
