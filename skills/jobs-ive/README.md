# jobs-ive

A Steve Jobs in your pocket. For the agentic ones.

You know that moment when you're staring at your product and something feels off, but you can't name it? Too many options. Too much copy. A pricing page that looks like a spreadsheet. You need someone to walk in and say *"this is garbage, here's what it should be"* with frightening clarity.

That's this skill.

## Install

```bash
npx skills add openclaw-rocks/skills --skill jobs-ive
```

Works with Claude Code, Cursor, GitHub Copilot, Gemini CLI, and [27+ other agents](https://agentskills.io).

## What it does

Turns your AI agent into a product thinker trained on the Jobs/Ive philosophy. Not a fanboy impression. A decision engine.

Your agent gets seven battle-tested protocols:

| Protocol | What it does |
|----------|-------------|
| **Simplify** | Remove half. Then remove half again. Obsess over what remains. |
| **Name** | Short. Evocative. Inevitable. No descriptors needed. |
| **Write Copy** | One idea. Benefits, not features. No hedging. |
| **Design** | Honest materials. Invisible details finished. Technology disappears. |
| **Kill** | Draw the grid. Everything outside it dies. |
| **Price** | Simple enough to remember. Decides for the customer. |
| **Present** | Problem, hero, rule of three, live demo, one more thing. |

Plus a built-in bullshit detector that rejects "flexible," "customizable," feature comparison matrices, and anything requiring an asterisk.

## When to use it

- You're naming a product and every option sounds like a SaaS from 2019
- Your landing page says twelve things instead of one
- The pricing page has a toggle, three tiers, and a "contact us" escape hatch
- You're designing an interface and it feels busy but you don't know what to cut
- You need to kill a feature and want permission from someone decisive
- You're writing a launch announcement and it reads like a changelog
- You're about to present and your deck has 47 slides

## Example prompts

```
Simplify this pricing page. Apply the Jobs/Ive protocols.

Name this product. It's a background job runner for serverless functions.

Review this landing page copy. Be Steve about it.

I need to cut our product from 6 features to 3. Help me decide.

Write the launch announcement for our new CLI tool. One big idea.

This onboarding flow has 8 steps. Make it feel inevitable.
```

## What's inside

```
jobs-ive/
├── SKILL.md                          # The decision engine
└── references/
    ├── philosophy.md                 # Jobs + Ive worldview, core principles
    ├── design-principles.md          # Ive's 7 principles, Rams' 10 tenets
    └── messaging.md                  # Apple copy playbook, naming, keynotes
```

The skill loads `SKILL.md` as the primary instruction set. Reference files give the agent deep context on specific domains when it needs to go deeper.

## The Three Laws

Every decision runs through three filters:

1. **Is it essential?** Remove until something breaks. Add back exactly one thing.
2. **Is it human?** Not "5GB storage with FireWire." Say "1,000 songs in your pocket."
3. **Does it feel inevitable?** If people can easily imagine an alternative, it's not done.

## Built by

[OpenClaw.rocks](https://openclaw.rocks) builds the simplest way to host AI agents. One-click deployment to EU infrastructure, zero platform fees.

---

*Here's to the ones who ship at 2am. Who delete more than they write. Who know that saying no to a thousand things is the price of saying yes to one.*
