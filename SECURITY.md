# Security policy

## Reporting

Report a suspected vulnerability privately to **security@ripples.run** before disclosing it
anywhere public, including an issue on this organization.

Useful reports name the contract or endpoint, the conditions that reach it, and what an attacker
gains. A transaction hash or a failing test says more than a description. You will get an
acknowledgement within two working days and an assessment within five.

Please do not test against mainnet in a way that risks other people's funds. Robinhood Chain
testnet is 46630 and Solana devnet is open; both run the same code.

## Scope

In scope: the launch contracts and the Solana program named on the organization profile, the
ripples.run application, and the API at api.ripples.run.

Out of scope: findings that require a compromised wallet or a compromised operator machine, rate
limits on public endpoints, and the market behaviour of any launch created by a third party.

## What Ripples does not hold

Every launch, trade, mint and settings change is approved in the user's own wallet. Ripples holds
no user key and takes no custody of user funds at any point.
