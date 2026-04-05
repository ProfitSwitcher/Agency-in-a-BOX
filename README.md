<div align="center">

# AI Agency in a Box

### Your full-service AI agency. 7 teams. 100+ agents. Zero setup.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Agents](https://img.shields.io/badge/Agents-100%2B-brightgreen)](#-the-7-teams)
[![Workflows](https://img.shields.io/badge/Workflows-9-orange)](#-workflows)
[![Templates](https://img.shields.io/badge/Templates-12-purple)](#-project-structure)

<br>

> **Clone this repo. Open it in Claude Code. Say `onboard`.**
> That's it — you now have a marketing, sales, strategy, content, intelligence, and management team working for you.

<br>

**No API keys. No pip install. No configuration. Just results.**

<br>

[Get Started](#-quick-start) · [See All Teams](#-the-7-teams) · [Browse Workflows](#-workflows) · [Setup Obsidian](#-obsidian-setup-guide)

</div>

---

## Table of Contents

- [Introduction](#-introduction)
- [Quick Start](#-quick-start)
- [The 7 Teams](#-the-7-teams)
- [Commands](#-commands)
- [Workflows](#-workflows)
- [How It Works](#-how-it-works)
- [Obsidian Setup Guide](#-obsidian-setup-guide)
- [Project Structure](#-project-structure)
- [Quality Gate](#-quality-gate)
- [ROI Tracking](#-roi-tracking)
- [Example Session](#-example-session)
- [Contributing](#-contributing)
- [License](#-license)

---

## Introduction

Most businesses can't afford a full-service agency. The ones that can still wait weeks for deliverables and pay $150/hr for work that's often generic.

**AI Agency in a Box changes that.**

It's a complete agency system — 7 specialized teams with 100+ AI agents — that runs entirely inside [Claude Code](https://docs.anthropic.com/en/docs/claude-code). No external APIs. No monthly SaaS fees. No complex setup. You clone a repo, answer a few questions about your business, and the agency starts working.

Here's what makes it different:

- **It remembers everything.** An [Obsidian](https://obsidian.md)-compatible vault stores your brand voice, competitor research, campaign history, and deliverables. Every session builds on the last.
- **It's not one agent — it's a full agency.** 7 teams with distinct specializations: Marketing (60 agents across 13 sub-teams), Sales, Intelligence, Strategy, Content, Direction, and Managing.
- **It delivers real output.** Blog posts, email campaigns, landing pages, competitive analyses, sales proposals, SEO strategies — not summaries or suggestions, but actual ready-to-use deliverables.
- **It checks its own work.** Every deliverable passes through a quality gate that verifies brand voice, factual accuracy, completeness, and formatting before delivery.

This is v1. It's built for business owners, founders, marketers, and freelancers who need agency-level output without agency-level budgets.

---

## Quick Start

### Step 1: Clone the repo

```bash
git clone https://github.com/z1fex/Agency-in-a-BOX.git
cd Agency-in-a-BOX
```

### Step 2: Open in Claude Code

Open the folder in Claude Code (CLI, VS Code extension, or desktop app).

### Step 3: Onboard your business

```
You: onboard
```

The agency will interview you about your business — company details, target audience, competitors, brand voice, and goals. It takes about 5 minutes.

### Step 4: Run your first workflow

```
You: workflow content-month
```

That's it. The agency researches trends, plans a content calendar, writes 4 blog posts, 30 social media posts, 4 newsletters, and 2 video scripts — all tailored to your brand.

---

## The 7 Teams

<table>
<tr>
<td width="140"><strong>Team</strong></td>
<td width="70" align="center"><strong>Agents</strong></td>
<td><strong>What They Do</strong></td>
</tr>
<tr>
<td>🔴 <strong>Marketing</strong></td>
<td align="center">60</td>
<td>SEO, social media, email campaigns, Google/Meta ads, landing pages, brand management, analytics, influencer marketing, A/B testing, competitive analysis, community management, PR — organized into 13 specialized sub-teams</td>
</tr>
<tr>
<td>🟠 <strong>Sales</strong></td>
<td align="center">10</td>
<td>Lead generation, qualification, cold outreach, call analysis, proposals, CRM management, pipeline tracking, follow-ups, forecasting, competitive battlecards</td>
</tr>
<tr>
<td>🔵 <strong>Intelligence</strong></td>
<td align="center">10</td>
<td>Competitor monitoring, market research, sentiment analysis, trend detection, price tracking, news monitoring, social listening, web scraping, data analysis, industry reports</td>
</tr>
<tr>
<td>🟢 <strong>Strategy</strong></td>
<td align="center">7</td>
<td>SWOT analysis, growth strategy, pricing optimization, market entry planning, resource allocation, risk assessment, business model analysis</td>
</tr>
<tr>
<td>🟣 <strong>Content</strong></td>
<td align="center">10</td>
<td>Blog posts, copywriting, social content, newsletters, video scripts, podcast scripts, whitepapers, content repurposing, editorial calendars, performance analysis</td>
</tr>
<tr>
<td>🟡 <strong>Direction</strong></td>
<td align="center">4</td>
<td>OKR setting, priority management (ICE/RICE scoring), vision alignment, data-driven decision frameworks</td>
</tr>
<tr>
<td>⚪ <strong>Managing</strong></td>
<td align="center">4</td>
<td>Task coordination, quality review, progress reporting, cross-team coordination</td>
</tr>
</table>

### Marketing Sub-Teams (60 agents)

The Marketing team is organized into 13 specialized sub-teams:

| Sub-Team | Agents | Focus |
|----------|--------|-------|
| SEO | 6 | Keyword research, content optimization, technical audits, rank tracking |
| Social Media | 6 | Content scheduling, platform-specific copywriting, engagement |
| Email | 6 | Campaign building, cold outreach, nurture sequences, analytics |
| Advertising | 8 | Google Ads, Meta Ads, LinkedIn Ads, TikTok Ads, creative, budgets |
| Landing Pages | 4 | Copywriting, conversion optimization, sales decks |
| Brand | 3 | Voice management, brand guidelines, messaging consistency |
| Analytics | 5 | Dashboards, web tracking, report generation, KPI monitoring |
| Influencer | 4 | Scouting, vetting, campaign coordination, outreach |
| A/B Testing | 3 | Experiment design, copy variants, results analysis |
| Competitive | 5 | Intelligence gathering, market research, trend analysis, positioning |
| Campaign | 5 | Planning, asset creation, scheduling, budgets, performance tracking |
| Community | 3 | Management, content curation, engagement tracking |
| PR | 3 | Press releases, media outreach, coverage tracking |

---

## Commands

| Command | What Happens |
|---------|-------------|
| `onboard` | Interactive client interview — builds your complete profile |
| `switch client [name]` | Switch between multiple client profiles |
| `run marketing` | Activate the marketing team (choose sub-team or run all) |
| `run sales` | Activate the sales team |
| `run intelligence` | Activate the intelligence team |
| `run strategy` | Activate the strategy team |
| `run content` | Activate the content team |
| `run direction` | Activate the direction team |
| `run managing` | Activate the managing team |
| `workflow [name]` | Run a pre-built workflow chain (see below) |
| `dashboard` | View agency status, active campaigns, deliverables |
| `roi` | See what the agency has produced and estimated cost savings |
| `list teams` | Show all 7 teams and their agents |
| `list workflows` | Show all available workflows |
| `status` | Current client, active campaigns, recent work |

---

## Workflows

Each workflow chains multiple agents together to produce a complete deliverable package.

<table>
<tr>
<td width="180"><strong>Workflow</strong></td>
<td width="50" align="center"><strong>Steps</strong></td>
<td><strong>What You Get</strong></td>
</tr>
<tr>
<td>🚀 <strong>Product Launch</strong></td>
<td align="center">11</td>
<td>Market research, competitor analysis, positioning, 3 blogs, 30 social posts, email sequence, ad copy, landing page, press release, launch calendar</td>
</tr>
<tr>
<td>🎯 <strong>Lead Generation</strong></td>
<td align="center">8</td>
<td>ICP research, 50-lead list, qualification, outreach emails, follow-ups, battlecards, proposal template</td>
</tr>
<tr>
<td>📝 <strong>Content Month</strong></td>
<td align="center">7</td>
<td>Trend research, content calendar, 4 blogs, 30 social posts, 4 newsletters, 2 video scripts, repurposing plan</td>
</tr>
<tr>
<td>🔍 <strong>Competitor Report</strong></td>
<td align="center">8</td>
<td>Competitor scraping, SWOT per competitor, feature comparison, pricing analysis, battlecards, final report</td>
</tr>
<tr>
<td>🎨 <strong>Brand Audit</strong></td>
<td align="center">6</td>
<td>Brand analysis, voice audit, messaging framework, brand guidelines, style guide</td>
</tr>
<tr>
<td>📈 <strong>SEO Overhaul</strong></td>
<td align="center">8</td>
<td>Technical audit, 100 keywords, competitor SEO, content gaps, 5 optimized posts, meta descriptions, linking strategy</td>
</tr>
<tr>
<td>📧 <strong>Email Sequence</strong></td>
<td align="center">6</td>
<td>Audience segments, welcome series (5), nurture series (5), re-engagement (3), 39 A/B subject line variants</td>
</tr>
<tr>
<td>📱 <strong>Social Media Blitz</strong></td>
<td align="center">7</td>
<td>Platform strategy, 30 posts, hashtag playbook, engagement plan, community guidelines</td>
</tr>
<tr>
<td>🧠 <strong>Full Strategy</strong></td>
<td align="center">10</td>
<td>OKRs, SWOT, market research, competitive analysis, growth + marketing + sales + content strategy, 90-day plan, KPI dashboard</td>
</tr>
</table>

---

## How It Works

```
┌─────────────────────────────────────────────────────┐
│                  YOU GIVE AN OBJECTIVE               │
└─────────────────────┬───────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────┐
│          CLAUDE.md routes to the right team          │
└─────────────────────┬───────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────┐
│     Agent reads your client profile from vault       │
└─────────────────────┬───────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────┐
│    Agent researches (web search, competitor sites)    │
└─────────────────────┬───────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────┐
│     Agent produces deliverable using templates        │
└─────────────────────┬───────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────┐
│  Quality gate checks voice, accuracy, completeness   │
└─────────────────────┬───────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────┐
│   Saved to vault (memory) + output folder (delivery) │
└─────────────────────┬───────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────┐
│        Dashboard and ROI tracker updated             │
└─────────────────────────────────────────────────────┘
```

---

## Obsidian Setup Guide

The `vault/` folder is an [Obsidian](https://obsidian.md)-compatible knowledge base. It's the agency's brain — it stores client profiles, research, campaigns, and deliverables with interconnected links.

### Why Obsidian?

- **Visual knowledge graph** — see how clients, campaigns, research, and deliverables connect
- **Bidirectional links** — `[[Client Name]]` creates a web of context automatically
- **Free and open source** — just a folder of markdown files
- **You can edit too** — add notes, correct info, and the agency picks it up

### Setup (Optional — the agency works without it)

**Step 1:** Download Obsidian for free from [obsidian.md](https://obsidian.md)

**Step 2:** Open Obsidian and click **"Open folder as vault"**

**Step 3:** Select the `vault/` folder inside this project

**Step 4:** You'll see the full agency knowledge base:

```
vault/
├── 00-Dashboard/        → Agency dashboard + ROI tracker
├── 01-Clients/          → Client profiles (created during onboarding)
├── 02-Campaigns/        → Campaign tracking
├── 03-Research/         → Market research, trends, reports
├── 04-Intelligence/     → Competitor monitoring, sentiment data
├── 05-Content/          → Content library, calendars, drafts
├── 06-Sales/            → Leads, proposals, pipeline
├── 07-Strategy/         → SWOT analyses, growth plans, pricing
└── 08-Operations/       → QA reviews, progress reports
```

**Step 5:** After onboarding, your client profile appears with linked notes. Open the **Graph View** (left sidebar) to see the knowledge web.

> **Don't have Obsidian?** No problem. The vault files are just markdown — browse them in VS Code, any text editor, or let the AI manage everything automatically.

---

## Project Structure

```
Agency-in-a-BOX/
│
├── CLAUDE.md                  # The brain — agency instructions
├── README.md                  # You are here
├── LICENSE                    # MIT
│
├── agents/                    # 66 agent prompt files
│   ├── marketing/             #   60 agents across 13 sub-teams
│   ├── sales/                 #   10 agents
│   ├── intelligence/          #   10 agents
│   ├── strategy/              #   7 agents
│   ├── content/               #   10 agents
│   ├── direction/             #   4 agents
│   ├── managing/              #   4 agents
│   └── _base/                 #   Quality standards for all agents
│
├── workflows/                 # 9 pre-built workflow chains
├── templates/                 # 12 professional deliverable templates
├── tools/                     # 6 free tool guides + 3 helper scripts
├── onboarding/                # Client interview and profile builder
├── quality/                   # Quality gate checklist
│
├── vault/                     # Obsidian vault (persistent memory)
│   ├── 00-Dashboard/          #   Agency dashboard + ROI tracker
│   ├── 01-Clients/            #   Client profiles
│   ├── 02-Campaigns/          #   Campaign tracking
│   ├── 03-Research/           #   Market research, trends
│   ├── 04-Intelligence/       #   Competitor monitoring
│   ├── 05-Content/            #   Content library, calendars
│   ├── 06-Sales/              #   Leads, proposals, pipeline
│   ├── 07-Strategy/           #   SWOT, growth plans
│   └── 08-Operations/         #   QA reviews, reports
│
└── output/                    # Final deliverables by client/date
```

### What's Inside

| Folder | Files | Purpose |
|--------|-------|---------|
| `agents/` | 66 | One markdown file per agent with role, instructions, and output format |
| `workflows/` | 9 | Step-by-step playbooks that chain agents together |
| `templates/` | 12 | Professional deliverable templates (strategy docs, proposals, reports, etc.) |
| `tools/` | 9 | Free tool guides (web research, competitor scraping, social listening) + Python scripts |
| `vault/` | 8 | Obsidian-compatible memory vault with dashboard, templates, and folder structure |
| `onboarding/` | 1 | Interactive client interview script |
| `quality/` | 1 | Pre-delivery quality checklist |

---

## Quality Gate

Every deliverable passes through a quality gate before delivery:

| Check | What It Verifies |
|-------|-----------------|
| **Brand Voice** | Matches your brand personality, tone, approved/banned words |
| **Accuracy** | All facts verified via web search, all claims sourced |
| **Completeness** | No placeholders, no TODOs, all sections filled |
| **Specificity** | Tailored to your business — never generic advice |
| **Formatting** | Uses correct template, professional structure |
| **Vault Integration** | Saved correctly, linked with wikilinks, dashboard updated |

---

## ROI Tracking

The agency tracks everything it produces in `vault/00-Dashboard/ROI Tracker.md`:

| Deliverable Type | Estimated Hours Saved | Value at $150/hr |
|-----------------|----------------------|------------------|
| Blog post | 2.5 hrs | $375 |
| 30 social posts | 30 hrs | $4,500 |
| Email campaign (5 emails) | 10 hrs | $1,500 |
| Competitor analysis | 3 hrs | $450 |
| Marketing strategy | 8 hrs | $1,200 |
| Full strategy package | 40 hrs | $6,000 |

A single `workflow content-month` produces ~40 deliverables worth an estimated **$3,000+** in traditional agency fees.

---

## Example Session

```
You: onboard

Agency: Welcome to your AI Agency! I'll ask you some questions
        about your business so I can set up your profile.
        What's your company name?

You: FreshBrew Coffee — we sell single-origin coffee beans online

Agency: Great! What industry are you in, and who's your ideal customer?

You: D2C specialty coffee. Our customers are coffee enthusiasts
     aged 25-40 who care about quality and sustainability.

Agency: [continues interview... competitors, brand voice, goals]

        Your profile is set up! Here's what I've created:
        - Client Profile
        - Brand Voice Guide
        - Competitive Landscape
        - Ideal Customer Profile
        - Goals & Success Criteria

        Based on your goals, I recommend starting with:
        1. workflow content-month — build your content engine
        2. workflow seo-overhaul — fix your organic search gap
        3. workflow lead-generation — build your sales pipeline

        What would you like to work on first?

You: workflow content-month

Agency: [researches real trends via web search]
        [plans 30-day content calendar]
        [writes 4 SEO-optimized blog posts]
        [creates 30 platform-specific social posts]
        [writes 4 email newsletters]
        [writes 2 video scripts]
        [runs quality gate on everything]
        [saves to vault + output folder]

You: dashboard

Agency: FreshBrew Coffee | Active
        40 deliverables | 20.5 hours saved | $3,075 value
```

---

## Multi-Client Support

The agency supports multiple clients simultaneously. Each client gets their own profile in `vault/01-Clients/` with dedicated brand voice, competitors, ICP, and goals.

```
You: switch client NexusAI
```

All agents automatically load the new client's context. Research, deliverables, and campaigns stay organized per client.

---

## Requirements

| Requirement | Details |
|-------------|---------|
| **Claude Code** | CLI, VS Code extension, or desktop app |
| **Python 3.6+** | Only for optional helper scripts in `tools/scripts/` |
| **Obsidian** | Optional — for visual vault browsing |

**That's it.** No API keys, no packages, no environment variables, no build steps.

---

## Contributing

Contributions are welcome.

1. Fork the repo
2. Create a branch (`git checkout -b feature/new-workflow`)
3. Add your agents, workflows, or templates
4. Submit a pull request

**Ideas for contributions:**
- New agents for existing teams
- New workflow chains
- Industry-specific templates (SaaS, e-commerce, real estate, etc.)
- Translations

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

**Built for business owners who want agency-level output without agency-level costs.**

[Get Started](#-quick-start) · [Star this repo](https://github.com/z1fex/Agency-in-a-BOX)

</div>
