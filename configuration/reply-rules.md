---
layout: default
title: "Reply Rules for AI Comment Replies"
description: "Reply rules in Rypl decide what happens to a kind of comment: the AI agent answers, your own text goes out, or the comment is skipped. Pro and Ultra."
last_modified_at: 2026-11-19
---

# Reply Rules

Reply rules change which comments the agent answers and what it says. A rule is a set of conditions that describe some comments, plus one action for them. You'll find them on the agent's **Replies** tab, in the **What it replies to** section. Each agent can have up to 20, on the **Pro** and **Ultra** plans.

By default the agent answers questions, purchases and requests. Rules add other kinds of comments (emoji reactions, praise, a giveaway keyword), or keep the agent silent on topics you never discuss in public.

---

## Conditions

Every condition you set has to fit for the rule to apply:

| Condition | Choices |
|---|---|
| **Content** | Any, Emoji only, Has text |
| **Is a question** | Yes, No |
| **Sentiment** | Positive, Neutral, Negative |
| **Type** | Intent: Question, Purchase, Request, Complaint, Feedback, Sharing, Spam, Between users, Other |
| **Contains any of** | A list of up to 50 words, one hit is enough |
| **But not** | Up to 50 words; if one appears, the rule is off for that comment |

## Actions

| Action | What happens |
|---|---|
| **AI replies** | The agent answers in its own words, from its instructions and knowledge base |
| **My text** | A reply you wrote is posted word for word, timed by **How soon**, with no AI involved. Write up to 10 variants and each comment gets one of them, so a busy thread doesn't repeat itself. Emoji and link settings are ignored |
| **Don't reply** | Nothing is posted, even for a question. Moderation runs as usual |

When rules conflict, **Don't reply** always wins, because those rules are checked before the rest. A wide rule such as "answer every positive comment" therefore can't pull the agent into a topic you've ruled out.

Rules work on comments only. In Messenger and Instagram DMs the agent replies to everything except spam and negative messages with no question in them, and its instructions decide what it says. No rule can make it answer a legal threat or an emergency: those are always left for a person.

---

## Ready-made rules

- **Emoji-only reactions**: comments that are just emoji, such as hearts or claps.
- **All positive comments.**
- **Never reply when**: silence for comments with words from your list.
- **Custom rule**: start from empty conditions.

## Examples

| Condition | Action | Why |
|---|---|---|
| Content emoji only, sentiment positive | My text: "🙏", "Thanks for the love! 💜" | Warm reactions get a quick response |
| Contains any of "GIVEAWAY" | My text with the entry link | A fixed answer for a campaign keyword |
| Contains any of "lawsuit", "lawyer" | Don't reply | Never discussed in public; a person handles it |
| Type Complaint | AI replies | An apology and a next step, in your voice |

---

## Thank-you replies

With **Praise and support** switched on under **What it replies to**, the agent writes a short thank-you under compliments that don't ask anything, like "Love this!" (Pro and Ultra). It keeps the thread active, and everyone who reads it later sees a brand that answers.

For a fixed thank-you instead, use **All positive comments** or **Emoji-only reactions** with **My text** and a few versions. Add **Is a question: No**, or a comment like "Gorgeous! What does it cost?" would get a thank-you instead of a price.

---

## Preview before you save

The editor's **On your recent comments** panel runs the rule over comments your channels already received, so you see what it would have answered and what it would have skipped.

---

## Suggestions for repeated comments

If one question keeps turning up, Rypl offers to turn it into a **My text** rule, so that answer is written once by you instead of by the AI each time.

---

## Can I approve replies before they go out?

No. AI replies are posted on the agent's **How soon** timing, without an approval step; **Review first** is a mode for moderation rules only. To control what goes out:

- a fixed answer to a frequent question: a **My text** rule;
- no reply on a topic: **Don't reply**, or a moderation rule set to **I'll answer myself**;
- everything answered by you: switch off **Replies** on the channel and reply from the Inbox.

Every AI reply can be checked afterwards in the Inbox, under **AI replies**, and edited or deleted on Facebook and TikTok.

---

## Next Steps

[Intent detection](intent-detection.md).


## More on rypl.is

- [How do reply rules work in Rypl?](https://www.rypl.is/docs/reply-rules/how-do-reply-rules-work): conditions, actions and ready-made rules
- [Which comments does the Rypl agent answer?](https://www.rypl.is/docs/reply-rules/which-comments-does-the-agent-answer): what gets a reply by default
- [How do thank-you replies work in Rypl?](https://www.rypl.is/docs/reply-rules/how-do-thank-you-replies-work): Praise and support
- [Can I approve Rypl's AI replies before they're posted?](https://www.rypl.is/docs/reply-rules/can-i-approve-replies-before-they-are-posted): the ways to control what goes out
- [How to Auto-Reply to Facebook Comments (2026)](https://www.rypl.is/guides/auto-reply-to-facebook-comments): Meta's own options and where AI replies fit
- [How to Auto-Reply to Instagram Comments (2026)](https://www.rypl.is/guides/auto-reply-to-instagram-comments): Instagram's own options and where AI replies fit
- [How to Auto-Reply to TikTok Ad Comments (2026)](https://www.rypl.is/guides/auto-reply-to-tiktok-ad-comments): what TikTok allows for ad comments
- [How to Detect Buying Intent in Ad Comments (Before the Lead Walks)](https://www.rypl.is/blog/detect-buying-intent-ad-comments): the questions that signal a buyer

---

[Back to Configuration](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
