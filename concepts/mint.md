---
id: mint
title: Mint (issue)
layer: business
related: [burn, issuer, reserves, primary-market]
implemented_by: [mintburn]
sources: [industry, atlas]
---

# Mint (issue)

**Creating new tokens on chain in exchange for fiat that goes into [reserves](reserves.md).** `[industry]`

## Rule of order

**Fiat first, tokens second.** The issuer never has tokens out without dollars in. `[atlas]`

## At Anchorage

1. A customer asks to convert, for example $1M into USDtb.
2. Their fiat is put on hold while the customer's own approvers sign off.
3. The fiat moves from the customer to the issuer.
4. A mint transaction is signed with the coin's minter key, and the tokens land in the customer's wallet.
5. Anchorage re-reads the chain to confirm the supply changed. A separate watcher flags any mint that doesn't match an internal record.

`[atlas]`

## Open questions

- If the mint fails after the fiat has moved, the fiat is not automatically returned. What is the procedure? `[atlas]` `[verify]`
- The issuer's review of each conversion is currently hardcoded to "approve". Is that intended? `[atlas]`

## Related

[Burn](burn.md) · [Issuer](issuer.md) · [Primary market](primary-market.md)
