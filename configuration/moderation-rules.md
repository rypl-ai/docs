---
layout: default
title: Moderation Rules — Rypl Documentation
description: Configure Rypl's automatic spam detection, negative comment handling, keyword blocklists, and custom moderation rules for Facebook ads.
---

# Moderation Rules

Rypl's moderation system protects your Facebook ad comments from spam, negative content, and irrelevant noise. Comments that match your moderation rules are hidden in approximately **1.7 seconds** — fast enough that most of your audience will never see them.

---

## How Moderation Works

When a new comment appears on your Facebook ad, Rypl processes it through your moderation rules before any other action:

1. **Comment arrives** on your ad post
2. **Moderation engine scans** the comment against all active rules
3. **If matched:** Comment is hidden from public view (~1.7 seconds)
4. **If clean:** Comment proceeds to intent detection and AI reply

Hidden comments are not deleted — they are simply made invisible to other users. The commenter can still see their own comment, and you can review and unhide comments from your dashboard at any time.

---

## Spam Detection

Rypl's built-in spam detection uses AI to identify common spam patterns:

- **Link spam** — Comments containing suspicious or irrelevant links
- **Bot comments** — Repetitive or template-generated content
- **Self-promotion** — Users promoting their own products or services in your ad comments
- **Scam content** — Phishing attempts, fake offers, or misleading claims
- **Emojis-only spam** — Comments consisting entirely of irrelevant emoji strings

Spam detection is enabled by default on all plans. On Pro and Ultra plans, you can configure the sensitivity level:

| Sensitivity | Behavior |
|-------------|----------|
| Low | Only hides obvious spam (links, known bot patterns) |
| Medium | Balanced detection — catches most spam with minimal false positives |
| High | Aggressive filtering — may occasionally hide borderline comments |

We recommend starting with **Medium** sensitivity and adjusting based on your experience.

---

## Negative Comment Handling

Not all negative comments are spam. Some are legitimate complaints or feedback that deserve a response. Rypl lets you configure how negative comments are handled:

### Hide Automatically

Comments with strong negative sentiment or profanity are hidden immediately. Best for high-volume ad campaigns where manual review is not practical.

### Flag for Review

Comments are marked in your dashboard with a flag but remain visible. You or your team can review them and decide whether to hide, reply, or escalate. Best for brands that want to address criticism publicly.

### Respond Diplomatically

The AI agent responds to the negative comment with an empathetic, solution-oriented reply. This shows other viewers that your brand cares about customer satisfaction. The comment remains visible along with your response.

### Hybrid Approach

Combine strategies: hide comments with profanity, flag moderate complaints for review, and auto-respond to mild criticism. You can configure these thresholds in your agent settings.

---

## Keyword Blocklists

Create lists of words or phrases that automatically trigger comment hiding:

### How to Set Up

1. Navigate to your agent's moderation settings
2. Open the keyword blocklist section
3. Add words or phrases, one per entry
4. Choose match type: exact match or contains
5. Save your blocklist

### Match Types

- **Exact match** — Only hides comments where the keyword appears as a standalone word. "scam" would match "this is a scam" but not "scammer."
- **Contains** — Hides comments where the keyword appears anywhere in the text. "scam" would match both "this is a scam" and "scammer."

### Common Blocklist Entries

Consider blocking:

- Competitor names (prevents competitor advertising in your comments)
- Profanity and slurs
- Spam trigger words ("DM me for," "check my page," "visit my profile")
- Scam-related terms
- Off-topic keywords irrelevant to your business

### Best Practices

- Start with a small blocklist and expand based on actual spam patterns
- Review hidden comments regularly to check for false positives
- Use exact match for short words to avoid over-filtering
- Use contains for longer phrases that are clearly problematic

---

## Custom Rules

Beyond spam detection and keyword blocklists, you can create custom moderation rules based on:

- **Comment length** — Hide extremely short comments (often spam) or excessively long ones
- **Repeated characters** — Flag comments with repeated characters or excessive capitalization
- **User behavior** — Configure actions for repeat offenders
- **URL patterns** — Block specific domains or URL patterns
- **Emoji patterns** — Filter comments that are purely emoji-based

---

## Reviewing Moderated Comments

All moderated comments are logged in your Rypl dashboard:

- View the original comment text
- See which rule triggered the moderation action
- Unhide comments that were incorrectly flagged (false positives)
- Adjust rules based on moderation patterns

Regular review of moderated comments helps you refine your rules over time and ensures legitimate customer comments are not being hidden accidentally.

---

## Next Steps

Learn about [Multi-Language Support](multi-language.md) to configure moderation for multilingual campaigns.

---

[Back to Configuration](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
