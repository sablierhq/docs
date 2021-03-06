---
id: basics
title: Basics
sidebar_position: 1
---

### Where can I access the Sablier protocol?

You can access Sablier through our branded web interfaces:

- [pay.sablier.finance](https://pay.sablier.finance) (streaming money)
- [app.sablier.finance](https://app.sablier.finance) (withdrawing the streamed money)
- [gnosis-safe.io](https://gnosis-safe.io)

We're working with various projects in the DeFi ecosystem to make Sablier accessible through more and more interfaces.
If you want to use Sablier on a testnet, you may have to get some [TestnetDAI](../guides/chains#testnet-tokens) first.

### What is real-time finance?

A term coined by us to emphasize the wide-ranging use cases for the Sablier protocol. We like to think about work as an attempt to rethink the way trust is established in financial contracts.

### What is money streaming?

An alternative wording, [coined](https://www.youtube.com/watch?v=gF_ZQ_eijPs) by Andreas Antonopoulos in 2017. Just like you can stream movies on Netflix or music on Spotify, so you can stream money by the second on Sablier.

### How does streaming work on Sablier?

Imagine a salary worth 3,000 DAI paid by Alice to Bob over the whole month of January.

1. Alice makes the 3,000 DAI deposit in the Sablier contract _before_ Jan 1, setting the stop time to Feb 1.
2. Every second beginning Jan 1 makes Bob richer.
3. On Jan 10, Bob will have earned approximately 1,000 DAI.
4. If at any point during January Alice wishes to recover her money, she can cancel the stream and recover what
   has not been streamed yet.
