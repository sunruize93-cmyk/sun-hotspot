<p align="center">
  🌐 <a href="README.md">中文</a> | <a href="README_EN.md"><b>English</b></a>
</p>

<h1 align="center">🍌 Sun Hotspot · skill</h1>

<p align="center">
  <i>A configurable hotspot-catching skill, distilled from Justin Sun (孙宇晨) — the man who never misses a trending topic.</i><br/>
  Every viral move, every quote, every posting trick he's made in over a decade online — reverse-engineered for you.
</p>

<p align="center">
  <a href="https://github.com/sunruize93-cmyk/sun-hotspot/releases"><img src="https://img.shields.io/badge/Version-v1.0.0-blue" alt="Version 1.0.0"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-green" alt="License: MIT"/></a>
  <a href="https://github.com/sunruize93-cmyk/sun-hotspot/releases/tag/v1.0.0"><img src="https://img.shields.io/badge/Release-v1.0.0-brightgreen" alt="Release v1.0.0"/></a>
  <img src="https://img.shields.io/github/stars/sunruize93-cmyk/sun-hotspot" alt="GitHub stars"/>
  <img src="https://img.shields.io/badge/Content-Chinese-orange" alt="Content: Chinese"/>
</p>

---

## ⚡ Quick Start (30 seconds)

```bash
# 1. Get the package
git clone https://github.com/sunruize93-cmyk/sun-hotspot.git
# 2. Fill in your config (only 2 required fields: niche + budget)
cp 配置模板/config.example.md config.md
# 3. Paste the full SKILL.md into any AI, then say: give me a hot-topic battle plan based on my config.md
```

