# Allog USA Market Watch

Persistent source of truth for the weekly **Allog USA Logistics Market Watch / Diesel Market Snapshot**.

This repository records how the report is researched, interpreted, written, reviewed, and visually presented so that ChatGPT, Codex, and future collaborators can reproduce the established standard without relying on chat history alone.

## Audience and purpose

The report is written in Portuguese for Allog colleagues and clients who use Allog for U.S. door delivery, drayage, trucking, warehousing/transload, rail/intermodal coordination, and flatbed/open-deck transportation.

The goal is not to publish a generic freight-news digest. Each edition should answer:

1. **What materially changed?**
2. **Where is it happening?**
3. **How can it affect cargo availability, pickup, delivery, routing, storage, capacity, or quote stability?**
4. **What is Allog monitoring to preserve service predictability?**

If there is no meaningful current development in a section, shorten or omit it rather than filling space with generic language.

## Core recurring signals

- DOE/EIA U.S. on-highway diesel prices by PADD and California.
- Direction of crude oil / energy markets at a client-relevant level.
- Flatbed/open-deck rate and capacity indicators.
- Logistics Managers' Index (LMI), especially **Transportation Capacity**, **Transportation Prices**, and warehousing indicators.
- Current port, terminal, rail-ramp, drayage, and labor developments.
- FMCSA/DOT/CVSA/Federal Register compliance developments that have a fresh operational impact.
- Emerging freight-fraud and carrier-identity risks when supported by credible research or primary sources.

## Repository map

- [`AGENTS.md`](AGENTS.md) — operating instructions for ChatGPT/Codex.
- [`docs/EDITORIAL_STANDARD.md`](docs/EDITORIAL_STANDARD.md) — tone, framing, structure, and freshness rules.
- [`docs/SOURCE_HIERARCHY.md`](docs/SOURCE_HIERARCHY.md) — preferred sources and corroboration rules.
- [`docs/METRICS_AND_METHODS.md`](docs/METRICS_AND_METHODS.md) — diesel, LMI, flatbed, port/rail, and compliance methodology.
- [`docs/IMAGE_STANDARD.md`](docs/IMAGE_STANDARD.md) — locked Allog weekly visual format.
- [`docs/WEEKLY_WORKFLOW.md`](docs/WEEKLY_WORKFLOW.md) — recurring research-to-publication workflow.
- [`watchlists/COMPLIANCE_WATCH.md`](watchlists/COMPLIANCE_WATCH.md) — topics to monitor for fresh developments.
- [`templates/WEEKLY_EMAIL_TEMPLATE.md`](templates/WEEKLY_EMAIL_TEMPLATE.md) — standard report skeleton.
- [`templates/IMAGE_COPY_TEMPLATE.md`](templates/IMAGE_COPY_TEMPLATE.md) — required map fields and five image highlights.
- [`decisions/DECISION_LOG.md`](decisions/DECISION_LOG.md) — durable editorial and visual decisions.
- [`archive/README.md`](archive/README.md) — weekly archive convention.
- [`assets/README.md`](assets/README.md) — reference-image convention.

## Public-repository safety

This repository is public. **Do not commit confidential customer/provider information**, shipment references, BOL/container numbers, private correspondence, internal rates, provider buy rates, dispute files, credentials, account information, or non-public operational data.

Weekly market intelligence stored here should be suitable for public/client-facing use or limited to methodology and publicly sourced research.
