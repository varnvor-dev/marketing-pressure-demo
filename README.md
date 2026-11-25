# Marketing Pressure — Campaign Orchestrator (demo)

An interactive demo of a marketing pressure and campaign orchestration tool built for
Salesforce Marketing Cloud Engagement, styled with the Salesforce Lightning Design System.

**[Open the demo →](https://varnvor-dev.github.io/marketing-pressure-demo/)**

## What this is

A single self-contained HTML file. It runs entirely in the browser on bundled sample
data and makes **no network requests of any kind** — no backend, no API keys, no tracking.
Every figure on screen is computed from that sample data.

## What it does

- **Campaign lifecycle** — Draft → Approved → Active → Completed, with the transition
  rules enforced and approved campaigns locked against edits.
- **Send limits (marketing pressure)** — frequency caps by channel and campaign type,
  most-restrictive-wins, with each campaign showing the limits it inherits.
- **Copilot** — describe a campaign in a sentence and get a reviewable draft; limits and
  audience filters are suggested, never applied automatically.
- **Calendar** — a per-day pressure heatmap and overlapping-audience warnings.
- **Insights** — send volume against limits, contacts protected from over-messaging, and
  control-group splits.

## Honest about its limits

The demo has no engagement data — no opens, clicks or revenue — so it never shows them.
Where a number cannot be computed from the data, the interface says so rather than
displaying a zero that looks like a measurement.

In production the UI talks to a CloudPages Code Resource; nothing here is connected to
any Marketing Cloud tenant.
