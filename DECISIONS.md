# Durable Decisions

## Scope

This repository covers the broader Amazon FBA experiment, not only EE Distribution. Supplier-specific terms and product research live under `suppliers/<supplier>/`.

## Product statuses

Use these statuses consistently:

- **UNRESOLVED** — encountered but not sufficiently researched or evidence was lost.
- **REJECTED** — a confirmed hard gate or economics failure makes the item unsuitable for the current experiment.
- **WATCH** — not currently actionable, but worth revisiting if a specific condition changes.
- **CANDIDATE** — passes the current screen and deserves final dealer-price / order-level validation.
- **SELECTED** — chosen for the current purchasing experiment.

## Current first-order risk posture

- Keep the first inventory position around $250–$500 total exposure.
- Prefer the smallest practical MOQ/order quantity.
- The purpose of the first order is to validate the sourcing-to-FBA loop with controlled downside.
- Approximately $5+ realistic profit per unit is the current working profitability screen, not a guarantee.
- A marketplace restriction is a hard reject.
- An uncertain exact ASIN/product match cannot advance to candidate status.

## Research durability rule

Do not conduct another large uncheckpointed shortlist sweep.

Research should be performed in small batches, with outcomes written to the relevant supplier product ledger before expanding the batch. This is specifically to prevent chat/session expiration from erasing completed work.

## EE first-order discount

For the first EE Distribution order, use sales rep Uriel Gonzalez so the confirmed first-order discount is 7% rather than the standard 5%.

See `suppliers/ee-distribution/README.md` for the supplier-specific terms.
