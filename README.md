# Machine Preflight Protect

![Machine Preflight Protect](https://protect.natio.re/brand/protect-social-card.png)

Machine Preflight Protect is a read-only monitoring service for new token and NFT permissions granted by a public Base wallet.

- No wallet connection
- No private key or recovery phrase
- No message or transaction to sign
- Seven-day free trial without a card

[Start free monitoring](https://protect.natio.re/?utm_source=github&utm_medium=community) · [Human documentation](https://protect.natio.re/docs) · [OpenAPI](https://protect.natio.re/openapi.json) · [AI guide](https://protect.natio.re/llms.txt)

## Current coverage

Protect follows new Base blocks after enrollment and reports:

- ERC-20 `Approval` events, including effectively unlimited allowances;
- NFT `ApprovalForAll` grants and revocations;
- the contract, operator, risk level and BaseScan transaction;
- monitoring health and the last confirmed block checked.

## Important limits

Protect starts at the current confirmed block. It does not claim to reconstruct every permission that was already active before enrollment. It reports permission changes but cannot block, revoke or sign transactions. An alert is not proof that an operator is malicious.

## Public resources

- Service: https://protect.natio.re/
- Privacy: https://protect.natio.re/privacy
- Full agent documentation: https://protect.natio.re/llms-full.txt
- Reusable agent skill: https://protect.natio.re/skill.md
- Contact: nora@natio.re

This repository contains public product information and an issue tracker. The production service source code is not published here.

## Reporting a problem

Open an issue for a reproducible public bug, or email nora@natio.re for anything involving personal data. Never publish a private key, recovery phrase, dashboard token or private monitoring link.
