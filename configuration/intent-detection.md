---
layout: default
title: "Intent Detection for Ad Comments"
description: "How Rypl detects what each ad comment wants (a question, a purchase, a request, a complaint) and how to use it in replies, rules and filters."
last_modified_at: 2026-11-19
---

# Intent Detection

Intent detection reads every comment and message for what the person wants: information, to buy, something done, or to complain. Rypl gives each one an intent label and a sentiment, on **every plan**, with nothing to set up.

---

## The labels

Each comment in the [inbox](inbox.md) shows its intent:

**Question** · **Purchase** · **Request** · **Complaint** · **Feedback** · **Sharing** · **Spam** · **User-to-user**

- **Request** means the person wants you to do something: a refund, a return, an exchange, a cancellation, an order status.
- **Spam** covers ads for other shops, links, competitor mentions, self-promotion and bots. Someone calling you a scam is a **Complaint**, not Spam.
- **User-to-user** is people talking to each other, often with an @mention. Reply rules call it **Between users**.
- **Other** (greetings, a lone emoji) gets no label.

Every label is defined, with examples, in [Supported Intents](../reference/supported-intents.md).

Sentiment is **Positive**, **Neutral** or **Negative**. Comments can also be marked urgent; the dashboard counts them under **High priority**.

---

## What it drives by default

| Intent | What Rypl does by default |
|---|---|
| Question, Purchase, Request | The agent answers |
| Complaint | Answered if it asks something. If it only states a problem, it gets no reply and waits in Needs attention for a person |
| Spam | Never answered; hidden when your banned words, filters or rules catch it |
| Feedback (praise) | Answered only with thank-you replies switched on (Pro and Ultra) |
| User-to-user | Not answered, unless it asks a question |
| Sharing, Other | Left alone unless a reply rule says otherwise |

Legal threats and emergencies are never answered by the agent, even with a rule: they wait for a person.

---

## Using intent in reply rules (Pro and Ultra)

[Reply rules](reply-rules.md) take intent (shown as **Type**) and sentiment as conditions:

- *Type: Feedback · Sentiment: Positive* → **My text**: "Thanks for the love! 💜"
- *Type: Between users* → **Don't reply**
- *Type: Complaint* → **AI replies**, with instructions to apologise and give a next step

---

## Using intent to improve your ads

- **Many questions about the same thing** (sizes, shipping) mean the ad or landing page leaves it out.
- **Many complaints on one ad** often point to a promise the product doesn't keep.
- **Mostly spam on one ad** suggests switching on the **Spam & media filter** for that channel.
- In the Inbox, the **Intent** filter combined with **Channel** and **Time** shows what each audience asks most.
- On Pro and Ultra, an AI app connected through the [API and MCP server](api-and-mcp.md) can rank your ads by complaints or list the questions nobody answered.

---

## Next Steps

[Languages](multi-language.md).



## More on rypl.is

- [What do Rypl's intent labels mean?](https://www.rypl.is/docs/conversations/what-do-the-intent-labels-mean): every label, with examples
- [Which comments does the Rypl agent answer?](https://www.rypl.is/docs/reply-rules/which-comments-does-the-agent-answer): what gets a reply by default
- [How to Detect Buying Intent in Ad Comments (Before the Lead Walks)](https://www.rypl.is/blog/detect-buying-intent-ad-comments): the questions that signal a buyer
- [Ad Comment Statistics 2026: What People Write to Advertisers](https://www.rypl.is/blog/ad-comment-statistics-2026): what people write under ads, RYPL data for Q3 2026
- [Ad Comment Glossary: Moderation and Reply Terms](https://www.rypl.is/glossary): dark posts, hidden comments, Moderation Assist and other terms

---

[Back to Configuration](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
