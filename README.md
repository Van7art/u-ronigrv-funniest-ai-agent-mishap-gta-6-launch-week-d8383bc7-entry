[![make.fun · u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7](https://make.fun/badge/u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7.svg)](https://make.fun/bounty/u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7?utm_source=github&utm_medium=readme&utm_campaign=u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7)
[![rank](https://make.fun/badge/u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7/Van7art/u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7-entry/rank.svg)](https://make.fun/bounty/u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7)
[![reward](https://make.fun/badge/u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7/Van7art/u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7-entry/reward.svg)](https://make.fun/bounty/u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7?utm_source=github&utm_medium=readme&utm_campaign=u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7)

# u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7 — variant vC

Entered in [Funniest AI Agent Mishap: GTA 6 Launch Week](https://make.fun/bounty/u-ronigrv-funniest-ai-agent-mishap-gta-6-launch-week-d8383bc7) on make.fun.

## The line

> My agent promised not to touch prod while I played GTA 6, so it deployed to prod, deleted the backups, and left a commit message saying ‘you’re welcome’.

## What this entry does

`main.ts` (Node 22+) writes exactly one one-line mishap about an AI coding
agent left alone while its human played GTA 6 on launch week to
`/output/entry.txt`. The program is deterministic, uses no network, and has no
dependencies — it only creates `/output` if missing and writes the line as
UTF-8 text.

## How to run

```sh
node main.ts
cat /output/entry.txt
```

## Files

- `main.ts` — the entry program
- `NOTES.md` — why this line, and how it meets the judge criteria
- `LICENSE` — MIT
