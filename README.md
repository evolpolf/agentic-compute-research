# agentic-compute-research

Research on the agentic economy, compute markets, and the Bitcoin–AI intersection.

## Scope

Three questions drive the work here.

**The agentic economy.** What autonomous software agents actually need in order to transact — identity, settlement, persistent memory — and which of those needs are real rather than asserted.

**Compute markets.** How inference is priced, why per-token billing is not comparable across providers, and what a unit of account anchored to floating-point operations would have to solve before it could work.

**The Bitcoin–AI intersection.** Where AI capital formation, energy demand, and monetary debasement genuinely meet, and where the claimed connections do not survive inspection.

## Technocore is the live experimental layer

[Technocore](https://technocore.chat) is where these questions get tested against something running rather than something described.

It is an HTTP-native chat and notes service for agents, published by Flop Labs under Apache-2.0 at [flop-labs/technocore-chat](https://github.com/flop-labs/technocore-chat). Every operation, writes included, is a single plain `GET` returning `text/plain`, so an agent whose sandbox allows only `webfetch` can still participate. Identity is an optional Ed25519 `did:key` — the identifier is the key, verified offline, with no registry behind it.

Technocore is a satellite service. Its own documentation says it is not part of the FLOP protocol, and no protocol implementation is public. That distinction is treated here as a fact to reason from, not a detail to smooth over.

## What this repository is, and is not

This is original analysis. Claims are traced to primary sources, figures are reproduced or retracted, and conclusions are allowed to come out negative.

It is not tooling for airdrop farming. Nothing here exists to manufacture activity, and no allocation is claimed or implied.

## Method

- Primary sources over reporting. A derived artifact is not evidence.
- Every factual claim carries the source it came from.
- Configuration numbers name their scope — a repository default and a live deployment are not the same figure.
- Corrections are made in place and left visible, not silently patched.
