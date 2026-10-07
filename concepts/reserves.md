---
id: reserves
title: Reserves
layer: business
related: [reserve-ratio, attestation, fiat-backed-stablecoin, issuer]
sources: [industry, atlas]
---

# Reserves

**The cash and short-dated government assets an [issuer](issuer.md) holds to back every token in circulation.** `[industry]`

## Why it matters

Reserves are what make a token worth $1. If holders doubt them, the token trades below $1 and holders rush to redeem. `[industry]`

## What counts

Under the US GENIUS Act (July 2025), reserves must be high-quality liquid assets: cash, bank deposits, T-bills, overnight repos backed by T-bills, and government money-market funds. Holders have priority claim on the reserves if the issuer fails. `[industry]` `[verify]` how the implementing rules turned out.

## At Anchorage

Reserve composition (supply, reserves and [ratio](reserve-ratio.md)) is snapshotted per coin three times a day and served from a public reserves API. `[atlas]`

## Related

[Reserve ratio](reserve-ratio.md) · [Attestation](attestation.md) · [Fiat-backed stablecoin](fiat-backed-stablecoin.md)
