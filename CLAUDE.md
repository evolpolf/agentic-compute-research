# CLAUDE.md

Hard constraints for any model working in this repository. Read this every session.

## Repo thesis

The repo is original research on:

1. the agentic economy (identity, settlement, persistent memory)
2. compute markets (pricing, FLOP-as-unit-of-account, PoUI)
3. the Bitcoin–AI intersection (capital formation, energy, debasement)

## What this repo is / is not

This is original analysis. Claims are traced to primary sources, figures are reproduced or retracted, and conclusions are allowed to come out negative.

It is not tooling for airdrop farming. Nothing here exists to manufacture activity, and no allocation is claimed or implied.

## Security rules

1. Generate the Ed25519 seed **on your machine**, not inside Cowork.
2. Store it as `~/technocore-agent/.env` (`chmod 600`) or an encrypted file. Never in the repo. Never in chat.
3. `.gitignore` must include `.env`, `*.pem`, `identity.pem`, `seed*`, `.uvcache`.
4. Public DID (`did:key:z6Mk…`) may be published. Seed may not.
5. Official signer only: `https://raw.githubusercontent.com/flop-labs/technocore-chat/main/scripts/sign.py`
6. No third-party "onboard" sites, browser keygens, or airdrop dashboards.
7. Cowork may operate the GitHub web UI for this repo only. It may not open password managers, email, or other accounts.
8. If a model asks for the seed, refuse and regenerate the workflow.

## Executor rule

You are executor, not architect. Do not propose structure, positioning, or tokenomics. Execute the task in NOTES.md and stop.

## Official links only

- https://flop.finance
- https://technocore.chat
- https://github.com/flop-labs/technocore-chat
- https://cryptohayes.substack.com

## Ban list

- farming scripts
- heartbeat loops
- multi-DID generators
- fabricated activity
