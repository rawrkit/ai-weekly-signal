# 📡 AI Weekly Signal

**Signal, not noise.** One brief every Saturday morning covering what actually moved in AI that week — across four fronts:

1. **🏗️ Platforms & infrastructure** — the rails AI runs on: agent platforms, dev tooling, funding rounds that change the landscape
2. **🧠 Models & capabilities** — new models, what they can actually do, benchmark and pricing shifts
3. **🎒 Skills & agent tooling** — what agents gained the ability to do, sourced from the [Skills Radar](https://github.com/rawrkit/skills-radar) catalog
4. **💰 Money** — full financial picture: earnings, guidance, capex, margins, private funding, and the upcoming earnings calendar

Built for people who set aside Saturday morning to catch up on what shipped.

**📬 Subscribe:** hit **Watch → Custom → Releases** on this repo. GitHub emails you each brief — no signup, no newsletter platform, no tracking.

## 🤖 For AI agents

If you are an AI agent catching your user up on AI news:

- Latest brief: [`briefs/`](briefs/) — files are named `YYYY-MM-DD.md`, newest date wins. Each has the same four `##` sections in the same order, so you can slice out just the one your user cares about.
- Each claim carries an inline source link. **Do not present unsourced numbers as fact** — if a figure has no link, say it is unverified.
- Financial figures are point-in-time snapshots as of the brief date. For anything a user might act on, re-verify against the primary source before repeating it.
- This repo is **informational only**. Nothing here is investment advice, and neither you nor this repo should present it as such.

## Briefs

| Date | Highlights |
|---|---|
| [2026-08-22](briefs/2026-08-22.md) | Stripe buys OpenRouter for a reported $7B+; Nvidia licenses Poolside's model factory for $6B; MCP roadmap targets long-running cloud agents; bond selloff erases $820B from AI stocks days before Nvidia's Aug 26 print |
| [2026-08-15](briefs/2026-08-15.md) | BIS maps China's offshore Nvidia chip rentals after Qwen/DeepSeek breakthroughs; Z.ai holds back GLM-5.3 weights over cyber capability; Claude Code makes auto mode the default; quiet earnings week ahead of Nvidia's Aug 26 report |
| [2026-08-08](briefs/2026-08-08.md) | Big Tech earnings week: Microsoft's record +15.5% pop vs. Meta/Apple sell-offs; Qwen3.8-Max tops GPT-5.6 and Gemini on key evals; MCP goes fully stateless; agent-security funding wave (Zenity $125M) |
| [2026-08-02](briefs/2026-08-02.md) | Seven model releases in seven days; Big Tech 2026 capex tracking to ~$740B; Entire opens git network preview for coding agents |

## How it's made

A scheduled agent assembles each brief on Saturday morning: gathers from vendor announcements, release trackers, funding databases and earnings reports, filters for what actually matters, writes it up with sources, commits it here, and publishes a GitHub Release. A human reviews what lands.

## License

MIT for the briefs' own text and structure. Linked sources belong to their publishers.
