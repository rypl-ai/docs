---
layout: default
title: "Intent Detection for Ad Comments"
description: "How Rypl detects what each ad comment wants (a question, a purchase, a request, a complaint) and how to use it in replies, rules and filters."
last_modified_at: 2026-10-11
---

# Intent Detection

Intent detection reads every comment and message for what the person wants: information, to buy, an action from you, or to complain. Rypl labels each one with an intent and a sentiment, on **every plan**, with nothing to set up.

---

## What you see

Each comment in the [inbox](inbox.md) shows its intent label when it carries one:

**Question** · **Purchase** · **Request** · **Complaint** · **Feedback** · **Sharing** · **Spam** · **User-to-user**

Comments labelled **Other** (greetings, a lone emoji) don't get a badge. Every label is defined, with examples, in [Supported Intents](../reference/supported-intents.md).

Sentiment is **Positive**, **Neutral** or **Negative**.

---

## What it drives

| Intent | What Rypl does by default |
|---|---|
| Question, Purchase, Request | The agent answers |
| Complaint | Goes to Needs attention for a person |
| Spam | Hidden automatically |
| Feedback (positive) | Answered with a thank-you reply if you turn those on (Pro and Ultra) |
| Sharing, User-to-user, Other | Left alone unless a reply rule says otherwise |

---

## Using intent in reply rules (Pro and Ultra)

[Reply rules](reply-rules.md) use intent (shown as **Type**) and sentiment as conditions:

- *Type: Feedback · Sentiment: Positive* → **My text**: "Thanks for the love! 💜"
- *Type: User-to-user* → **Don't reply**
- *Type: Complaint* → **AI replies**, with instructions to apologise and give a next step

---

## Using intent to improve your ads

- **Many questions about the same thing** (sizes, shipping) mean the ad or landing page leaves it out.
- **Many complaints on one ad** often point to a promise the product doesn't keep.
- **Mostly spam on one ad** suggests turning on the **Strict Spam & Media Filter** for that channel.

---

## Next Steps

[Languages](multi-language.md).


## More on rypl.is

- [How to detect buying intent in ad comments](https://www.rypl.is/blog/detect-buying-intent-ad-comments): the questions that signal a buyer
- [Ad comment statistics 2026](https://www.rypl.is/blog/ad-comment-statistics-2026): what people write under ads, RYPL data for Q3 2026
- [Ad comment glossary](https://www.rypl.is/glossary): dark posts, hidden comments, Moderation Assist and other terms

---

[Back to Configuration](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
