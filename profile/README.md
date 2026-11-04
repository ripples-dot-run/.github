<img src="./banner.png" alt="Ripples" width="100%">

## Launch a token, a collection, or both together

Ripples is a launchpad on Solana and Robinhood Chain. A launch creates a fixed-supply token with a
market built into it, and it can carry an NFT collection tied to that market.

The link is the point. Every piece minted before the market reaches its target pays 10%, 20% or 40%
of its price into that market, and the people who minted share 2%, 5% or 10% of the token supply,
released after a cliff. Collectors fund the market they end up holding. When a market reaches its
target its liquidity locks: on Solana in a new Meteora pool, and on Robinhood Chain in the Uniswap v4
pool it already trades in.

On Robinhood Chain, a market launched since 2 November 2026 also adds part of every trade fee to
liquidity locked in its own pool.

Every transaction on ripples.run is one you approve in your own wallet, and no launch requires
writing or publishing code.

**[ripples.run](https://ripples.run)** · [How it works](https://ripples.run/about) ·
[Developer reference](https://ripples.run/docs) · [Genesis](https://ripples.run/genesis) ·
[日本語](https://ripples.run/ja) · [简体中文](https://ripples.run/zh)

### On chain

Tokens created on Robinhood Chain carry their own image, description and links in the contract, so
a market is legible to a terminal from its first trade rather than after a filing.

| | |
| --- | --- |
| Token launch factory | [`0x8C43801Fe498B9C400F1D376198727Ecf8AfCAC6`](https://robinhoodchain.blockscout.com/address/0x8C43801Fe498B9C400F1D376198727Ecf8AfCAC6) |
| Hook | [`0xBA7401628167fbcd8f9db9F6ad2dDA72aB41EAcc`](https://robinhoodchain.blockscout.com/address/0xBA7401628167fbcd8f9db9F6ad2dDA72aB41EAcc) |
| Solana program | `RippcKjgg9pkjHY7RKp6R1K8jPGwq2BRSJcgbErufjF` |

Robinhood Chain is 4663. [contracts](https://github.com/ripples-dot-run/contracts) has the source and
the deployed addresses on Robinhood Chain, Base, Ethereum and Arc. Verify deployed bytecode against
the verified sources before trusting an address; the addresses a launch depends on are also
published at [ripples.run/docs#proof](https://ripples.run/docs#proof).

### $RIPPLES

Part of the platform's share of trade fees on Robinhood Chain buys $RIPPLES on the open market and
adds it, with WETH, to a full-range position owned by the dead address, so it can never be
withdrawn. Nothing is minted to fund it, and each buy is bounded on chain.

| | |
| --- | --- |
| $RIPPLES | [`0xC465130Ac047cc363D3839b4DE1C8F35Cf8aE9fd`](https://robinhoodchain.blockscout.com/address/0xC465130Ac047cc363D3839b4DE1C8F35Cf8aE9fd) |
| Buyback | [`0x4B2B547688a7D39512937aD9583315619c3Ce711`](https://robinhoodchain.blockscout.com/address/0x4B2B547688a7D39512937aD9583315619c3Ce711) |

### Contact

Security reports go to [security@ripples.run](mailto:security@ripples.run), privately, before
anywhere public. Everything else: [hello@ripples.run](mailto:hello@ripples.run) or
[@ripplesdotrun](https://x.com/ripplesdotrun).
