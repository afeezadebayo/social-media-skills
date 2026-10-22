# Social Media — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **social media** skills for **Claude, Claude Code, OpenAI Codex** and any agent that reads the
[Agent Skills](https://agentskills.io/specification) format. Organic strategy across LinkedIn, Instagram, TikTok,
X and YouTube, video scripts, content calendars, community management, listening, creator and employee advocacy,
and reporting. Each skill is a single `SKILL.md`: a senior practitioner's workflow — when to use it, the inputs to
ask for, a numbered process, decision rules, an output template and sources — loaded only when a task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/social-media/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/social-media-skills.git
cp -r social-media-skills/social-media-audit ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r social-media-skills/social-media-audit ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/social-media/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`social-media-audit`](social-media-audit/SKILL.md) | Audit an organic social presence end to end, with focus, maintain or exit decisions. The entry point. |
| [`social-media-strategy`](social-media-strategy/SKILL.md) | Build an organic social strategy: role, audiences, platform choices, pillars, voices, governance. |
| [`social-content-calendar`](social-content-calendar/SKILL.md) | Build content calendars and production workflows: rhythm, series, batching, approvals. |
| [`linkedin-organic`](linkedin-organic/SKILL.md) | Grow on LinkedIn through people and pages: posts, carousels, hooks, daily engagement. |
| [`instagram-organic`](instagram-organic/SKILL.md) | Grow on Instagram: Reels, carousels, Stories, search, sends and saves. |
| [`tiktok-organic`](tiktok-organic/SKILL.md) | Grow on TikTok: the For You feed, hooks, series, keyword-rich captions, watch time. |
| [`x-twitter-organic`](x-twitter-organic/SKILL.md) | Grow on X: profile, threads, replies, conversation maps, Spaces and Communities. |
| [`youtube-seo-growth`](youtube-seo-growth/SKILL.md) | Grow a YouTube channel: topic research, titles and thumbnails, retention, Shorts. |
| [`short-video-scripts`](short-video-scripts/SKILL.md) | Write scripts for 15–90 second vertical videos across platforms, with hook banks. |
| [`community-building`](community-building/SKILL.md) | Build and run brand communities: purpose, response standards, moderation, feedback loops. |
| [`social-listening`](social-listening/SKILL.md) | Set up social listening that leads to action: queries, alerts, crisis signals, routing. |
| [`creator-employee-advocacy`](creator-employee-advocacy/SKILL.md) | Run creator partnerships and employee advocacy with disclosure and measurement. |
| [`social-media-reporting`](social-media-reporting/SKILL.md) | Report organic social by goal, with consistent definitions and decisions, not vanity metrics. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: social media skills, SKILL.md, Agent Skills, Claude skills, Claude Code skills, Codex skills, AI
agent skills, LinkedIn organic, Instagram Reels, TikTok growth, X Twitter, YouTube SEO, short video scripts,
community management, social listening, creator marketing, employee advocacy, social media reporting.</sub>