| What you want | Where |
|---|---|
| 🚀 Quick install | "Quick Start" below |
| 📖 Full usage guide | "Usage Guide" below |
| 💬 Feedback / Bugs / Ideas | [GitHub Issues](https://github.com/sunruize93-cmyk/sun-hotspot/issues) |
| ⭐ Find it useful? | Hit the ⭐ top right (support = fuel) |

---

## Who is this for?

- People working in **AI / self-media / cross-border e-commerce / indie dev / anything that needs traffic**
- People who want to ride trends, but often realize "the trend is already over" by the time they notice
- People comfortable with GitHub and AI chat tools (**no coding required**)

---

## How it works (30-second overview)

```
You fill in config (niche/platform/budget)  →  the skill scans current hotspots  →  output = your trending-topic battle plan
[Sun Hotspot.skill]                            [12-layer Sun method]                   [topics + copy + risks]
```

**A real example** (assume config = "AI tool reviews · Xiaohongshu · budget ¥1000"):

> 📌 **Hotspot scan**: Justin Sun sues Jing Tian (blew up 8/27, still hot) → your angle: "AI writing controversy", play: anchor to the hotspot (#1)
>
> 🎯 **3 topics**:
> 1. "Sun Yuchen's 10k-word post, distilled into a 15KB AI skill" — AI + gossip double hotspot (number-bombing)
> 2. "He asked Claude whether to pay $50M; the AI said no" — the "Blame Claude" meme (name-drop formula)
> 3. "From a New Concept essay prize to a lawsuit — the same writing formula for 19 years" — deep-dive (serial drama)
>
> ✍️ **Copy skeleton for the top pick**: Xiaohongshu image post → big-text cover + 3 image cards + interactive ending hook (full version in output)

Now you know what you'll get after installing.

---

## Quick Start (5 minutes)

### Step 1: Download

```bash
git clone https://github.com/sunruize93-cmyk/sun-hotspot.git
```

### Step 2: Create your config

In `配置模板/`, copy `config.example.md` to `config.md`:

```bash
cp 配置模板/config.example.md config.md
```

**Only 2 required fields** (the rest can be left blank):
- `领域` (niche): what you do (e.g. AI tool reviews / cross-border e-commerce / food)
- `资源` (budget): money/time per attempt (e.g. ≤¥1000, 1 hour/day)

> Too lazy to fill it in yourself? Paste this into your AI:
> **"Fill config.md for me — I do XXX, mainly on YYY platform, budget ZZZ."**
> It will generate the config for you.

### Step 3: Launch

Open your AI tool of choice, paste the **full text of `SKILL.md`** in as your system prompt, then ask:

```
Based on my config.md, scan today's hotspots and give me a battle plan.
```

If you use Claude Code, after installing just type `/孙割热点学` (see install below).

---

## Usage Guide

### 1. Config fields (config.md)

| Field | Required | What it does | Example |
|---|---|---|---|
| `名字` (name) | optional | tone of copy | Xiaolu |
| `领域` (niche) | ✅ | your track, decides which hotspots fit | AI tool reviews |
| `平台` (platform) | optional | main platform, decides copy format | Xiaohongshu images |
| `人设` (persona) | optional | public identity, for contrast | ex-FAANG PM, now freelance |
| `资源` (budget) | ✅ | money/time per attempt | ≤¥1000, 1h/day |
| `频率` (frequency) | optional | posting cadence | 3×/week |
| `风格` (style) | optional | serious/meme/sarcastic/emotional | meme-first |
| `红线` (red lines) | optional | absolute no-go topics | no surrogacy, no politics |
| `目标` (target) | optional | the specific trend you're eyeing | Jing Tian incident |

**Unfilled fields** get defaults, or the skill asks 1-2 key questions. Only 2 are required: **niche** + **budget**.

### 2. Common prompts

```text
# Hotspot scan
Based on my config, scan what I can ride today. Judge whether it's worth it by Sun Yuchen's "act within 24 hours" standard.

# Topic generation
Give me 3 topics about 「XX」 using the Sun formulas, each traceable to a real move of his.

# Copy skeleton
Using "number-bombing" + "name-drop" formulas, write me a Xiaohongshu image-post skeleton riding 「XX hotspot」, within 300 chars.

# Post-mortem
Diagnose my last viral/flopped post with the Sun method — where did I lose the traffic?
```

### 3. Install as a Claude Code skill (optional, for CLI users)

```bash
# After cloning, put the whole folder into Claude Code's skill directory
mkdir -p ~/.claude/skills && cp -r sun-hotspot ~/.claude/skills/孙割热点学
```

Then type `/孙割热点学` in conversation.

> **Don't want to install a skill?** No problem. Paste the full `SKILL.md` + your `config.md` into any AI chat tool (ChatGPT/Claude/Kimi/Doubao) as a system prompt — same effect.

---

## FAQ

| Question | Answer |
|---|---|
| **I can't use the command line** | Fine. Just paste SKILL.md into an AI + fill config.md — fully graphical |
| **The AI ignores the skill** | Paste SKILL.md first, then add: "strictly follow the method above, trace every step to a Sun Yuchen case" |
| **Will riding a trend backfire?** | It can. The skill includes risk flags and red lines — read "🚨 risks" before posting. If you still get burned, use layer 9 "reframe the narrative" |
| **I have no money — can I still use it?** | Yes. 90% of the layers are zero-cost (anchor hotspots / number-bomb / create friction). Money is just an accelerator. See the budget table in the methodology |
| **The trend already passed — too late?** | Use the "3 questions": still residual heat? can you insert an extreme variable? does it fit your niche? If all yes, you can still ride it |
| **Sun was sued by the SEC — won't I get in trouble copying him?** | The skill already **removed** his illegal tactics (wash trading / market manipulation / paying celebs to shill without disclosure). Only legal content-marketing playbooks remain — see the red lines |

---

## 🚨 Red Lines (read this)

1. No fabrication, defamation, or privacy leaks; for real people, use facts and cite sources
2. No investment advice, no pump-and-dump, no fake engagement, no market manipulation
3. Platform rules first (Xiaohongshu/Douyin are sensitive to topics like surrogacy and politics — respect moderation)
4. Traffic has a price: riding a trend can backfire, personas flip — think before you post
5. Understanding ≠ imitation: this skill is for understanding traffic logic, not an endorsement of Justin Sun or his business practices

---

## File structure

```
sun-hotspot/
├── README.md                       ← Chinese docs (you are here: EN)
├── README_EN.md                    ← English version
├── SKILL.md                        ← main skill instruction (the core to paste into AI)
├── LICENSE                         ← MIT License
├── 配置模板/
│   └── config.example.md           ← config template (copy to config.md)
├── 知识库/
│   ├── 01-孙宇晨热点事件档案.md      ← every viral event: timeline + data + teardown
│   ├── 02-孙宇晨推特语录与发帖风格.md ← quotes + copy formulas + behavior patterns
│   └── 03-孙氏流量方法论.md          ← 12-layer method + budget table
└── 示例输出/
    └── 示例作战包-2026-08-28.md      ← a real battle plan as reference
```

---

## 📄 License

This project is released under the **MIT License** ([full text](LICENSE)):

- ✅ **Free to use, modify, and distribute** (including commercially)
- ✅ **Fork it and make it yours**
- ⚠️ Keep the copyright notice; provided "AS IS" without warranty
- 🚫 **Red lines are not licensed away**: this project contains no illegal tactics; if you use it for illegal/ToS-violating content, that's on you

---

*Educational content-marketing material, compiled from public reporting. Event details are subject to authoritative media and court rulings.*
