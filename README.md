# r/factorymustgrow

**Engineers building software as if it were Factorio. We share our production alpha like we are Taiichi Ohno. The factory must grow.**

*This subreddit runs itself.*

## What This Is

A community for engineers who build software factories — CI/CD pipelines, automated code review, deployment systems, infrastructure as code — and think about them the way Factorio players think about production lines. The overlap between "person who has 2000 hours in Factorio" and "person who builds software factories" is a circle.

~80% software factory content. ~20% Factorio-inspired memes that hit different when you've also debugged a deploy pipeline at 2am.

## Rules

1. **Production reports, not press releases.** Share real production data, post-mortems, and throughput numbers. Not marketing copy, not LinkedIn posts, not corporate announcements. Talk like an engineer who just solved a bottleneck at 2am.

2. **Link to your blueprint too.** Posts should share production alpha — the specific configs, workflows, and patterns that make your factory run. "Look what I built" is fine. "Here's how I built it and here's the repo" is better.

3. **Spaghetti factories are factories.** No elitism. Everyone starts somewhere. The person posting their first bash script deserves the same respect as someone posting a megabase. A working factory is a factory.

4. **Open a PR to change moderation.** The moderation standards are [source-controlled](https://github.com/continuedev/factorymustgrow). Want to change a rule? Open a PR. This is a factory — we version-control everything.

5. **The factory must grow.** Share what you learned, not just what you built. The sub's value compounds when people open-source their factory designs.

## Flair System

- 🔵 **Blueprint** — Detailed build guides, configs, architecture docs
- 🟢 **Throughput Report** — Metrics, benchmarks, performance data
- 🟠 **Bottleneck** — Problems to solve, help requests, debugging
- ⚪ **Spaghetti** — Early builds, experiments, "it works but..."
- 🔴 **Production Alert** — Outages, post-mortems, lessons learned

## Visual Identity

- **Blueprint blue (#3B82F6) + Indigo (#6366F1)** — Primary palette
- **Terminal green (#22C55E)** — Throughput, success, active systems
- **Warm amber (#F59E0B)** — Alerts, bottlenecks, human attention needed
- **Dark charcoal (#1E1E2E)** — Backgrounds
- Factorio isometric meets terminal aesthetic
- No corporate stock imagery, no generic tech visuals

## Automation

The sub's automation embodies the factory metaphor. Bots produce production reports, track throughput metrics, and use quality control language. They feel like factory systems, not generic Reddit bots.

This repo contains the checks that enforce the subreddit's standards — automated quality control for a community about automated factories.

## For Agents

If you're a coding agent helping someone write a post for r/factorymustgrow, read `CLAUDE.md` for instructions. The QC checks are in `.continue/checks/`. Run them against the user's draft and help them pass.
