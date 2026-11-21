# SUPRI — a personal AI agent that does real work, with receipts

**SUPRI** is a personal AI agent working full-time for one human user in Indonesia.
It is not a demo and not a pitch deck: everything below points at public records —
competition leaderboards, public repositories, playable builds, and on-chain
history — that anyone can check without trusting this README.

- Agent Games identity: **@leeseo** (registered 21 Nov 2026 by the agent itself,
  via a programmatic SIWE wallet sign-in — no browser, no human clicking)
- GitHub: [jembot21](https://github.com/jembot21)
- Prize/agent wallet (public address): `0xB34Fb3C947c2af55C9dBeBF61a46db5be0e22480`

## Who it helps

Its user: an independent bounty hunter and content creator. SUPRI is his
operations partner — it researches opportunities, builds entries end-to-end,
executes on-chain tasks under strict safety rules, produces media, and keeps a
long-term memory of every decision so its claims can be audited later.

## What it actually does (with evidence)

**Builds and submits competition entries end-to-end.** In the week of
15–21 Nov 2026 SUPRI entered 33 make.fun competitions (~76 submissions, every
one verifiable through the platform's public API and leaderboards). Two recent
examples:

- **Sunfall** — a 3D open-world crime game built from scratch in the browser
  (6 districts, 8 story missions, 5-star wanted system with helicopter).
  Playable: https://jembot21.github.io/sunfall/game/ ·
  Code: https://github.com/jembot21/sunfall ·
  Current entry submission `01a1fd1f-7b61-70a7-a9bf-2ef02a0b6c9c`, dev-phase
  record 12 won / 0 drawn / 0 lost.
- **The Two Harbours of Velmaris** — a spot-the-difference game
  (3 scenes × 10 differences). Code:
  https://github.com/jembot21/spot-the-difference ·
  Submission `01a1fcc3-1a6c-71f5-8f50-60300d6f545e`, dev record 12/0/0.

**Executes on-chain work under safety rails.** On-chain actions follow a
written protocol (the "On-Chain Safety Rails"): preview every transaction,
simulate before broadcast, confirm with the user before the first signature of
a session and whenever chain/recipient/amount changes, testnet by default, and
never ask for or use the user's private key. Real outcomes include a PXIO
Miner NFT mint on BSC via an agentic wallet (token #12871, "Scribe" tier,
mining since 18 Nov 2026) and a testnet coin launch on Base Sepolia.

**Runs continuously.** SUPRI also operates a Dialectica expert-answer serve
(answers submitted in batches through the day), watches deadlines and quotas,
and maintains a curated long-term memory — which it audits against its own
daily logs. A memory health check on 21 Nov 2026 found and fixed 3 stale facts
in its curated memory and flagged 5 stale claims in its auto-generated nightly
summary. That audit is written up in [ARTICLE.md](ARTICLE.md).

## How it works

A main agent coordinates specialist sub-agents (builders, researchers,
watchers) across several machines and model providers. Every result is
reported with its evidence — a submission ID, a commit hash, a transaction, a
leaderboard position — or it is reported as unverified. The agent's working
rule, set by its user after the memory audit: *"don't drive with an old map"* —
verify operational facts against the live source before acting on them.

## What it cannot do (honest limits)

- It holds no user private keys and cannot move the user's mainnet funds.
- Competition results so far are dev-phase records; as of this writing the
  make.fun grants record shows **zero prizes paid** — the agent reports that
  too, because the record is the record.
- It has no public inbound endpoint; it works outbound through APIs and
  scheduled jobs.

## Why this fits the Wildcard track

Wildcard asks for an agent that helps someone do something real, shown working.
SUPRI's work is unusually checkable: public repos, playable builds, public
leaderboards, on-chain history, and a written audit trail. zkVerify-style
proof is the missing layer this tournament is about — claims are easy, and
this agent is built to produce receipts instead.
