# OODA Subagents 🚀

AI agents that think like military strategists. 

## Quick Install

```bash
# Option 1: Git submodule
git submodule add https://github.com/al3rez/ooda-subagents.git .claude

# Option 2: Copy agents
git clone https://github.com/al3rez/ooda-subagents.git
cp -r ooda-subagents/.claude/agents <your-project>/.claude/
```

## What's OODA?

**Observe → Orient → Decide → Act**. A decision-making loop that turns chaos into clarity.

![OODA Loop in Action](ooda.png)

```
┌─────────────┐
│   OBSERVE   │ ← Gather info
└──────┬──────┘
       ▼
┌─────────────┐
│   ORIENT    │ ← Analyze patterns
└──────┬──────┘
       ▼
┌─────────────┐
│   DECIDE    │ ← Pick best path
└──────┬──────┘
       ▼
┌─────────────┐
│     ACT     │ ← Execute
└─────────────┘
```

## The Agents

### 🔍 Observe
Gathers info: reads files, searches code, finds patterns.

### 🧭 Orient  
Makes sense of data: spots connections, analyzes context.

### 🎯 Decide
Weighs options: evaluates trade-offs, recommends solutions.

### ⚡ Act
Executes: writes code, runs tests, ships features.

## Example

Debugging an auth issue:
1. **Observe**: Scans error logs and recent commits
2. **Orient**: Identifies race condition pattern
3. **Decide**: Recommends mutex locking strategy
4. **Act**: Implements fix and verifies

## Why OODA?

- Systematic problem-solving
- Faster delivery through structured thinking
- Nothing falls through cracks

---

## Built by [AstroMVP](https://astromvp.com) 🌟

We help early-stage startups build AI-first products that ship fast. OODA agents are how we deliver speed AND quality.

**What we do:**
- Build AI products that ship (not demos)
- Set up scalable dev processes
- Turn vision into working code

Got an AI product idea? Let's build → [astromvp.com](https://astromvp.com)
