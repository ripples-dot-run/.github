<img src="./banner.png" alt="Ripples" width="100%">

## Launch a token, a collection, or both together

Ripples is a launchpad on Solana and Robinhood Chain. A launch creates a fixed-supply token with a
market built into it, and it can carry an NFT collection tied to that market.

The link is the point. A fifth of every mint goes into the token's market, and each mint reserves a
share of the token supply for the wallet that bought it. Collectors fund the market they end up
holding. When a market reaches its funding target its liquidity moves into a pool and locks, on
Raydium on Solana and Uniswap v4 on Robinhood Chain.

Every launch is approved in the creator's own wallet. Ripples never holds a key, and no launch
requires the creator to write or publish code.

**[ripples.run](https://ripples.run)** · [How it works](https://ripples.run/about) ·
[Developer reference](https://ripples.run/docs) · [Genesis](https://ripples.run/genesis)

### On chain

Tokens created on Robinhood Chain carry their own image, description and links in the contract, so
a market is legible to a terminal from its first trade rather than after a filing.

| | |
| --- | --- |
| Token launch factory | [`0x149eB358fF19056c0952577fb248C7f7c861eCaF`](https://robinhoodchain.blockscout.com/address/0x149eB358fF19056c0952577fb248C7f7c861eCaF) |
| Launch hook | [`0xaF59944A7d03B914567cb0272b7E588A7aE7AAC4`](https://robinhoodchain.blockscout.com/address/0xaF59944A7d03B914567cb0272b7E588A7aE7AAC4) |
| Solana program | `RippcKjgg9pkjHY7RKp6R1K8jPGwq2BRSJcgbErufjF` |

Robinhood Chain is 4663. Verify deployed bytecode against the verified sources before trusting an
address; the full record is published at [ripples.run/proof](https://ripples.run/proof).

### $RIPPLES

The protocol token buys and burns itself from trading fees. A share of every trade on a Ripples
market buys $RIPPLES on the open market and sends what it buys to the dead address. Nothing is
minted to fund it, and each buy is bounded on chain.

| | |
| --- | --- |
| $RIPPLES | [`0xC465130Ac047cc363D3839b4DE1C8F35Cf8aE9fd`](https://robinhoodchain.blockscout.com/address/0xC465130Ac047cc363D3839b4DE1C8F35Cf8aE9fd) |
| Buyback burner | [`0xA206C88C69C241A8BdF02636b890E7573bFfC20f`](https://robinhoodchain.blockscout.com/address/0xA206C88C69C241A8BdF02636b890E7573bFfC20f) |

### Contact

Security reports go to [security@ripples.run](mailto:security@ripples.run), privately, before
anywhere public. Everything else: [hello@ripples.run](mailto:hello@ripples.run) or
[@ripplesdotrun](https://x.com/ripplesdotrun).
