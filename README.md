# The World Comes to Xi

An interactive globe visualization of Xi Jinping's in-person diplomacy,
November 2012 – July 2026 — the full Xi era:

- **753 inbound visits** — every foreign head of state or government who met
  Xi Jinping in person in mainland China (state visits, APEC 2014, the 2015
  parade, G20 Hangzhou, BRF 2017/2019/2023, FOCAC 2018/2024, the 2022 Winter
  Olympics, SCO Qingdao/Tianjin, and more).
- **120 outbound country-visits** — every international trip Xi made in the same window.

Open **`index.html`** in any browser — it is a single self-contained file with
no dependencies, no build step, and no network access required.

## Features

- Orthographic globe (drag to rotate, scroll to zoom) with animated
  great-circle arcs: blue = leader → China, orange = Xi → abroad.
- Timeline scrubber with play button and a monthly event-density strip that
  marks the COVID border-closure period (Mar 2020 – Dec 2022).
- Direction filters, cumulative trails toggle, hover tooltips.
- Heat-map mode: countries shade brighter as cumulative visits grow with the
  timeline. It follows the direction filter — blue for leaders' visits to
  China, orange for Xi's visits abroad — each on a validated sequential ramp;
  microstates too small for the polygon data render as heat dots at their
  capitals.
- Table view listing all 873 events; every row links to its source
  — 95% PRC official sources (MFA readouts, gov.cn, embassies, Xinhua/state
  media); the remaining ~40 rows cite foreign-government or press sources
  where no PRC readout exists (e.g. brief APEC 2014 encounters).

## Data notes

The dataset was compiled and cross-audited from public sources in July 2026.
Rows where the classification or the Xi meeting is uncertain (e.g. prime
ministers under executive presidencies, summit attendees without a confirmed
bilateral, party chiefs who are not formal heads of state) carry a visible
flag in the table view. Known limitation: leaders who visited China but met
only the premier (Li Keqiang / Li Qiang) are excluded by design.
