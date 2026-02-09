# NewSpace NTN & D2D Atlas
**Version:** v0.2.0 (Academic Draft)  
**Last updated:** 2026-02-09

A public, evidence-oriented **technical atlas** covering:
- **New Space satellite communications (SatCom)**
- **3GPP NTN (Non-Terrestrial Networks)**
- **D2D/DTC (Direct-to-Device / Direct-to-Cell)**

The writing style is intentionally **academic and technically rigorous** (definitions → assumptions → models → implications → references).

## Authors
- **Andy (Andrija Kolundžić)** — *Japan IT Business* (Project Owner / Maintainer)
- **Dragorad Milovanović** — *Co-author* (R&D materials and domain expertise)

## Live Docs (GitHub Pages)
- https://kolundzic.github.io/newspace-ntn-d2d-atlas/

## Structure
- `01_foundations/` — definitions, scope, terminology
- `02_orbit-and-radio/` — constellation geometry, orbit types, link budgeting concepts
- `03_d2d-and-dtc/` — D2D service models, handset constraints, ecosystem notes
- `04_latency-and-handoff/` — RTT, handoff frequency, availability modeling
- `05_ops-and-trust/` — SSA, failure modes, evidence schema, ops playbook
- `06_use-cases/` — pilot scenario specifications
- `07_project-bridges/` — trust seal, evidence badge, public authority

## Quick contribution rule
Every non-trivial claim should have:
- stated assumptions,
- a method (reference or computation),
- and references to primary sources where possible.
