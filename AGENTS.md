# AGENTS.md — Allog USA Market Watch

These instructions apply to the entire repository.

## Mission

Produce a fresh, client-relevant weekly U.S. logistics market report in Portuguese for Allog USA covering diesel, trucking capacity, flatbed/open-deck, warehousing/transload, rail/port/drayage conditions, and current regulatory/compliance developments.

## Non-negotiable editorial rules

1. **Freshness beats completeness.** Do not recycle a topic merely because it is important. Include recurring regulatory or market themes only when there is a new deadline, enforcement action, measurable effect, service change, market reaction, or other current development.
2. **No filler.** Never write generic warnings such as “monitor appointments/chassis/rail dwell” unless a current condition, location, advisory, or data point supports the statement.
3. **Translate data into client impact.** For each material item, explain what changed and how it can affect cargo availability, pickup, delivery, routing, storage, carrier flexibility, or quote stability.
4. **Client framing.** Allog is the service provider. Do not shift operational responsibility to the client. Chassis, pre-pull, storage, detention, demurrage, appointments, empty return, receiving coordination, etc. are operational variables Allog manages. Mention them only as market conditions Allog is monitoring when relevant.
5. **Avoid “extra cost” language unless necessary.** Prefer service-awareness language: reduced flexibility, longer lead time, tighter receiving windows, stronger pricing, more selective capacity, or possible execution impact.
6. **Primary sources first.** Use official agencies, ports, terminals, railroads, and index publishers whenever available. Secondary industry media may provide context but should not replace a primary source for a rule, deadline, closure, price, or official service change.
7. **Do not promote competitors.** Competitor research can be used internally as corroboration, but avoid repeatedly naming logistics competitors in client-facing copy when direct/independent sources are available.
8. **Do not fabricate significance.** If a number cannot be benchmarked meaningfully, do not call it “high,” “low,” “congested,” or “normal” without context.
9. **No stale holiday notices.** Past holiday schedules disappear after the event unless there is evidence of current residual backlog or service impact.
10. **No final diesel image until EIA publishes the new weekly diesel reading.** If the release is pending, prepare the narrative but label diesel/map data pending.

## Standard client-facing structure

Use the following as the default, but shorten or omit a section if there is no material fresh development:

1. Visão geral da semana
2. Diesel e mercado de energia
3. Flatbed / Open-Deck
4. Warehousing / Transload / Transportation Capacity
5. Portos / Rail / Drayage
6. Regulatório e Carrier Compliance
7. Conclusão

Do not create a standalone Container Drayage section if it merely repeats port/terminal/rail issues already covered elsewhere.

## Diesel rules

- Source: DOE/EIA weekly U.S. on-highway diesel data.
- Track national average, WoW, YoY, PADD 1–5, California, lowest region, highest point, reference week, release date, next release date.
- Florida remains in PADD 1 / East Coast.
- Energy commentary should be simple and directional. Clients need to know whether pressure is rising/easing and what it may mean for transportation stability.
- Avoid overly technical wholesale-product detail (e.g. low-sulfur diesel hub prices) unless it materially changes the client-facing conclusion.

## LMI / capacity rules

Permanently monitor the Logistics Managers’ Index (LMI):

- Transportation Capacity
- Transportation Prices
- Warehousing Capacity
- Warehousing Utilization
- Warehousing Prices

LMI is monthly, not weekly. Carry the latest reading until a new monthly release is published.

Always explain the diffusion-index rule:
- above 50 = expansion
- below 50 = contraction

Transportation Capacity is a **broad transportation-capacity indicator**, not a drayage-specific index. Use it alongside diesel and current port/terminal conditions to discuss carrier flexibility, spot availability, quote stability, and broad drayage/trucking pressure.

## Flatbed rules

Whenever possible include actual data, not generic “flatbed is tight” language:

- weekly rate movement
- YoY comparison
- load-volume or load-to-truck/capacity signal
- whether the market is tightening, stabilizing, or correcting

Translate the result for project cargo, construction, energy, infrastructure, data centers, industrial equipment, oversized/overweight, and specialized equipment where relevant.

## Rail rules

Rail is client-relevant when there is a material service change, such as:

- new or expanded service
- service suspension
- ramp opening/closure/restriction
- material backlog/dwell
- route change
- labor/weather disruption
- change affecting cargo availability, transit time, pickup, or delivery

Do **not** include rail fuel surcharges or internal rail pricing mechanics in the client report. Allog arranges rail through the steamship line; those cost mechanics are not useful to the client.

If rail dwell is cited, explain what the metric means, whether it is elevated relative to a comparable baseline, why it changed if known, and how it may affect cargo availability or final delivery timing.

## Warehousing rules

Use fresh capacity/demand/pricing evidence. Explain what the index means, not just the number.

Client impact may include:
- reduced receiving flexibility
- need to reserve space earlier
- firmer short-term storage pricing
- tighter transload windows

Do not turn the client report into an internal warehouse-operation checklist.

## Ports and drayage rules

Use geographically specific information. Prefer direct port/terminal advisories and current operational dashboards.

Useful developments include:
- terminal congestion or improving fluidity
- gate/appointment changes
- terminal consolidation or assignment changes
- rail-connected backlog
- road/access changes that materially improve/worsen truck flow
- labor disruption
- weather disruption

If there is no material port/terminal development, keep the section short.

## Compliance rules

Recurring themes (ELD removals, English Language Proficiency, non-domiciled CDL, MC-number trafficking, broker liability, FMCSA modernization, CDL-school enforcement) should appear only when there is a fresh development or current operational effect.

Always distinguish:
- **current enforceable rule / active deadline**
- **proposed rule / consultation / advocacy proposal**

Client-facing framing: compliance is increasingly a **capacity and service-availability issue**, not merely paperwork.

## Image rules

The official visual is locked. Read `docs/IMAGE_STANDARD.md` before generating the weekly image.

Do not redesign the dashboard. Do not add tables, energy bands, slogans, flags, or alternate layouts. The top logistics photo strip must look photorealistic and natural, not painterly, textured, pixelated, or obviously AI-generated.

## Weekly archive

After an edition is approved, store the final public/client-facing text and key data in the archive using the convention in `archive/README.md`.
