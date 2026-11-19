---
layout: default
title: "Comment Moderation: Filters and Rules"
description: "How Rypl hides spam, hate and unwanted comments on Facebook, Instagram and TikTok ads: banned words, filters, rules in plain words, author blocking."
last_modified_at: 2026-11-19
---

# Moderation

Rypl moderates comments on Facebook and Instagram ads and posts and on TikTok ads. At sign-up it sets up banned words, filters and rules from your business description, so spam and hate are hidden automatically; you can change every part. Spam is flagged in about 1.7 seconds on average and hidden within seconds (RYPL's own measurement). Counting the time Meta takes to deliver a comment, 94% of the Facebook comments Rypl hid were down within a minute of being posted (RYPL data, Q3 2026).

Moderation acts on comments, not on DMs, and every change applies to new comments after you save it.

**Hide or delete?** A hidden comment disappears from public view and its author isn't told: on Facebook the author and their friends still see it, on Instagram only the author. You can unhide it at any time. A deleted comment is gone for everyone and can't be restored. TikTok doesn't allow deleting other people's comments, so on TikTok, Delete becomes Hide. Hide by default, and keep Delete for scams, phishing links and personal data posted in public.

---

## How the layers fit together

| Layer | What it catches | Plans |
|---|---|---|
| **Banned words** | Exact words and phrases from your list; no AI involved | Every plan |
| **Moderation rules** | A kind of comment you describe in a sentence | Pro and Ultra |
| **Filter by tone** and **Spam & media filter** | Negative comments, links and media that slip past words and rules | Every plan |
| **Block author** | Whatever one person posts on a channel | Every plan |

Banned words and blocks come first, and no rule can overrule them. Three channel options also ignore your rules: **Hide all**, **Delete all** and the **Spam & media filter**. **Hide negative** and **Delete negative** are different: they leave alone any comment a rule has already matched.

---

## What's on every plan

### Banned words
Words and phrases you never want shown: competitor names, a rival's domain, slurs, a scam link. A comment containing one is hidden or deleted straight away.

- **Global list**: up to 50 words for every channel that uses Global rules, kept in the **Global rules** card at the top of **Channels**.
- **Channel list**: up to 50 more for a single channel, added under **Only on this channel** after you click its row.

You choose what each list does: **Hide**, **Delete** or **Off** (TikTok offers no Delete). Type the words separated by commas or Enter.

How a banned word matches:

| You type | It catches |
|---|---|
| `scam` | Any word that begins with "scam": *scam*, *scams*, *scammer* |
| `*scam*` | "scam" anywhere in the text, even inside a longer word |
| `"scam"` | The word *scam* on its own, nothing longer |

Banned words suit exact spellings. For anything people can phrase many ways, a moderation rule catches the meaning.

### Spam & media filter
A channel switch that hides comments with links, attachments or competitor mentions, photo-only comments included. Useful on ads that draw link spam. Click the channel's row and find it under **Moderation**.

### Filter by tone
For what banned words and rules don't catch. Set per channel: click the row and find it under **Moderation**. It saves at once.

| Option | What it does |
|---|---|
| **Off** (default) | Every comment stays up unless a rule or banned word catches it |
| **Hide negative** | Hides rude or angry comments |
| **Delete negative** | Deletes rude or angry comments. Can't be undone. Not on TikTok |
| **Hide all** | Hides every new comment, whatever it says |
| **Delete all** | Deletes every new comment. Can't be undone. Not on TikTok |

Rypl asks you to confirm **Hide all** and **Delete all**, and while either is on, banned words and the Spam & media filter switch off because they aren't needed.

Off is the default for a reason: a real complaint answered in public builds more trust than a thread with no criticism at all. Complaints go to **Needs attention** so a person answers them.

On a channel you add after sign-up, **Filter by tone** and the **Spam & media filter** start **Off**, so check them when you connect a new Page.

### Block author
In the Inbox, **Block author** in the conversation header hides that person's comments in the conversation and every new comment they post on that channel. It isn't a Facebook or TikTok ban: they aren't notified, they can keep commenting (and those comments are hidden), and they can still message you. **Unblock**, in the same place, lets new comments through again; comments hidden earlier stay hidden. Blocking needs an active plan.

---

## Moderation rules in plain words (Pro and Ultra)

A rule is one sentence, in any language, describing a kind of comment, plus the action Rypl takes when a comment fits it. Because the AI judges what a comment means rather than which words it uses, a single rule catches all the ways people phrase the same thing. Global rules hold up to 30, and each channel can add up to 30 of its own.

**Examples:**

- *Promotes another shop or links to one* → **Hide**
- *Mentions a refund, a late delivery or an order that never arrived* → **Flag for me**
- *Says we're a scam but gives no order details* → **Hide**
- *Asks about bulk or wholesale pricing* → **I'll answer myself**

### Actions

| Action | What happens |
|---|---|
| **Allow** | Shields the comment from the tone filter's negative options. It can't beat banned words, Hide all, Delete all, the Spam & media filter or a stricter rule |
| **Hide** | Taken out of public view without telling the author |
| **Delete** | Gone for good, for everyone. On TikTok it hides instead |
| **Flag for me** | Sent to Needs attention for you to decide |
| **I'll answer myself** | No AI reply; it goes to Needs attention so you can answer |

When more than one rule fits a comment, the toughest action applies, in this order: Delete, Hide, Flag for me, I'll answer myself, Allow.

Rules don't check photo- or video-only comments (the Spam & media filter handles those), DMs, or comments posted before you saved the rule.

### Global rules and channel rules

- **Global rules** sit in a card at the top of **Channels**. Inside it you write rules (**Quick add** offers ideas), pick the mode under **When a rule matches**, keep the global **Banned words**, and use **Used on** to leave out channels the rules don't suit. **Save global rules** applies the changes.
- **For a single channel**, click its row and look under **Moderation**: the **Global rules** switch takes that channel out of them entirely, **Choose which** skips individual rules or the banned words, and **Only on this channel** holds extra rules and words for it.

### Review first or Apply automatically

One setting covers all your rules, under **When a rule matches**:

- **Review first**: matches wait for your decision under **Needs review** instead of being acted on. Start new rules here to see what they catch.
- **Apply automatically**: each matching rule acts right away.

**Pause your rules**, at the bottom of the card, stops every rule on every channel without deleting any; the card then reads **Paused**. Banned words keep working.

On Simple you can keep rules, but they only start acting after a move to Pro or Ultra.

---

## Checking what was hidden

The [inbox](inbox.md) sidebar has a **Hidden or deleted** view that gives the reason for every removal, and the **Moderation** filter narrows the list to **Hidden by your rules**, **Hidden by banned words**, **Hidden by channel filters**, **Hidden by you**, **Deleted** or **From blocked authors**. Unhide anything hidden by mistake, then fix the word or rule that caught it.

On Pro and Ultra, a connected AI app can also tell you what was hidden and why, and, if you allow it, add or edit rules for you, never ones that delete. See [API and MCP server](api-and-mcp.md).

---

## Next Steps

[Reply rules](reply-rules.md).


## More on rypl.is

- [What does Rypl hide automatically?](https://www.rypl.is/docs/moderation/what-does-rypl-hide-automatically): the layers, and what each catches
- [How do moderation rules work in Rypl?](https://www.rypl.is/docs/moderation/how-do-moderation-rules-work): actions, modes and where to set rules
- [How do banned words work in Rypl?](https://www.rypl.is/docs/moderation/how-do-banned-words-work): global and per-channel lists
- [How does Filter by tone work in Rypl?](https://www.rypl.is/docs/moderation/how-does-filter-by-tone-work): the five options
- [How do I block a comment author in Rypl?](https://www.rypl.is/docs/moderation/how-do-i-block-an-author): blocking and unblocking
- [Should I hide or delete a comment?](https://www.rypl.is/docs/moderation/should-i-hide-or-delete-a-comment): when each makes sense
- [How to Hide Comments on Facebook Ads Automatically (2026)](https://www.rypl.is/blog/hide-comments-on-facebook-ads): where Meta's tools stop and rules in plain words take over
- [How to Stop Spam Comments on Facebook (2026)](https://www.rypl.is/guides/stop-spam-comments-on-facebook): Meta's filters and automatic hiding
- [How to Stop Spam Comments on Instagram (2026)](https://www.rypl.is/guides/stop-spam-comments-on-instagram): hidden words, limits and automatic hiding
- [How to Stop Spam Comments on TikTok Ads (2026)](https://www.rypl.is/guides/stop-spam-comments-on-tiktok-ads): blocked words, block user and hiding
- [How to Delete Comments on Facebook and Instagram (2026)](https://www.rypl.is/blog/delete-comments-on-facebook): what deleting does, and how hiding differs
- [Keyword Moderation: Auto-Filter Spam Before AI Even Sees It](https://www.rypl.is/blog/keyword-moderation-auto-filter-spam): banned words done right

---

[Back to Configuration](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
