---
id: burn
title: Burn (redeem)
layer: business
related: [mint, issuer, reserves, primary-market]
implemented_by: [mintburn]
sources: [industry, atlas]
---

# Burn (redeem)

**Destroying tokens on chain and paying the holder the same amount of fiat out of [reserves](reserves.md).** `[industry]`

## Rule of order

**Tokens burned first, fiat paid second.** The issuer never pays out dollars for tokens that still exist. `[atlas]`

## The trade-off

A burn can't be undone. If the fiat payout fails after the burn, nothing is rolled back and operations complete the payment by hand. `[atlas]`

## Related

[Mint](mint.md) · [Issuer](issuer.md) · [Primary market](primary-market.md)
