---
layout: default
title: "Supported Intents: Comment Labels"
description: "The intent labels Rypl puts on every comment and message: Question, Purchase, Request, Complaint, Feedback, Sharing, Spam and more, with examples."
last_modified_at: 2026-11-19
---

# Supported Intents

Rypl reads every comment and message for what the person wants and gives it one intent label, plus a sentiment (Positive, Neutral or Negative). Intent detection is on **every plan**. The labels appear in the [inbox](../configuration/inbox.md), and on Pro and Ultra [reply rules](../configuration/reply-rules.md) can use them as a condition.

---

## The labels

| Intent | What it means | Examples |
|---|---|---|
| **Question** | Asks for information: price, availability, specs, how it works, where or how to get it | "How much?", "Does it come in XL?", "Do you ship to Spain?" |
| **Purchase** | Says outright they want to buy or order | "I'll take two", "How do I order? I want one" |
| **Request** | Asks you to do something: a return, refund, exchange, cancellation or order status check | "I want to return this", "Where is my order #1042?" |
| **Complaint** | Something went wrong, or they're unhappy with your product, service, price or staff, without asking for a specific action. Calling you a scam counts here, not as Spam | "Arrived broken", "This is a scam" |
| **Feedback** | An opinion, suggestion or recommendation | "Love the new colours", "Too expensive for me", "You should make a smaller size" |
| **Sharing** | Tells a personal experience or circumstance without expecting a reply | "I've had mine for a year, still going strong" |
| **Spam** | Commercial spam, links to other shops, competitor mentions or price comparisons that send buyers elsewhere, self-promotion, bot text | "Cheaper at [another store]", "DM me for a better deal" |
| **User-to-user** | Commenters talking to each other, often starting with @name. Reply rules call it **Between users** | "@Anna look, this is the one I told you about" |
| **Other** | Greetings, simple emojis, anything unrelated. It shows no label in the inbox | "Hi", "🔥", "first" |

When a comment both asks you to act and something else, **Request** wins: "This arrived broken, I want a refund" is a Request, not a Complaint.

---

## How the labels are used

- **Replies.** Questions, purchase signals and requests are answered by default. People talking to each other get no reply unless they ask a question.
- **Complaints.** A complaint that only states a problem gets no AI reply; if it asks something, the agent answers. Without a reply, it waits for a person in **Needs attention**.
- **Spam.** Never answered. Your banned words, rules and **Spam & media filter** hide it.
- **Messages.** In DMs (Messenger and Instagram Direct) the agent replies to every message apart from spam and negative complaints with no question in them.
- **Reply rules** (Pro and Ultra). Use the label as a condition on comments, for example "Type: Feedback, Sentiment: Positive → My text".
- **Inbox filters.** Filter by intent and sentiment (the intent filter leaves out User-to-user and Other).
- **API and MCP server** (Pro and Ultra). A connected app reads each comment's intent, sentiment, language and urgency, so you can ask it, for example, which ad draws the most complaints. See [API and MCP server](../configuration/api-and-mcp.md).

---

## What people write under ads

In [RYPL's Q3 2026 data](https://www.rypl.is/blog/ad-comment-statistics-2026), 40% of the comments RYPL's AI analyzed on advertisers' Facebook and Instagram ads and posts were questions, 38% showed buying intent (mostly questions about the product), and only 2% said outright that the person wanted to buy. Buying intent mostly arrives as a Question, not a Purchase. 3% accused the brand of a scam or said the product was fake. The figures are published under CC BY 4.0.


## More on rypl.is

- [What do Rypl's intent labels mean?](https://www.rypl.is/docs/conversations/what-do-the-intent-labels-mean): the labels in the help center
- [Which comments does the Rypl agent answer?](https://www.rypl.is/docs/reply-rules/which-comments-does-the-agent-answer): what gets a reply by default
- [How to detect buying intent in ad comments](https://www.rypl.is/blog/detect-buying-intent-ad-comments): the questions that signal a buyer
- [Ad comment statistics 2026](https://www.rypl.is/blog/ad-comment-statistics-2026): what people write under ads, RYPL data for Q3 2026
- [Ad comment glossary](https://www.rypl.is/glossary): dark posts, hidden comments, Moderation Assist and other terms

---

[Back to Reference](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
