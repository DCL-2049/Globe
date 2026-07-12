# The World Comes to Xi

An interactive globe visualization of Xi Jinping's in-person diplomacy,
January 2020 – July 2026:

- **275 inbound visits** — every foreign head of state or government who met
  Xi Jinping in person in mainland China (state visits, the 2022 Winter
  Olympics, Belt & Road Forum 2023, FOCAC 2024, SCO Tianjin 2025, and more).
- **26 outbound trips** — every international trip Xi made in the same window.

Open **`index.html`** in any browser — it is a single self-contained file with
no dependencies, no build step, and no network access required.

## Features

- Orthographic globe (drag to rotate, scroll to zoom) with animated
  great-circle arcs: blue = leader → China, orange = Xi → abroad.
- Timeline scrubber with play button and a monthly event-density strip that
  marks the COVID border-closure period (Mar 2020 – Dec 2022).
- Direction filters, cumulative trails toggle, hover tooltips.
- Table view listing all 301 events; every row links to its source
  (Chinese MFA readouts, Xinhua, embassy releases, or major wire coverage).

## Data notes

The dataset was compiled and cross-audited from public sources in July 2026.
Rows where the classification or the Xi meeting is uncertain (e.g. prime
ministers under executive presidencies, summit attendees without a confirmed
bilateral, party chiefs who are not formal heads of state) carry a visible
flag in the table view. Known limitation: leaders who visited China but met
only the premier (Li Keqiang / Li Qiang) are excluded by design.
