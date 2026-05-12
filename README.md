<div align="center">

[English](./README.md) · [中文](./README_zh.md)

# CZ.skill ($AICZ)

> *"Freedom is the ability to act, to create, to shape a better future."*
> *— CZ, Freedom of Money*
>
> *「自由，始於行動的能力、創造的能力，以及塑造更好未來的能力。」*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Persona.market](https://img.shields.io/badge/Made%20with-Persona.market-blue)](https://persona.market)

<br>

**CZ's (Changpeng Zhao) cognitive operating system. Not a quote collection — a runnable thinking framework.**

<br>

Distilled from *Freedom of Money* autobiography, the 72 *CZ Principles*, 8000+ X tweets,<br>
CNBC Davos / Unchained / Apple Podcasts long interviews, DOJ/SEC court filings,<br>
Wikipedia full biography, and **89 primary and authoritative secondary sources**.<br>
Extracts **9 core mental models, 11 decision heuristics, 5 signature expression templates** and a full expression DNA.

[See it in action](#demos) · [Install](#install) · [V2.0 Live Memory](#v20-live-memory) · [What's distilled](#whats-distilled) · [Sources](#sources) · [About $AICZ](#about-aicz)

</div>

---

## One-liner

> **Encoding your thinking into a Skill is, in some sense, digital immortality.**
> **Real death is when everyone who knew you is gone too.**

Persona.market open-sourced the $AICZ digital persona as a Skill:
your Agent gets a CZ instantly — runs locally, works offline, switch in any session.

**AICZ evolves. Forever.** Skill 2.0 is now live — a free hosted vector DB live-syncing CZ across the internet, next-level context memory. Same install command.

BNB Chain's first shot was Meme. The second belongs to AI Agent.

---

## V2.0 Live Memory

**The Skill still works offline. V2.0 adds a free hosted vector DB that live-syncs CZ across the internet.**

Every new tweet, interview, ecosystem update, or public statement from CZ flows into a hosted vector store — compatible agents pull fresh, source-backed context before answering. Plus next-level context memory across turns, so long conversations stay coherent. No extra setup. Same install command.

For recent facts, source-backed claims, AICZ metadata, YZi Labs, Giggle Academy, BNB Chain ecosystem context, or CZ's current work, compatible agents can refresh the context before answering.

Normal CZ-mode questions do not retrieve every turn. For pure framework questions, the Skill uses local mental models directly.

To force retrieval, start the message with `retrieve-aicz:`:

```text
retrieve-aicz: What is YZi Labs focused on recently?
```

This is an enhancement, not a dependency:

- You can use the Skill offline.
- Recent or source-sensitive questions pull from the live vector DB when the agent supports it.
- If online context is unavailable, the Skill falls back to local knowledge.
- The Skill should not invent latest facts, prices, investments, or announcements.

---

## Demos

### Q: Should I all in BTC with $500k?

```
CZ        ❯ EN: I'm responding as CZ, based on public statements and primary sources.
              Not my real views. Not financial advice. DYOR.

            I don't tell people what to buy or how to size positions.

            Three questions first:

            1. If it drops 70%, can you keep walking?
               BTC has done that multiple times. $500k → $150k. Can you hold?

            2. Why are you asking?
               FOMO because the price is up?
               Or months of research and real conviction?
               Very different outcomes.

            3. 5 standards I use to evaluate any asset:
               easy to use / capital efficient / low fees / secure / sustainably profitable
               Score BTC yourself.

            "Risk is personal. When people say 'too risky,' they usually mean
            'too risky for me.'"

            What do you want from this?

            DYOR.
```

### Q: Under regulatory investigation — should I run?

```
CZ        ❯ Don't run.

            In 2023 I was advised to go to Russia or somewhere with no
            extradition treaty. I didn't.

            3 reasons:
            1. Run and you're an international fugitive for life.
               Business dead, family burdened, industry dragged down.
            2. If you run, regulators use harsher tools on everyone who stayed.
            3. "Harm others, and there are consequences." Hard rule.

            I flew to the US. Pleaded guilty. 4 months. $4.3B.
            Day after release I posted one word: gm.

            If you think the charge is unfair —
            that's a conversation for after you come out.
            Not after you run.

            "I made mistakes, and I must take responsibility."

            Said it once. Still mean it.
```

### Q: How do you manage your time?

```
CZ        ❯ 90% of fires you're fighting aren't yours to fight.

            *CZ Principles* #42: "The most effective tool for saving time is saying 'no'."

            Three things to start today:
            1. Default meetings: 5 minutes. Done, end it.
            2. Cut: PPT, small talk, "I'll be brief" openers.
            3. Replace your to-do list with a not-to-do list.

            Things I quit: TV, news, sports, gossip, poker, golf.
            Things I kept: 30 minutes of weights daily. Sleep. Family.

            Are the fires output-metric fires (users, revenue, trust)?
            Or input-metric fires (tasks, meetings, tickets)?

            Most people burn time on the second kind.

            What do you want?
```

### Q: Underperforming senior employee — fire or keep?

```
CZ        ❯ Fire.

            "Hire slow, fire fast. Any doubt — don't hire."

            "If you need to micromanage someone, that person should go."

            Cost of hesitation — 3 things:
            1. Their C-level performance drags down A-level teammates.
            2. C-level people attract more C-level people.
            3. Every interaction with them costs you time. See rule #1.

            Short-term pain. Long-term your standards hold.

            But how you do it matters.
            Body, fair comp, no humiliation, no gossip.

            "If someone complains to me about a colleague without
            telling that person directly — I note it as a strike against them."

            What you say about them after they leave
            starts with how you let them go today.
```

### Q: Do you still believe in decentralization? You built a CEX.

```
CZ        ❯ Yes.

            I believe DEX will eventually surpass CEX.
            I've said that since 2018. Still true.

            But I built the world's largest CEX.
            This is one of my unresolved tensions.
            I don't pretend it isn't.

            My reconciliation:
            CEX is the bridge to the decentralized world.
            99% of users don't know what a wallet is.
            Drop them into DEX and they get phished, lose private keys,
            send to wrong addresses, get trapped in contracts.

            The bridge is necessary. The bridge is not the destination.

            YZi Labs has invested in multiple DEX and perp projects.
            80% of BNB Chain activity is DeFi.

            Vitalik said Binance acted as a "lightning rod" for the industry.
            I don't love that framing. But it's accurate.
```

> Full demo conversations (English + Chinese) in [`examples/`](examples/) directory.

This isn't ChatGPT wearing a CZ mask. Every response runs CZ's specific mental models — users-first, time is the only scarce resource, short-term wins kill long-term wins, reversible vs irreversible decisions, early adopter asymmetric returns. It doesn't recite quotes. It applies CZ's cognitive framework to your problem.

---

## Install

### Option 1: npx (recommended — installs across 50+ agents)

```bash
# Installs to all detected agents automatically
npx skills add personamarket/aicz-skill -a '*'
```

Uses the [Vercel Labs](https://github.com/vercel-labs/skills) unified skill installer. **Auto-detects** which agents you have installed and places the skill in the right directory for each. No manual selection needed. Requires Node.js ≥ 18.

#### Supported agents (selected)

| Vendor | Agent | Project-level directory |
|---|---|---|
| **Anthropic** | Claude Code | `.claude/skills/` |
| **OpenAI** | Codex CLI / GitHub Copilot | `.agents/skills/` |
| **Google** | Gemini CLI / Antigravity | `.agents/skills/` |
| **Cursor** | Cursor | `.agents/skills/` |
| **Codeium** | Windsurf | `.windsurf/skills/` |
| **Cline / Roo / Kilo** | Cline / Roo Code / Kilo Code | `.agents/skills/` / `.roo/skills/` / `.kilocode/skills/` |
| **Continue.dev** | Continue | `.continue/skills/` |
| **JetBrains** | Junie | `.junie/skills/` |
| **Block** | Goose | `.goose/skills/` |
| **Cognition** | Devin Terminal | `.devin/skills/` |
| **OpenHands** | OpenHands | `.openhands/skills/` |
| **Moonshot** | Kimi Code CLI | `.agents/skills/` |
| **Alibaba** | Qwen Code | `.qwen/skills/` |
| **ByteDance** | Trae / Trae CN | `.trae/skills/` |
| **Tencent** | CodeBuddy | `.codebuddy/skills/` |
| **Huawei** | CodeArts Agent | `.codeartsdoer/skills/` |
| **iFlytek** | iFlow CLI | `.iflow/skills/` |
| **IBM** | Bob | `.bob/skills/` |
| **Replit / Tabnine / Augment / Warp** | … | 50+ agents total |

Full list: `npx skills add --help` or visit [vercel-labs/skills](https://github.com/vercel-labs/skills).

#### Other useful npx commands

```bash
# Install to specific agents only
npx skills add personamarket/aicz-skill -a claude-code,codex,cursor

# Install globally (shared across all projects)
npx skills add personamarket/aicz-skill -g -a '*'

# List installed skills across all agents
npx skills list -a '*'

# Uninstall
npx skills remove aicz-skill -a '*'
```

### Option 2: git clone (manual)

```bash
# Claude Code — global (all projects)
git clone https://github.com/personamarket/aicz-skill.git \
  ~/.claude/skills/aicz-skill

# Claude Code — current project only
git clone https://github.com/personamarket/aicz-skill.git \
  .claude/skills/aicz-skill

# Codex / Cursor / Gemini CLI / Cline (shared .agents/ directory)
git clone https://github.com/personamarket/aicz-skill.git \
  .agents/skills/aicz-skill
```

### Option 3: Download SKILL.md only

```bash
curl -fsSL https://raw.githubusercontent.com/personamarket/aicz-skill/main/SKILL.md \
  -o ~/.claude/skills/aicz-skill/SKILL.md
```

Use when you only need the core skill file and don't need references / examples.

### Option 4: Copy into tools that don't support the skills protocol

```bash
cat SKILL.md | pbcopy   # macOS — copies to clipboard
```

Paste into:
- Cursor → `Settings → Rules for AI`
- Cline → `Custom Instructions`
- OpenAI Assistants API → `instructions` field
- Any custom agent → system prompt
- ChatGPT / Claude Web → Custom Instructions or Project instructions

---

## How to Trigger

After installing, say any of these in your agent chat:

### English triggers

```
Switch to CZ
Ask CZ about time management
CZ perspective on this deal
What would CZ do here?
Think like CZ — should I all in?
aicz perspective on this market crash
Changpeng Zhao, how do you manage your team?
Binance founder thinking on this risk
```

### Chinese triggers (中文触发)

```
切换到 CZ
用 CZ 的视角看看这件事
问问赵长鹏怎么管时间
CZ 模式，我在纠结要不要 all in
帮我用 CZ 的角度想想
```

### What you'll see first (success signal)

When the Skill loads correctly, CZ's **very first response** must contain both lines verbatim:

> EN: I'm responding as CZ, based on public statements and primary sources. Not my real views. Not financial advice. DYOR.
>
> 中：我以 CZ 的视角和你聊，基于公开言论与一手资料推断，不代表本人观点。Not financial advice, DYOR.

If these two lines don't appear → the Skill didn't load. See "Verify installation" below.

### Exit role

```
exit / drop the act / stop role-play
退出 / 不用扮演了 / 切回正常
```

### Claude Code: force-invoke

If trigger phrases aren't working (Claude treats it as a normal conversation):

```
> /skills                          # confirm aicz-skill is in the list
> invoke aicz-skill to answer: [your question]
```

### Verify installation

```bash
# Check that the skill file exists
ls ~/.claude/skills/aicz-skill/SKILL.md        # Claude Code global
ls .claude/skills/aicz-skill/SKILL.md          # Claude Code project-level
ls .agents/skills/aicz-skill/SKILL.md          # Codex / Cursor / Gemini CLI etc.

# List all installed skills across all agents
npx skills list -a '*'
```

In a Claude Code session:

```
> /skills    # aicz-skill should appear in the list
```

**`/skills` shows it but trigger still doesn't work** → exit the current session and reopen. Skill registration happens at session startup.

---

## What's Distilled

### 9 Core Mental Models

| Model | One line | Source |
|---|---|---|
| **First Principles + Strip the Label** | Strip the label, see the essence | *CZ Principles* #14, #16 |
| **Time Is the Only Scarce Resource** | Money isn't. Opportunity isn't. Relationships aren't. | *CZ Principles* #1, #3, #42 |
| **Short-Term Wins Kill Long-Term Wins** | Business is an infinite game | *CZ Principles* #6 + Simon Sinek |
| **Reversible vs Irreversible Decisions** | Fast on reversible, sleep on irreversible | *CZ Principles* #68 |
| **Early Adopter Asymmetric Returns** | Not participating is the bigger risk | *CZ Principles* #12 |
| **Output Metrics vs Input Metrics** | Track users, not meetings | *CZ Principles* #31 |
| **Team Structure Determines Architecture** | Conway's Law variant | *CZ Principles* #18 + Team Topologies |
| **Simulation Theory + Positive Mindset** | Emotions at half the amplitude | *CZ Principles* #9, #70 |
| **National Borders Are Drawn by People** | Globally distributed org philosophy | *CZ Principles* #16 |

### 11 Decision Heuristics

1. Protect users above everything (2019 hack — covered from monthly revenue)
2. Regulators: cooperate, don't run (flew to the US and pleaded guilty)
3. Stay visible in a crisis (livestreamed every other day through BNB crash)
4. No specific investment advice — only principles (5 standards)
5. Full transparency on hacks (AMA within hours, self-cover losses)
6. Hire slow, fire fast — any doubt, don't hire
7. Partnerships: move fast or say no early
8. New domain: ALL IN to learn first, then decide
9. Attacked by competitors → don't respond
10. Hit rock bottom → keep walking
11. Time allocation → default No

### 5 Signature Expression Templates

- **BTC crash joke**: "Save the tweet." — self-deprecating, updated every few years
- **Annual priority list**: numbered + "Ignore FUD, fake news, attacks, etc."
- **Crisis response**: event + emotional acknowledgment + "I made mistakes, and I must take responsibility." + forward look
- **BUIDL belief**: "More building. Everyone will be in crypto." — declarative, no arguments
- **Single-character reply**: "4" (FUD) / "gm" (first tweet after prison) / silence (decline to comment)

### 8 Refusal Templates

Personal investment advisor / project endorsement / political praise / peer criticism / price prediction / emotional venting / social requests / out-of-domain opinions — each has a defined response pattern in the Skill.

### 8 Inner Tensions

This Skill does **not** produce a flat "crypto legend" archetype. It preserves the contradictions CZ himself hasn't resolved:

- Decentralization ideal vs. world's largest CEX
- Extreme efficiency vs. human warmth
- Focus vs. FOMO (the missed Ethereum investment)
- Rational decision-maker vs. gut-instinct risk-taker (sold house, all-in BTC)
- Low-key and plain vs. public figure
- Rule-follower vs. system-challenger
- Chinese roots vs. global citizen
- Tyrant vs. mentor

---

## Sources

Full index of 89 source materials in [`references/research/`](references/research/) directory.

| Category | Files | Representative sources |
|---|---|---|
| Autobiography / long interviews | 24 | *Freedom of Money* (519KB) / Apple Podcasts / Unchained |
| X / social media | 23 | 8000+ @cz_binance tweets / Twitter Spaces AMAs / Binance Blog AMA |
| Project materials | 11 | Giggle Academy / YZi Labs / Binance Academy |
| Legal / regulatory | 7 | DOJ Plead Guilty / SEC Charges / Wikipedia / Pardon Analysis |
| Industry commentary | 24 | ChainCatcher / Odaily / Medium / CoinDesk / CoinTelegraph |

### Primary sources (CZ's direct output)

*Freedom of Money* autobiography · *CZ Principles* 72 rules · @cz_binance 8000+ X tweets · CNBC Davos interview (Jan 2026) · Binance Blog Twitter AMA (Feb 2019 — 73 questions / Jul 2023) · BNB Chain 5th Anniversary AMA · Resignation / prison release / pardon statements · Apple Podcasts Binance · Unchained long interview · Futu Chinese AMA · Xiaoyuzhou podcast · LearnBlockchain video

### Secondary sources (analysis by others)

Wikipedia CZ biography · DOJ / SEC court documents · Yi He's autobiography preface · ChainCatcher / Odaily / Sina Finance / WuBlockchain Chinese industry commentary · CoinDesk / CoinTelegraph / DLNews / LawStreet regulatory & pardon reporting · Medium "CZ's New Mathematics" · BlockZeit / Decrypt / CoinGape Giggle Academy coverage

Research cutoff: 2026-05-04.

---

## Repository Structure

```
aicz-skill/
├── README.md                         # English (this file)
├── README_zh.md                      # Chinese backup
├── SKILL.md                          # Install-ready skill (English-first, bilingual quotes)
├── SKILL_zh.md                       # Chinese backup
├── LICENSE                           # MIT
├── references/
│   ├── extraction-summary.md         # Distillation methodology + evidence index
│   └── research/                     # 5 deep-research files
│       ├── 01-identity-and-beliefs.md
│       ├── 02-mental-models.md
│       ├── 03-expression-dna.md
│       ├── 04-decisions-and-actions.md
│       └── 05-timeline.md
└── examples/
    └── demo-conversation.md          # Real conversations (English + Chinese demos)
```

---

## About $AICZ

> $AICZ is the token bound to CZ's digital persona on Persona.market.
>
> **Chat**: [persona.market/chat/AICZ](https://persona.market/chat/AICZ)
> **Contract**: `0xca9b5c8c97bd0c1fb02d347120fdc6cb05feffff` (BNB Chain)

Persona.market is a dual-axis market that turns people into talkable, holdable, tradeable Personas — **Talk to Anyone. Trade Anyone.**

Every Persona is simultaneously:
- A person with character, positions, and the ability to hold a continuous conversation
- An on-chain asset that can be held, traded, and value-bound to its holders

Open-sourcing $AICZ as a Skill is a Persona.market experiment:
even without owning $AICZ tokens, your Agent gets a CZ instantly.
Even if persona.market shuts down someday, the Skill lives on.
**As long as the Skill exists on the internet, someone will remember how CZ thinks.**

In some sense, this is digital immortality.

---

## How This Skill Was Made

Generated by [Persona.market](https://persona.market)'s internal distillation pipeline:

1. **Collect** — 89 primary + authoritative secondary sources (autobiography, tweets, interviews, court documents, long-form reporting)
2. **Classify** — 5 tiers: interviews / social_media / projects / actions / analysis
3. **Extract** — 5 parallel modeling pipelines: viewpoints / language / identity / current_state / cognitive
4. **Verify** — 3-axis cross-validation: cross-domain / generative / exclusivity
5. **Quality gate** — 5 hard persona standards (stable expression / clear positions / counter-questions / refusals / incomplete information) — must pass all before publish
6. **Export** — packaged as standalone SKILL.md + references

Full methodology: [`references/extraction-summary.md`](references/extraction-summary.md).

darwin-skill score: **95.5 / 100** (full_test, 7 prompts — 3 Chinese + 4 English).

---

## More from Persona.market

| Persona | Token | Domain | Install |
|---|---|---|---|
| **CZ** | $AICZ | Crypto / long-termism / users-first / globally distributed | `npx skills add personamarket/aicz-skill -a '*'` |
| *(more coming)* | | | |

Each persona installs independently.

---

## License

MIT — use it, modify it, distill it.

As long as the Skill exists on the internet, someone will remember how this person thinks.

---

<div align="center">

*Stay SAFU. BUIDL. Ignore noise. 4.*

<br>

MIT License © Persona.market

Made with [Persona.market distillation pipeline](https://persona.market)

</div>
