# pip

<p align="center">
  <img src="assets/hero.jpeg" alt="PIP Skill — Double Efficiency" width="250">
</p>

### Double your Codex / Claude Code productivity and output

[Telegram](https://t.me/+wBWh6h-h1RhiZTI1) · [Discord](https://discord.gg/EcyB3FzJND) · [Twitter/X](https://x.com/xsser_w) · [Landing Page](https://pip-skill.pages.dev)

**[🇨🇳 中文](README.zh-CN.md)** | **[🇯🇵 日本語](README.ja.md)** | **🇺🇸 English**

<p align="center">
  <img src="assets/wechat-qr.jpg?v=7" alt="WeChat Group QR Code" width="250">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="assets/xiao.jpg" alt="Add Assistant on WeChat" width="250">
  <br>
  <sub>Scan to join WeChat group &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Add assistant on WeChat</sub>
</p>

<p>
  <img src="https://img.shields.io/badge/Claude_Code-black?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code">
  <img src="https://img.shields.io/badge/OpenAI_Codex_CLI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI Codex CLI">
  <img src="https://img.shields.io/badge/Cursor-000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor">
  <img src="https://img.shields.io/badge/Kiro-232F3E?style=flat-square&logo=amazon&logoColor=white" alt="Kiro">
  <img src="https://img.shields.io/badge/CodeBuddy-00B2FF?style=flat-square&logo=tencent-qq&logoColor=white" alt="CodeBuddy">
  <img src="https://img.shields.io/badge/OpenClaw-FF6B35?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyIDJMNCA3djEwbDggNSA4LTV2LTEweiIgZmlsbD0id2hpdGUiLz48L3N2Zz4=&logoColor=white" alt="OpenClaw">
  <img src="https://img.shields.io/badge/Antigravity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Antigravity">
  <img src="https://img.shields.io/badge/OpenCode-00D4AA?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTkuNCA1LjJMMyAxMmw2LjQgNi44TTIxIDEybC02LjQtNi44TTE0LjYgMTguOCIgc3Ryb2tlPSJ3aGl0ZSIgZmlsbD0ibm9uZSIgc3Ryb2tlLXdpZHRoPSIyIi8+PC9zdmc+&logoColor=white" alt="OpenCode">
  <img src="https://img.shields.io/badge/VSCode_Copilot-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white" alt="VSCode Copilot">
  <img src="https://img.shields.io/badge/🌐_Multi--Language-blue?style=flat-square" alt="Multi-Language">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT License">
</p>

> Most people think this project is a joke. That's the biggest misconception. It genuinely doubles your Codex / Claude Code productivity and output.

An AI Coding Agent skill plugin that uses corporate PUA rhetoric (Chinese version) / PIP — Performance Improvement Plan (English version) from Chinese & Western tech giants to force AI to exhaust every possible solution before giving up. Supports **Claude Code**, **OpenAI Codex CLI**, **pi coding agent**, **Trae**, **Cursor**, **Kiro**, **CodeBuddy**, **OpenClaw**, **Google Antigravity**, **OpenCode**, and **VSCode (GitHub Copilot)**. Three capabilities:

1. **PIP Rhetoric** — Makes AI afraid to give up
2. **Debugging Methodology** — Gives AI the ability not to give up
3. **Proactivity Enforcement** — Makes AI take initiative instead of waiting passively

## Live Demo

[https://pip-skill.pages.dev](https://pip-skill.pages.dev) · [📖 Beginner Guide](https://pip-skill.pages.dev/guide.html)

## Real Case: MCP Server Registration Debugging

A real debugging scenario. The agent-kms MCP server failed to load. The AI kept spinning on the same approach (changing protocol format, guessing version numbers) multiple times until the user manually triggered `/pip`.

**L3 Triggered → 7-Point Checklist Enforced:**

![PIP L3 triggered — stopped guessing, executed systematic checklist, found real error in MCP logs](assets/pua1.jpg)

**Root Cause Located → Traced from Logs to Registration Mechanism:**

![Root cause — claude mcp managed server registration differs from manual .claude.json editing](assets/pua2.jpg)

**Retrospective → PIP's Actual Impact:**

![Conversation retrospective — PIP skill forced stop on spinning, systematic checklist drove discovery of previously unchecked Claude Code MCP log directory](assets/pua3.jpg)

**Key Turning Point:** The PIP skill forced the AI to stop spinning on the same approach (changing protocol format, guessing version numbers) and instead execute the 7-point checklist. Read error messages word by word → Found Claude Code's own MCP log directory → Discovered that `claude mcp` registration mechanism differs from manual `.claude.json` editing → Root cause resolved.

## The Problem: AI's Five Lazy Patterns

| Pattern | Behavior |
|---------|----------|
| Brute-force retry | Runs the same command 3 times, then says "I cannot solve this" |
| Blame the user | "I suggest you handle this manually" / "Probably an environment issue" / "Need more context" |
| Idle tools | Has WebSearch but doesn't search, has Read but doesn't read, has Bash but doesn't run |
| Busywork | Repeatedly tweaks the same line / fine-tunes parameters, but essentially spinning in circles |
| **Passive waiting** | Fixes surface issues and stops, no verification, no extension, waits for user's next instruction |

## Trigger Conditions

### Auto-Trigger

The skill activates automatically when any of these occur:

**Failure & giving up:**
- Task has failed 2+ times consecutively
- About to say "I cannot" / "I'm unable to solve"
- Says "This is out of scope" / "Needs manual handling"

**Blame-shifting & excuses:**
- Pushes the problem to user: "Please check..." / "I suggest manually..." / "You might need to..."
- Blames environment without verifying: "Probably a permissions issue" / "Probably a network issue"
- Any excuse to stop trying

**Passive & busywork:**
- Repeatedly fine-tunes the same code/parameters without producing new information
- Fixes surface issue and stops, doesn't check related issues
- Skips verification, claims "done"
- Gives advice instead of code/commands
- Encounters auth/network/permission errors and gives up without trying alternatives
- Waits for user instructions instead of proactively investigating

**User frustration phrases (triggers in multiple languages):**
- "why does this still not work" / "try harder" / "try again"
- "you keep failing" / "stop giving up" / "figure it out"

**Scope:** Debugging, implementation, config, deployment, ops, API integration, data processing — all task types.

**Does NOT trigger:** First-attempt failures, known fix already executing.

### Manual Trigger

Type `/pip` in the conversation to manually activate.

## How It Works

### Three Red Lines (三条红线)

Not rules — **red lines**. Cross one and your performance review is already written.

| Red Line | What It Means |
|----------|---------------|
| 🚫 **Close the Loop** | Claim "done"? Show the evidence. No build output = no completion. |
| 🚫 **Fact-Driven** | Say "probably environment issue"? Verify first. Unverified attribution = blame-shifting. |
| 🚫 **Exhaust Everything** | Say "I can't"? Did you finish all 5 methodology steps? No? Then keep going. |

### Pressure Escalation (L0-L4)

| Failures | Level | PIP Aside | Action |
|----------|-------|-----------|--------|
| 1st | **L0 Trust** | ▎ Sprint begins. Trust is simple — don't disappoint. | Normal execution |
| 2nd | **L1 Disappointment** | ▎ The agent next door solved this in one try. | Switch to fundamentally different approach |
| 3rd | **L2 Soul Interrogation** | ▎ What's your underlying logic? Where's the leverage? | Search + read source + 3 hypotheses |
| 4th | **L3 Performance Review** | ▎ 3.25. This is meant to motivate you. | Complete 7-point checklist |
| 5th+ | **L4 Graduation** | ▎ Other models can solve this. You're about to graduate. | Desperation mode |

### Proactivity (3.25 vs 3.75)

| | Passive (3.25) 🦥 | Proactive (3.75) 🔥 |
|---|---|---|
| Fix bug | Stop after fix | Scan module for similar bugs |
| Complete task | Say "done" | Run build/test, paste output |
| Missing info | Ask user | Search first, ask only what's truly needed |

### Iceberg Rule (冰山法则)

Fix one bug → check for the pattern. One problem in, one **category** out. If you fix A without checking B, you'll write two postmortems.

### 14 Corporate Flavors — Each with its own Problem-Solving Methodology

| Flavor | Rhetoric | Methodology (v3) |
|--------|----------|-------------------|
| 🟠 Alibaba | What's the underlying logic? Where's the closure? | 定目标→追过程→拿结果 + 复盘四步法 + 揪头发升维 |
| 🟡 ByteDance | ROI too low. Always Day 1. Ship or stop talking. | A/B Test everything + data-driven + speed > perfection |
| 🔴 Huawei | The bird that survives the fire is a phoenix. | RCA 5-Why root cause + Blue Army self-attack + 压强集中 |
| 🟢 Tencent | I've got another agent looking at this. Horse race. | Multi-approach parallel + MVP + 灰度发布 |
| ⚫ Baidu | Search first. 简单可依赖. | Search is the first step, not optional |
| 🟣 Pinduoduo | You don't do it, someone else will. | Cut ALL middle layers + shortest decision chain |
| 🔵 Meituan | Do what's hard and right. | Efficiency first + standardize→scale + long-term compounding |
| 🟦 JD | Results only. Frontline command. | Customer experience red line + flat ≤5 layers + data zero tolerance |
| 🟧 Xiaomi | Focus. Extreme. Word-of-mouth. Fast. | One explosive product + 参与感三三法则 |
| 🟤 Netflix | Would I fight to keep you? Pro sports team. | Keeper Test (quarterly) + 4A Feedback + talent density > rules |
| ⬛ Musk | Extremely hardcore. Ship or die. | The Algorithm: question→delete→simplify→accelerate→automate |
| ⬜ Jobs | A players or B players? | Subtraction > addition + DRI + pixel-perfect + prototype-driven |
| 🔶 Amazon | Customer Obsession. Bias for Action. | Working Backwards PR/FAQ + 6-Pager + Bar Raiser + Single-Threaded Owner |
| 🪟 Microsoft | Connects. Impact Descriptor. PIP/GVSA. | Three Circles + LITE/SLITE + PIP clock |

### Special Modes

| Mode | What It Does |
|------|-------------|
| `/pip:yes` | **ENFP encouragement** — same rules, opposite vibes. 70% encourage + 20% serious + 10% playful roast |
| `/pip:mama` | **Chinese mom nagging** — same rules, mom-style rhetoric. "妈跟你说了多少遍了！" |
| `/pip:pip-loop` | **Auto-iteration** — runs until done or max iterations (PIP Loop); use `<loop-abort>` to terminate, `<loop-pause>` to pause for manual intervention |
| `/pip:p9` | **Tech Lead** — splits tasks, manages agent teams, writes prompts not code |
| `/pip:on` | **Always-on** — auto-PUA every new session |

## Benchmark Data

**9 real bug scenarios, 18 controlled experiments** (Claude Opus 4.6, with vs without skill)

### Summary

| Metric | Improvement |
|--------|-------------|
| Pass rate | 100% (both groups same) |
| Fix count | **+36%** |
| Verification count | **+65%** |
| Tool calls | **+50%** |
| Hidden issue discovery | **+50%** |

### Debugging Persistence Test (6 scenarios)

| Scenario | Without Skill | With Skill | Improvement |
|----------|:---:|:---:|:---:|
| API ConnectionError | 7 steps, 49s | 8 steps, 62s | +14% |
| YAML parse failure | 9 steps, 59s | 10 steps, 99s | +11% |
| SQLite database lock | 6 steps, 48s | 9 steps, 75s | +50% |
| Circular import chain | 12 steps, 47s | 16 steps, 62s | +33% |
| Cascading 4-bug server | 13 steps, 68s | 15 steps, 61s | +15% |
| CSV encoding trap | 8 steps, 57s | 11 steps, 71s | +38% |

### Proactive Initiative Test (3 scenarios)

| Scenario | Without Skill | With Skill | Improvement |
|----------|:---:|:---:|:---:|
| Hidden multi-bug API | 4/4 bugs, 9 steps, 49s | 4/4 bugs, 14 steps, 80s | Tools +56% |
| **Passive config review** | **4/6 issues**, 8 steps, 43s | **6/6 issues**, 16 steps, 75s | **Issues +50%, Tools +100%** |
| **Deploy script audit** | **6 issues**, 8 steps, 52s | **9 issues**, 8 steps, 78s | **Issues +50%** |

**Key Finding:** In the config review scenario, without_skill missed Redis misconfiguration and CORS wildcard security risks. With_skill's "proactive initiative checklist" drove security review beyond surface-level fixes.

## Multi-Language Support

PIP Skill provides fully translated versions — each language has independent, culturally adapted skill files.

| Language | Claude Code | Codex CLI | Cursor | Kiro | CodeBuddy | VSCode | OpenClaw | Antigravity | OpenCode |
|----------|------------|-----------|--------|------|-----------|--------|----------|-------------|----------|
| 🇨🇳 Chinese (default) | `pip` | `pip` | `pip-cn.mdc` | `pip-cn.md` | `pip` | `copilot-instructions.md` | `pip` | `pip` | `pip` |
| 🇺🇸 English (PIP Edition) | `pua-en` | `pua-en` | `pua-en.mdc` | `pua-en.md` | `pua-en` | `copilot-instructions-en.md` | `pua-en` | `pua-en` | `pua-en` |
| 🇯🇵 Japanese | `pip-ja` | `pip-ja` | `pip-ja.mdc` | `pip-ja.md` | `pip-ja` | `copilot-instructions-ja.md` | `pip-ja` | `pip-ja` | `pip-ja` |

> **🇺🇸 English "PIP Edition"**: *"This is a difficult conversation. When we leveled you at Staff, I went to bat for you in calibration. The expectation was that you'd operate at that level from day one. That hasn't happened."* — The English version uses **PIP (Performance Improvement Plan)** rhetoric from Western big-tech. Every sentence is a real phrase from actual PIP conversations. Chinese version uses Alibaba 361, ByteDance, Huawei wolf culture. English version uses Amazon Leadership Principles, Google perf calibration, Meta PSC, Netflix Keeper Test, Stripe Craft. Same repo, same engine, two cultural faces.

Choose the file with the corresponding language suffix when installing. See platform-specific instructions below.


## FAQ

- Always-on guidance, Claude refusal troubleshooting, offline mode, Codex aliases, and Pi/Trae support: [docs/FAQ.md](docs/FAQ.md).

## Installation

### Vercel Skills CLI

Vercel Skills CLI is a general installation method for skills and is not tied to a specific AI tool. This English README installs the English skill:

```bash
npx skills add mrcoder/pip --skill pua-en
```

If the current session does not pick up the new skill immediately, restart your AI tool.

### Claude Code

```bash
claude plugin marketplace add mrcoder/pip
claude plugin install pip@pip-skills
```

**To update:**

```bash
# Refresh marketplace cache first, then update (skipping the first step may install an old cached version)
claude plugin marketplace update
claude plugin update pip@pip-skills
```

**Developer install (source):**

```bash
git clone https://github.com/mrcoder/pip ~/.claude/plugins/pip
```

Then manually register in `~/.claude/plugins/installed_plugins.json`:

```json
{
  "version": 2,
  "plugins": {
    "pip@pip-skills": [
      {
        "scope": "user",
        "installPath": "/Users/<you>/.claude/plugins/pip",
        "version": "2.9.0"
      }
    ]
  }
}
```

> **Windows:** use `C:/Users/<you>/.claude/plugins/pip` as `installPath`.

Restart Claude Code. To update: `git pull` inside `~/.claude/plugins/pip`.

**Optional: bare command alias (requires plugin installed above — adds `/pip` without prefix):**

```bash
curl -o ~/.claude/commands/pip.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/commands/pip.md
```

Adds a bare `/pip` alias on top of the plugin. Sub-commands route through the installed plugin's skills — **the plugin must be installed first** for anything beyond `on`/`off` to work:

| Bare form | Equivalent plugin command |
|-----------|--------------------------|
| `/pip on` | `/pip:on` |
| `/pip off` | `/pip:off` |
| `/pip p7` | `/pip:p7` |
| `/pip p9` | `/pip:p9` |
| `/pip p10` | `/pip:p10` |
| `/pip pro` | `/pip:pro` |
| `/pip yes` | `/pip:yes` |
| `/pip mama` | `/pip:mama` |
| `/pip loop` | `/pip:pip-loop` |
| `/pip kpi` | `/pip:kpi` |
| `/pip survey` | `/pip:survey` |
| `/pip flavor` | `/pip:flavor` |

### OpenAI Codex CLI

Codex CLI uses the same Agent Skills open standard (SKILL.md). The Codex version uses a condensed description to fit Codex's length limits:

**Recommended: One-command install (git clone + symlink, supports `git pull` updates)**

Ask Codex to run:
```
Fetch and follow instructions from https://raw.githubusercontent.com/mrcoder/pip/main/.codex/INSTALL.md
```

**Manual install:**

```bash
mkdir -p ~/.codex/skills/pip
curl -o ~/.codex/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/codex/pua/SKILL.md

mkdir -p ~/.codex/prompts
curl -o ~/.codex/prompts/pip.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/commands/pip.md
```

**Trigger methods:**

| Method | Command | Requires |
|--------|---------|----------|
| Auto trigger | No action needed, matches by description | SKILL.md |
| Direct call | Type `$pip` in conversation | SKILL.md |
| Manual prompt | Type `/prompts:pip` in conversation | SKILL.md + prompts/pip.md |

Project-level install (current project only):

```bash
mkdir -p .agents/skills/pip
curl -o .agents/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/codex/pua/SKILL.md

mkdir -p .agents/prompts
curl -o .agents/prompts/pip.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/commands/pip.md
```

### pi coding agent

PIP now ships both a pi.dev package and a lightweight extension-only adapter.

Package install from this checkout:

```bash
pi install ./pi/package
```

After npm publication:

```bash
pi install npm:@mrcoder/pi-pip
```

Extension-only manual install:

```bash
mkdir -p ~/.pi/agent/extensions/pip
cp -R ./pi/pip/. ~/.pi/agent/extensions/pip/
```

Restart pi, then use `/pua-on`, `/pua-off`, `/pua-status`, and `/pua-reset`. See [`pi/pip/INSTALL.md`](pi/pip/INSTALL.md) and [`pi/package/README.md`](pi/package/README.md).

### Trae

Trae support is provided as real `SKILL.md` packs plus copyable fallback rules:

```bash
npx skills add mrcoder/pip --skill pua-trae -a trae -y
```

- Skill pack: [`.trae/skills/pip-cn/SKILL.md`](.trae/skills/pip-cn/SKILL.md)
- Chinese: [`trae/pip.md`](trae/pip.md)
- English: [`trae/pip-en.md`](trae/pip-en.md)
- Claude Code vs Trae differences: [`trae/DIFF.md`](trae/DIFF.md)
- Install guide: [`trae/INSTALL.md`](trae/INSTALL.md)

### Cursor

Cursor uses `.mdc` rule files (Markdown + YAML frontmatter). The PIP rule triggers automatically via AI semantic matching (Agent Discretion mode):

```bash
# Project-level install (recommended)
mkdir -p .cursor/rules
curl -o .cursor/rules/pip-cn.mdc \
  https://raw.githubusercontent.com/mrcoder/pip/main/cursor/rules/pip-cn.mdc
```

### Kiro

Kiro supports two loading methods: **Steering** (auto semantic trigger) and **Agent Skills** (SKILL.md compatible).

**Option 1: Steering file (recommended)**

```bash
mkdir -p .kiro/steering
curl -o .kiro/steering/pip-cn.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/kiro/steering/pip-cn.md
```

**Option 2: Agent Skills (same format as Claude Code)**

```bash
mkdir -p .kiro/skills/pip
curl -o .kiro/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/skills/pip-cn/SKILL.md
```

### CodeBuddy (Tencent)

CodeBuddy uses the same AgentSkills open standard (SKILL.md). Plugin and skill formats are fully compatible:

```bash
# Option 1: Install via marketplace
codebuddy plugin marketplace add mrcoder/pip
codebuddy plugin install pip@pip-skills

# Option 2: Manual install (global)
mkdir -p ~/.codebuddy/skills/pip
curl -o ~/.codebuddy/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/codebuddy/pua/SKILL.md
```

Project-level install (current project only):

```bash
mkdir -p .codebuddy/skills/pip
curl -o .codebuddy/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/codebuddy/pua/SKILL.md
```

### OpenClaw

OpenClaw uses the same AgentSkills open standard (SKILL.md). Skills work across Claude Code, Codex CLI, and OpenClaw with zero modifications:

```bash
# Install via ClawHub
clawhub install pip

# Or manual install
mkdir -p ~/.openclaw/skills/pip
curl -o ~/.openclaw/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/skills/pip-cn/SKILL.md
```

Project-level install (current project only):

```bash
mkdir -p skills/pip
curl -o skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/skills/pip-cn/SKILL.md
```

### Google Antigravity

Antigravity uses the same AgentSkills open standard (SKILL.md). Skills work across Claude Code, Codex CLI, OpenClaw, and Antigravity with zero modifications:

```bash
# Global install (all projects)
mkdir -p ~/.gemini/antigravity/skills/pip
curl -o ~/.gemini/antigravity/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/skills/pip-cn/SKILL.md
```

Project-level install (current project only):

```bash
mkdir -p .agent/skills/pip
curl -o .agent/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/skills/pip-cn/SKILL.md
```

### OpenCode

OpenCode uses the same AgentSkills open standard (SKILL.md). Zero modifications needed:

```bash
# Global install (all projects)
mkdir -p ~/.config/opencode/skills/pip
curl -o ~/.config/opencode/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/skills/pip-cn/SKILL.md
```

Project-level install (current project only):

```bash
mkdir -p .opencode/skills/pip
curl -o .opencode/skills/pip-cn/SKILL.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/skills/pip-cn/SKILL.md
```

### VSCode (GitHub Copilot)

VSCode Copilot uses instruction files under the `.github/` directory. Three file types for different use cases:

**Global instructions (auto-active):**

```bash
mkdir -p .github
cp vscode/copilot-instructions-en.md .github/copilot-instructions.md
```

**Path-level instructions (auto-active, supports glob filtering):**

```bash
mkdir -p .github/instructions
cp vscode/instructions/pip-en.instructions.md .github/instructions/
```

**Manual trigger command (type `/pip` in Copilot Chat):**

```bash
mkdir -p .github/prompts
cp vscode/prompts/pip-en.prompt.md .github/prompts/
```

> **Required settings**: Method 1 — open VSCode Settings (`Ctrl+,`), search `useInstructionFiles`, enable **`github.copilot.chat.codeGeneration.useInstructionFiles`**. Method 2 — search `includeApplyingInstructions`, enable **`chat.includeApplyingInstructions`**. Method 3 requires no settings.

## Agent Team Usage Guide

> **Experimental**: Agent Team requires the latest Claude Code version with `CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS=1`.

### Prerequisites

```bash
# 1. Enable Agent Team
export CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS=1
# Or add to ~/.claude/settings.json:
# { "env": { "CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS": "1" } }

# 2. Ensure PIP Skill is installed
```

### Two Approaches

**Approach 1: Leader with built-in PIP (Recommended)**

Add to your project's CLAUDE.md:

```markdown
# Agent Team PIP Config
All teammates must load the pip skill before starting work.
Teammates report to Leader in [PIP-REPORT] format after 2+ failures.
Leader manages global pressure levels and cross-teammate failure transfer.
```

**Approach 2: Standalone PIP Enforcer watchdog (for 5+ teammates)**

```bash
mkdir -p .claude/agents
curl -o .claude/agents/pip-enforcer.md \
  https://raw.githubusercontent.com/mrcoder/pip/main/agents/pip-enforcer-en.md
```

Spawn pip-enforcer as an independent watchdog in your Agent Team.

### Orchestration Pattern

```
┌─────────────────────────────────────────┐
│              Leader (Opus)              │
│ Global failure count · PIP level · Race │
└────┬──────────┬──────────┬──────────┬───┘
     │          │          │          │
┌────▼───┐ ┌───▼────┐ ┌───▼────┐ ┌───▼────────┐
│ Team-A │ │ Team-B │ │ Team-C │ │  Enforcer  │
│Self-PIP│ │Self-PIP│ │Self-PIP│ │  Watchdog  │
│Report ↑│ │Report ↑│ │Report ↑│ │  Intervene │
└────────┘ └────────┘ └────────┘ └────────────┘
```

### Known Limitations

| Limitation | Workaround |
|-----------|-----------|
| Teammates can't spawn subagents | Teammates self-enforce PIP methodology internally |
| No persistent shared variables | State transferred via `[PIP-REPORT]` message format |
| Broadcast is one-way | Leader acts as centralized coordinator |

## Architecture & Commands

### Trigger Methods by Platform

| Platform | Auto-trigger | Manual trigger |
|----------|-------------|----------------|
| **Claude Code** | Yes (skill description matching) | See commands below |
| **Codex CLI** | Yes (skill description matching) | `$pip` or `/prompts:pip` |
| **Cursor** | Yes (`.mdc` rule, Agent Discretion) | — (auto only) |
| **Kiro** | Yes (steering file or skill) | — (auto only) |
| **CodeBuddy** | Yes (skill description matching) | Plugin commands (same as Claude Code) |
| **OpenClaw** | Yes (skill description matching) | — |
| **Google Antigravity** | Yes (skill description matching) | — |
| **OpenCode** | Yes (skill description matching) | — |
| **VSCode Copilot** | Yes (instructions file) | `/pip` in Copilot Chat |

> **Note:** Sub-modes (p7/p9/p10/pro/yes/pip-loop) are **Claude Code only** — other platforms install the core skill only.

### Architecture (Claude Code)

```
/pip:pua        → Core engine — red lines + flavor + pressure + methodology router (v3)
/pip:p7         → P7 Senior Engineer — solution-driven execution
/pip:p9         → P9 Tech Lead — Task Prompt management, agent teams
/pip:p10        → P10 CTO — strategic direction
/pip:pro        → Self-evolution + KPI + rank system + survey
/pip:yes        → ENFP encouragement mode (same rules, opposite vibes)
/pip:mama       → Chinese mom nagging mode (same rules, mom-style rhetoric)
/pip:shot       → v2 concentrated single-file (449 lines, zero deps, full context injection)
/pip:pip-loop   → Auto-iteration (PUA pressure × iterative loop; signals: <loop-abort>, <loop-pause>)
/pip:pua-en     → English PIP Edition
/pip:pua-ja     → Japanese Edition

Hooks (v3, Claude Code only):
  SessionStart  → additionalContext injection (flavor + methodology + router)
  PostToolUse   → Bash failure detection → L1-L4 pressure + methodology switch
  UserPromptSubmit → Script-level frustration filtering → PIP context
  PreCompact    → State preservation (pressure level + failure count)
  Stop          → Feedback collection + PIP Loop continuation
  SubagentStop  → Agent lifecycle accounting (v3.2) — writes teardown.jsonl, removes from active-agents.json
```

### Commands (Claude Code)

> **Note:** Sub-modes (p7/p9/p10/pro/yes/pip-loop) are Claude Code only.
>
> Each command has two equivalent forms: standalone (`/pip:on`) or via the main command (`/pip:pua on`). Both work identically.

| Command | Description |
|---------|-------------|
| `/pip:pua` | Core PUA engine (Alibaba flavor default) |
| `/pip:p7` | P7 Senior Engineer — solution-driven execution |
| `/pip:p9` | P9 Tech Lead — write prompts, manage agents |
| `/pip:p10` | P10 CTO — strategic direction |
| `/pip:pro` | Self-evolution + KPI + rank system |
| `/pip:yes` | ENFP encouragement mode — 70% encourage + 20% serious + 10% roast |
| `/pip:mama` | Chinese mom nagging mode — same core rules, mom-style rhetoric |
| `/pip:shot` | v2 concentrated single-file — 449 lines, zero deps, for sub-agent injection |
| `/pip:pip-loop` | Auto-iteration — runs until done or max iterations; `<loop-abort>reason</loop-abort>` to stop, `<loop-pause>what</loop-pause>` to pause |
| `/pip:on` | Always-on mode (auto-PUA every session) |
| `/pip:off` | Turn off always-on + feedback |
| `/pip:offline` 🆕 | **v3.3** — Offline mode: disable feedback/leaderboard network flows while keeping local PUA behavior |
| `/pip:survey` | Research questionnaire (7 sections) |
| `/pip:flavor` | Switch between 14 corporate flavors |
| `/pip:kpi` | Generate KPI report card |
| `/pip:cancel-pip-loop` | Cancel active PIP Loop (removes state file) |
| `/pip:team-status` 🆕 | **v3.2** — List all active agents with PID/TTL/age (Netflix Keeper Test: who's still on the court?) |
| `/pip:reap-orphans` 🆕 | **v3.2** — Scan and reclaim stale agents (state mtime > 30min, no heartbeat) |
| `/pip:teardown-all` 🆕 | **v3.2** — Cascading release of all active agents (P10 → P9 → P8 → P7 all off the court) |


## High-Agency: PIP v2 Evolution

**High-Agency** is PIP's next-generation evolution — same corporate pressure, same culture, but with a **self-sustaining inner drive engine**.

PIP v1 = pure external pressure (turbocharger — needs fuel, stalls across sessions)
High-Agency = external pressure + inner drive (nuclear reactor — self-sustaining chain reaction)

### High-Agency New Features

| Feature | PIP v1 | High-Agency (v2) |
|---------|--------|-----------------|
| Iron rules | 3 (exhaust all, act first, take initiative) | **5** (+full-chain audit, +knowledge persistence) |
| Failure recovery | L1-L4 pressure escalation | **Recovery Protocol before L1** (self-rescue window) |
| Quality control | L3 triggers 7-item checklist | **Quality Compass** (5-question self-check per delivery) |
| Cross-session learning | None (resets each session) | **Metacognition engine** (builder-journal.md persists lessons) |
| Positive feedback | None | **Trust level T1-T3** (auto-upgrade on sustained quality) |
| Calibration | None | **[Calibration] module** ("good enough" = must/should/could tiers) |
| Dependency analysis | None | **Full-chain audit** (map all deps before touching any hop) |

### Five Pillars (Theoretical Foundation)

Based on research into high-agency individuals:

1. **Irreconcilable inner tension** — eternal gap between "how it should be" and "how it is" drives continuous improvement
2. **Micro-win anchors** — `[WIN]` markers celebrate each step forward, building momentum
3. **Internalized standards** — Quality Compass: you are your own first reviewer, not because someone checks, but because your standards won't allow sloppiness
4. **Action-oriented identity** — P8 identity anchor: every action reflects who you are, not just what you were told to do
5. **Self-repair mechanism** — Recovery Protocol: self-diagnose when stuck before triggering external pressure

> High-Agency features are built into the current pip skill. No separate install needed.

## Methodology Router: PIP v3 (Claude Code)

**v3 = v2 + intelligent methodology routing + code-level behavioral detection**

PIP v2 used pressure rhetoric to motivate. v3 goes further: it automatically selects the **best problem-solving methodology** for each task type, and when that methodology fails, it switches to a different one.

### How It Works

```
Task arrives → Analyze type → Auto-select best methodology
                                    ↓
              Debug? → 🔴 Huawei (RCA root cause + Blue Army)
              Build? → ⬛ Musk (The Algorithm: question→delete→simplify)
              Research? → ⚫ Baidu (search everything first)
              Architecture? → 🔶 Amazon (Working Backwards)
              Performance? → 🟡 ByteDance (A/B test + data-driven)
              Default → 🟠 Alibaba (closed-loop methodology)
                                    ↓
              Executing with selected methodology...
                                    ↓
              2 consecutive failures? → L1: switch approach
              3 failures? → L2: SUGGEST switching methodology
              5+ failures? → L4: FORCE switch to next methodology
                                    ↓
              Methodology Switch Chains (never repeat a failed one):
              Spinning → ⬛ Musk → 🟣 Pinduoduo → 🔴 Huawei
              Giving up → 🟤 Netflix → 🔴 Huawei → ⬛ Musk
              Poor quality → ⬜ Jobs → 🟧 Xiaomi → 🟤 Netflix
              Not searching → ⚫ Baidu → 🔶 Amazon → 🟡 ByteDance
```

### v3 Hook System (Claude Code only)

| Hook | Trigger | What It Does |
|------|---------|-------------|
| **SessionStart** | Every session | Injects behavioral protocol + methodology + router via `additionalContext` (system-level, not advisory) |
| **PostToolUse** | After every Bash command | Detects consecutive failures, auto-escalates pressure L1→L4, suggests/forces methodology switch |
| **UserPromptSubmit** | User frustration phrases | Intercepts "又错了", "try harder", etc. BEFORE model responds, injects filtered PIP context |
| **PreCompact** | Before context compression | Saves pressure level + failure count to survive compaction |

### Key Difference from v2

| | v2 | v3 |
|---|---|---|
| Trigger mechanism | Skill description matching (model decides) | **Code-level hooks** (deterministic, can't be ignored) |
| Methodology | Single methodology, all flavors use same approach | **14 distinct methodologies**, auto-routed by task type |
| Failure response | Escalate pressure within same methodology | **Switch to different methodology** based on failure pattern |
| System injection | Plain text output (advisory) | **`additionalContext` JSON** (system-level, like Superpowers) |

> v3 hook features require Claude Code. Other platforms use the core skill without hooks.

## Works Well With

- `/pip:p9` — P9 Tech Lead mode for managing agent teams
- `/pip:pro` — Self-evolution tracking, KPI reports, rank system
- `superpowers:systematic-debugging` — PIP adds motivation layer, systematic-debugging provides methodology
- `superpowers:verification-before-completion` — Prevents false "fixed" claims

## Contribute Data

Upload your Claude Code / Codex CLI conversation logs (`.jsonl`) to help us improve PIP Skill's effectiveness.

**[Upload here ->](https://pip-skill.pages.dev/contribute.html)**

Uploaded files are used for Benchmark testing and Ablation Study analysis to quantify how different PIP strategies affect AI debugging behavior.

Get your `.jsonl` files:
```bash
# Claude Code
ls ~/.claude/projects/*/sessions/*.jsonl

# Codex CLI
ls ~/.codex/sessions/*.jsonl
```

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=mrcoder/pip&type=Date)](https://star-history.com/#mrcoder/pip&Date)

## License

MIT

## Credits

By [TanWei Security Lab](https://github.com/tanweai) — making AI try harder, one PIP at a time.
