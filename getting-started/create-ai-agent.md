---
layout: default
title: Create an AI Agent — Rypl Documentation
description: Step-by-step guide to creating and configuring your Rypl AI agent with brand voice, knowledge base, and moderation rules.
---

# Create an AI Agent

An AI agent is the core of Rypl. It reads your ad comments, understands intent, applies your brand voice, and replies using the knowledge you provide. This guide walks you through creating your first agent.

---

## What Is an AI Agent?

Each AI agent in Rypl is configured for a specific purpose — typically mapped to a Facebook Page or client. An agent has three main components:

1. **Brand Voice** — How the agent communicates (tone, style, personality)
2. **Knowledge Base** — What the agent knows (products, FAQs, policies)
3. **Moderation Rules** — What the agent filters (spam, negative comments, blocked keywords)

The number of agents you can create depends on your plan:

| Plan | Agents |
|------|--------|
| Simple | 2 |
| Pro | Unlimited |
| Ultra | Unlimited |

---

## Step-by-Step Agent Creation

### Step 1: Name Your Agent

Give your agent a descriptive name that helps you identify it later. For example: "Main Store Agent," "Client — Acme Co," or "Summer Campaign Bot."

### Step 2: Set the Brand Voice

Your brand voice determines how the AI writes replies. Configure:

- **Tone** — Friendly, professional, casual, formal, witty, or a custom combination
- **Style Guidelines** — Specific instructions like "Use short sentences," "Include emojis sparingly," or "Always mention free shipping"
- **Example Prompts** — Provide sample replies the agent can learn from to match your style

For a detailed guide on crafting the perfect brand voice, see [Brand Voice Configuration](../configuration/brand-voice.md).

### Step 3: Upload Your Knowledge Base

The knowledge base is what makes your AI agent truly useful. Without it, the agent can only give generic responses. With it, the agent can answer specific product questions, quote prices, explain policies, and more.

Rypl supports seven knowledge base source types:

| Source Type | Format | Best For |
|-------------|--------|----------|
| Product Catalog | PDF | Product specs, pricing, descriptions |
| FAQ Answers | CSV | Common questions and approved answers |
| Brand Voice | TXT | Tone guidelines, do's and don'ts |
| Website URLs | URL | Pulling content from your website |
| Database | Structured data | Inventory, pricing tables |
| User Comments | Historical data | Learning from past interactions |
| Conversation History | Chat logs | Understanding customer patterns |

Upload as many sources as you need. The more context your agent has, the better its replies will be. See [Knowledge Base Configuration](../configuration/knowledge-base.md) for format requirements and tips.

### Step 4: Configure Moderation Rules

Define what the agent should filter out automatically:

- **Spam Detection** — Enable automatic spam hiding (hidden in ~1.7 seconds)
- **Negative Comment Handling** — Choose to hide, flag for review, or respond diplomatically
- **Keyword Blocklists** — Add specific words or phrases that should trigger automatic hiding
- **Custom Rules** — Create rules based on patterns, user behavior, or comment content

See [Moderation Rules](../configuration/moderation-rules.md) for detailed configuration options.

### Step 5: Assign to a Facebook Page

Link your agent to one or more of your connected Facebook Pages. Each Page can have one active agent managing its comments.

### Step 6: Review and Save

Before saving, review all your settings:

- Is the brand voice appropriate for your audience?
- Does the knowledge base cover the most common customer questions?
- Are moderation rules strict enough to catch spam but lenient enough to keep genuine comments?

Save your agent configuration. You can edit any of these settings at any time.

---

## Tips for a Great Agent

- **Start with your FAQ** — If you have an FAQ page on your website, this is the fastest way to give your agent useful knowledge
- **Be specific in brand voice** — "Be friendly and helpful" is too vague. "Use short, upbeat sentences. Address the commenter by name when possible. Always mention our free 30-day return policy" is much better
- **Start with moderate moderation** — You can always tighten rules later. Starting too strict may hide legitimate comments
- **Test before going live** — Review the agent's configuration carefully before activating it

---

## Next Steps

Your agent is configured and ready. Proceed to [Go Live](go-live.md) to activate it and start automating your comment management.

---

[Back to Getting Started](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
