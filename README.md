# Chewy Match: Reducing Product Discovery Friction

> MGMT 6100 Product Development, Carlson School of Management · Team: George, Wenyu, Lili, Saloni Jain
> Saloni Jain's role: designed and ran both primary-research surveys, synthesized all 15 interviews/responses into the need statements and concept scorecard below.

A product-development sprint on Chewy.com: find out what's actually broken about buying pet
supplies online, then design and score a concept to fix it — using real primary research, not
assumptions.

## Process

```mermaid
flowchart LR
    A[15 interviews & surveys] --> B[8 gaps with quote evidence]
    B --> C[Need statements: % expressing each]
    C --> D[Concept scorecard: 5 concepts]
    D --> E[Chewy Match]
```

## Research base

**15 total touchpoints**: 9 live interviews (6 pet owners interviewed by George, 2 by Wenyu, 1 by
Lili) plus 6 survey responses (5 from a pet-shopping-experience survey, 1 from
a veterinary-sciences-student survey — both designed and run by Saloni Jain).

## What we found — 8 real gaps, not assumed ones

| Gap | Evidence |
|---|---|
| **No pet profile engine** — every session starts from zero | *"It's more just a search engine rather than algorithm based."* |
| **No vet-linked health records** — owners manually cross-reference diagnoses to products | *"I wish it was like Epic where anywhere with the system can access your pet's health and recent diagnosis from the vet."* |
| **No peer-matched reviews** — can't filter reviews by pet age/breed/condition | *"I want reviews from other owners with similar pets — not official marketing fluff."* |
| **No first-time-owner onboarding** — no starter kit or guided flow | *"So many options when I first got my cat."* |
| **No nutritional filtering** — can't filter by protein, AAFCO grain-free status, life stage | *"I compare fat and protein content depending on what my cat needs — I search on Xiaohongshu or Google."* |
| **Opaque recommendations** — "you might also like" reads as ads, not guidance | *"Distrust comes from black-box recommendations — feeling like ads rather than helpful suggestions."* |
| **Autoship doesn't adapt** — breaks on prescriptions, multi-pet households, travel | *"I often forget when the next shipment is coming."* |
| **No "what does my pet need now" tool** — no bridge from a life event (new diagnosis, aging) to a shopping list | — |

## From evidence to need statements

Mapped all 15 participants against 5 candidate needs (Y = need expressed) to prioritize, not just
list, what to solve for:

| Need | Expressed by |
|---|---|
| Intelligent curation (cut hundreds of options to a relevant shortlist) | **8 / 10** |
| Health & vet integration | **6 / 10** |
| Pet-matched review access | **5 / 10** |
| Transparent, explainable AI | **4 / 10** |
| New-owner guided onboarding | **3 / 10** |

Curation was the need almost everyone expressed, whether or not they were already Chewy users —
that's why it's the core of the concept below, not the AI/trust angle that gets more attention in
pitches.

## The concept: Chewy Match

A guided-discovery layer combining a persistent pet profile, explainable filters (not a black-box
recommender), and a short, reasoned product shortlist — scored against 4 alternative concepts on
evidence strength, customer value, trust & safety, feasibility, and testability (`docs/concept-scorecard.csv`).
Treated as a concept, not a launch-ready system: would need veterinary, privacy, accessibility, and
experimentation review before shipping.

## Repository contents

- [Research plan](docs/research-plan.md)
- [Concept scorecard](docs/concept-scorecard.csv)
- [Measurement plan](docs/measurement-plan.md)
- [Responsible product guardrails](docs/responsible-product-guardrails.md)

## Data & privacy note

Interview subjects and survey respondents are described by pet/situation, not named, to protect
their privacy — quotes above are verbatim, attribution is anonymized. Raw survey files (which
include first names) are not included in this public repo.

## Methods

Customer discovery interviews · survey design · VOC synthesis · need-statement writing ·
weighted concept scoring · responsible-product review
