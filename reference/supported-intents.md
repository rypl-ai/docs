---
layout: default
title: "Supported Intents: Comment Labels"
description: "The intent labels Rypl puts on every comment and message: Question, Purchase, Request, Complaint, Feedback, Sharing, Spam and more, with examples."
last_modified_at: 2026-10-11
---

# Supported Intents

Rypl reads every comment and message for what the person wants and gives it one intent label, plus a sentiment (Positive, Neutral or Negative). Intent detection is on **every plan**. The labels appear in the [inbox](../configuration/inbox.md), and you can filter by them and use them in [reply rules](../configuration/reply-rules.md).

---

## The labels

| Intent | What it means | Examples |
|---|---|---|
| **Question** | Asks for information: price, availability, specs, how it works, where or how to get it | "How much?", "Does it come in XL?", "Do you ship to Spain?" |
| **Purchase** | Says outright they want to buy or order | "I'll take two", "How do I order? I want one" |
| **Request** | Asks you to do something: a return, refund, exchange, cancellation or order status check | "I want to return this", "Where is my order #1042?" |
| **Complaint** | Unhappy with your product, service, price or staff, without asking for a specific action | "Arrived broken", "Worst support ever" |
| **Feedback** | An opinion, suggestion or recommendation | "Love the new colours", "Too expensive for me", "You should make a smaller size" |
| **Sharing** | Tells a personal experience or circumstance without expecting a reply | "I've had mine for a year, still going strong" |
| **Spam** | Commercial spam, links to other shops, competitor mentions that send buyers elsewhere, self-promotion, bot text | "Cheaper at [another store]", "DM me for a better deal" |
| **User-to-user** | Commenters talking to each other, often starting with @name | "@Anna look, this is the one I told you about" |
| **Other** | Greetings, simple emojis, anything unrelated | "Hi", "🔥", "first" |

When a comment both asks you to act and something else, **Request** wins: "This arrived broken, I want a refund" is a Request, not a Complaint.

---

## How the labels are used

- **Replies.** Questions, purchase signals and requests are answered by default.
- **Needs attention.** Complaints and urgent comments wait for a person.
- **Moderation.** Spam is hidden automatically.
- **Reply rules** (Pro and Ultra). Use the label as a condition, for example "Type: Feedback, Sentiment: Positive → My text".
- **Inbox filters.** Filter conversations by intent and sentiment.

---

## What people write under ads

In [RYPL's Q3 2026 data](https://www.rypl.is/blog/ad-comment-statistics-2026), 40% of the comments RYPL's AI analyzed on advertisers' Facebook and Instagram ads and posts were questions, 38% showed buying intent (mostly questions about the product), and only 2% said outright that the person wanted to buy. Buying intent mostly arrives as a Question, not a Purchase.


## More on rypl.is

- [How to detect buying intent in ad comments](https://www.rypl.is/blog/detect-buying-intent-ad-comments): the questions that signal a buyer
- [Ad comment statistics 2026](https://www.rypl.is/blog/ad-comment-statistics-2026): what people write under ads, RYPL data for Q3 2026
- [Ad comment glossary](https://www.rypl.is/glossary): dark posts, hidden comments, Moderation Assist and other terms

---

[Back to Reference](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
