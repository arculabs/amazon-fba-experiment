# EE Distribution

## Status

ARCU Labs has an approved EE Distribution dealer account and is using EE as the first distributor for the Amazon FBA experiment.

## Confirmed sales-rep terms

Sales representative: **Uriel Gonzalez**

Confirmed by phone on 2026-09-29:

- EE charges **$0.50 per item** for labeling and packaging.
- The $0.50 per-item charge is **non-refundable even if an order is canceled**.
- The first order receives a **7% discount when placed through Uriel Gonzalez**.
- If the first order is not placed through him, the first-order discount is **5%**.
- The **5% / 7% first-order discount does not stack with EE sale pricing**; sale items use the displayed sale price instead.
- No other special terms were identified in that conversation.

For first-order screening through Uriel, the working supplier-side unit-cost formula is:

```
effective EE unit cost = dealer price × 0.93 + $0.50
```

This formula does **not** include Amazon referral/FBA fees, inbound transportation, or other order-specific costs.

For EE sale items, use:

```
effective EE unit cost = displayed sale price + $0.50
```

Do not apply the first-order 5% / 7% discount again to a sale SKU.

## Product research

See [products.md](./products.md).

## Current workflow

Screen in this order:

`orderable/in stock → Amazon resale allowed → exact Amazon match → demand/competition → Amazon fees/economics → actual EE dealer price`

Dealer pricing is account-gated and must be supplied or checked from the logged-in EE account when needed.


## Sourcing strategy after reverse-sourcing research

After fourteen small product-research batches, ordinary displayed EE dealer pricing has repeatedly been too close to prevailing Amazon/retail pricing for the current ~$5/unit FBA target.

EE Distribution's own ordering guidance states that:
- tiered pricing can improve with quantity;
- various wholesale sales run throughout the year; and
- clients should contact their Sales Representative for better/current pricing opportunities.

The site's **Drop Zone** is for upcoming product launches, not a liquidation/closeout channel.

For the current experiment, the preferred EE sourcing sequence is now:

1. ask Uriel Gonzalez for current wholesale sales/specials or unusually discounted in-stock inventory that is permitted on Amazon;
2. favor one individually packaged SKU with a small practical case quantity;
3. capture exact SKU/UPC/model;
4. match the exact Amazon ASIN;
5. validate live Amazon price plus multiple recent sold-market signals where available;
6. calculate the maximum viable EE price;
7. compare the special/dealer price and only advance if the economics clear the threshold.

Ordinary catalog reverse sourcing remains useful as a secondary path for catching products near the transition from normal availability to scarcity.
