---
layout: default
title: "AI Models Behind Rypl"
description: "The AI behind Rypl's replies and moderation, what differs by plan, and why plans aren't tied to model names."
last_modified_at: 2026-11-19
---

# AI Models

[Rypl](https://www.rypl.is) runs on the latest OpenAI models and upgrades them automatically, on every plan. Plans are not tied to model names: a model name on a plan card would go out of date the next time the model improves, and you would have to change plans to get the better one.

---

## What differs by plan

| | Simple | Pro | Ultra |
|---|:--:|:--:|:--:|
| **Latest OpenAI models, upgraded automatically** | ✅ | ✅ | ✅ |
| **Most powerful AI**, for the toughest questions | — | — | ✅ |
| **Read the post** (image, video, copy) before replying | — | ✅ | ✅ |
| **Remember the conversation** | — | — | ✅ |

Everything else that uses AI is the same on every plan: intent detection, spam and hate detection, replies from your knowledge base, replies in the commenter's language, and **Suggest improvements**.

---

## What the AI does

- **Reads what each comment wants.** Every comment gets an intent label (a question, a purchase signal, a complaint, praise and more) and a sentiment. See [Supported Intents](supported-intents.md).
- **Spots spam and hate.** The AI flags spam in about 1.7 seconds on average, and the comment is hidden within seconds (RYPL's own measurement).
- **Writes replies in your brand voice** from your agent's instructions, tone and knowledge base, in the language the person wrote in, or in the language you set for the channel.
- **Looks at the post or ad** before replying, from Pro.
- **Follows moderation rules you write in plain words**, from Pro, so one rule catches every way of saying the same thing.
- **Remembers earlier messages** from the same person, on Ultra.
- **Suggests improvements.** It looks back over the agent's recent answers and the questions it had no answer for, then proposes Q&A entries and edits to the instructions; you add the ones you want.

## What it leaves to a person

- **Complaints that only state a problem.** They wait in **Needs attention** instead of getting an AI reply.
- **Legal threats and emergencies.** These always wait for a person, whatever your rules say.
- **Anything your rules hand to you**, with **Flag for me** or **I'll answer myself**.

---

## Same models, different answers

Agents on the same plan share the same models, but what each one says comes from that business's own instructions and knowledge base, so a shop and a clinic answer "how much?" very differently. Answers are only as good as the facts in your knowledge base: keep prices, stock and policies current, and read replies closely in your first week.

---

## Next Steps

- [Pricing](pricing.md): what each plan includes
- [Knowledge base](../configuration/knowledge-base.md): give the AI the facts it answers from
- [API and MCP server](../configuration/api-and-mcp.md): ask your own AI app, such as Claude Code or Cursor, about your comments (Pro and Ultra)
- [Sign up](https://app.rypl.is/signup): start a 7-day free trial


## More on rypl.is

- [How does Rypl write a reply?](https://www.rypl.is/docs/agents/how-does-rypl-write-a-reply): from reading the comment to posting the answer
- [How does Suggest improvements work in Rypl?](https://www.rypl.is/docs/agents/how-does-suggest-improvements-work): drafts of new Q&A and instruction changes
- [Why generic auto-replies hurt your brand](https://www.rypl.is/blog/context-aware-replies-explained): what context-aware replies change
- [AI vs rule-based comment automation](https://www.rypl.is/blog/ai-vs-rule-based-comment-automation): what actually works on Facebook

---

[Back to Reference](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
