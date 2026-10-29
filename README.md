# INDmoney Transfer Tracker — Product Concept

A clickable product prototype exploring how INDmoney could make delayed US stock transfers easier to understand and easier to resolve.

> **Disclaimer:** This is an independent product concept, not an official INDmoney feature. It uses illustrative sample data and does not connect to INDmoney, banks, payment systems, or live support.

## The Problem

When a deposit or withdrawal is delayed, users may be left wondering:
- Where is my money in the transfer process?
- Has the expected arrival time changed?
- What should I do if the transfer is still delayed?

The concept focuses on reducing uncertainty with clearer status information and a direct support path.

## Proposed Solution

The prototype explores four key screens:

1. **US Stocks Dashboard** — a prominent alert for a delayed deposit.
2. **Transaction History** — a focused way to find and select a transfer.
3. **Transfer Tracker** — status, estimated arrival time, latest update, and a progress timeline.
4. **Support Request** — a prefilled request flow for users who need help.

It also explores alternate states such as dismissed alerts, empty transaction history, and unavailable status information.

## Product Decisions

- Show the delay alert prominently on the dashboard.
- Display the current status and revised ETA, with a plain-language explanation where available.
- If status data is unavailable, show the last known status and timestamp and allow a retry.
- Provide a support path without implying that the transfer itself can be sped up.
- Keep bank integrations, automatic compensation, and a full chatbot out of scope.

## Success Metric

**Hypothesis:** Reduce support requests per delayed transfer by **20% within eight weeks** of launch.

This is a proposed target, not a measured result. A real launch would require a baseline and reliable event tracking.

## Prototype Features

- Before / After experience toggle
- Clickable screen-to-screen navigation
- Toggleable annotations
- Sample transfer data and simulated status updates
- Empty and unavailable-status states
- Editable, prefilled support request
- Local demo submission confirmation
- Closing panel explaining the metric and trade-off

## How to Run

1. Download or clone this repository.
2. Open the self-contained HTML prototype in a modern browser.
3. Use the **Before / After** toggle to compare the baseline concept with the proposed experience.
4. Follow the dashboard alert or transaction history to explore the tracker.
5. Try the unavailable-status and empty-history scenarios to inspect the alternate states.

No installation, backend, or API keys are required.

## Scope and Limitations

- All transaction statuses, ETAs, and amounts are sample data.
- Refresh behaviour is simulated locally.
- Support submission does not create a real support ticket.
- The prototype does not initiate deposits or withdrawals.
- Some transaction screens are proposed concepts because the complete existing INDmoney transfer flow could not be verified from the available screenshots.

## Product Trade-off

More detailed status information can reduce uncertainty, but stale or inaccurate updates can create false confidence. A production version should display only verified status information and clearly label estimates.

## Screenshots and Demo

Add your prototype screenshots, GIF, and case-study PDF here once they are committed to the repository. For example:

- `assets/demo.gif`
- `assets/before-after.png`
- `assets/case-study.pdf`

Then embed them with Markdown:

```md
![Transfer Tracker demo](assets/demo.gif)
```

## Built With

- HTML
- CSS
- JavaScript

## Author's Note

This project demonstrates product discovery, problem framing, user-flow design, prototype interaction design, edge-case thinking, and success-metric definition. It is a portfolio concept intended to invite discussion and feedback.
