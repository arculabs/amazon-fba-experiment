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


## First-experiment inventory condition

For the initial one-SKU FBA experiment, source straightforward **new / normal retail-condition inventory**.

EE listings explicitly marked **Not Mint** are outside the current experiment because packaging condition is not guaranteed. They may be researched later as a separate condition-sensitive liquidation strategy, but they should not be mixed into the first distributor-to-FBA validation loop.


## EE sourcing discovery priority

Research through 2026-09-29 established that broad scanning of ordinary EE inventory is low-yield for the first Amazon FBA experiment because displayed dealer cost is commonly too close to live retail.

Prioritize sourcing discovery in this order:

1. **Current EE Distribution wholesale sales / sales-rep specials** for in-stock, Amazon-permitted, single-SKU inventory.
2. **Reverse sourcing** from exact Amazon products with a durable live-market premium while EE still has inventory.
3. Ordinary catalog scanning only when there is a specific reason to expect unusual margin.

Do not treat EE/Entertainment Earth **Drop Zone** as a closeout feed; it is an upcoming-product-launch surface.


## Market-first sourcing decision

After fourteen reverse-sourcing batches plus a complete visible September EE sale screen, pause broad supplier-first product hunting.

The next sourcing work is **market first, supplier second**: identify viable Amazon markets/products first, then establish a direct brand relationship or brand-confirmed authorized wholesale source.

Current preference order:

1. brand-direct authorized wholesale;
2. brand-confirmed specialized distributor;
3. opportunistic EE/supplier specials only when the ASIN is already market-qualified;
4. OA/RA only as a tactical learning/discovery path, not the core operating model;
5. private label only as a separately approved future business case.

The ~$5/unit screen remains a minimum floor for the first experiment. Also record inventory-turn expectation and expected 30-day dollar contribution so low absolute returns are visible.
