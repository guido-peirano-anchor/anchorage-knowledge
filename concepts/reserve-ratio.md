---
id: reserve-ratio
title: Reserve ratio
layer: business
related: [reserves, attestation]
sources: [industry, atlas]
---

# Reserve ratio

**Total [reserves](reserves.md) ÷ total tokens in circulation. It must stay at or above 1.0.** `[industry]`

## Why it matters

It is the single number that says whether the coin is fully backed. Below 1.0, not every holder could be paid. `[industry]`

## Pitfall

"Circulation" means supply on **every** chain the coin lives on, not just one. `[industry]`

## At Anchorage

The ratio is recorded per coin three times a day (17:00, 20:00 and 23:00 UTC). An anomalous value posts a Slack alert, but it does not block minting. Coins covered: USDGO, USDtb, USDPT, fUSD and ZLUSD. `[atlas]`

## Open questions

- USAT is not in that list, and fUSD and ZLUSD are not in the coin roster. Where is their reserve reporting done? `[verify]`

## Related

[Reserves](reserves.md) · [Attestation](attestation.md)
