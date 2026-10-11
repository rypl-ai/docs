---
layout: default
title: Reply Rules — Rypl Documentation
description: Reply rules in Rypl decide what happens to a kind of comment: the AI agent answers, a ready reply goes out, or the comment is skipped. Pro and Ultra.
---

# Reply Rules

Reply rules decide what happens to a kind of comment once Rypl knows what it is. Each rule reads *When a comment…* (a condition) *Then…* (an action). Reply rules are on the **Pro** and **Ultra** plans and live on the agent.

Questions, purchase signals and requests are answered by default. Rules add other kinds of comments (emoji reactions, praise, a giveaway keyword), or keep the agent silent on topics you never discuss in public.

---

## Conditions

A rule can match on any combination of:

| Condition | Options |
|---|---|
| **Type** | Question, Complaint, Request, Sharing, Feedback, Purchase, Spam, Between users, Other |
| **Sentiment** | Positive, Neutral, Negative |
| **Is a question** | Yes or no |
| **Content** | Emoji only, or has text |
| **Contains any of** | Matches if any of the words is in the comment |
| **But not** | The rule doesn't apply if any of these words is in the comment |

## Actions

| Action | What happens |
|---|---|
| **AI replies** | The agent writes a reply, following its instructions and knowledge base |
| **My text** | A reply you wrote goes out as is, without the AI. Add several replies and Rypl varies them, so the thread doesn't fill with identical answers |
| **Don't reply** | Stays silent, even if the comment is a question. Moderation still runs |

**Don't reply** wins over every other rule, so a broad rule like "answer all positive comments" never overrides a topic you told the agent to stay out of.

Reply rules apply to comments. Direct messages follow the agent's instructions.

---

## Examples

| Condition | Action | Why |
|---|---|---|
| Content emoji only, sentiment positive | My text: "🙏", "Thanks for the love! 💜" | Warm reactions get a quick response |
| Contains any of "GIVEAWAY" | My text with the entry link | A fixed answer for a campaign keyword |
| Contains any of "lawsuit", "lawyer" | Don't reply | Never discussed in public; a person handles it |
| Type Complaint | AI replies | An apology and a next step, in your voice |

---

## Thank-you replies

**Thank-you replies** (Pro and Ultra) answer praise like "love this!" with a short, on-brand reply. They keep the thread active, and every later viewer sees a brand that responds.

---

## Rule suggestions

Above the agent's settings, Rypl suggests rules for what your current rules miss: complaints that got no answer, the same question asked again and again (a ready reply answers it the same way every time), and emoji reactions. Click a suggestion to open it as a draft; you decide whether to add it.

---

## Preview before you save

The rule editor shows how a rule would treat your recent comments (**On your recent comments**), so you see what will be answered before you save it.

---

## Next Steps

[Intent detection](intent-detection.md).

---

[Back to Configuration](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
