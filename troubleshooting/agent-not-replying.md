---
layout: default
title: Agent Not Replying — Rypl Documentation
description: Why a Rypl AI agent isn't replying to Facebook, Instagram or TikTok comments, and how to fix it.
---

# Agent Not Replying

Work through these checks in order.

---

## 1. Is Reply with AI on for the channel?

Open **Channels**, pick the channel, then **AI replies**. **Reply with AI** must be on and an agent must be chosen. If the channel shows **AI is off on this channel**, switch it on.

## 2. Is the connection working?

If the account shows **Expired** or **Needs reconnect**, reconnect it. See [Connection troubleshooting](facebook-connection.md).

## 3. Is your plan active?

Check your subscription in **Settings**. If a payment failed, the account shows **Payment required**. See [Billing](billing.md).

## 4. Was the comment hidden?

Comments hidden by moderation don't get a reply. In the inbox, filter by **All hidden or deleted** to see whether the comment was hidden, and by what: your rules, banned words, the tone filter or you. A banned word that matches too broadly is the most common cause.

## 5. Was it sent to a person?

Comments matched by a rule set to **Flag for me** or **I'll answer myself**, and complaints, wait in **Needs attention** instead of getting an AI reply.

## 6. Is the agent set to reply there?

- **Where it replies**: *Comments only* skips DMs; *Messages only* skips comments.
- **How soon**: *Within an hour* or *Within a day* means the reply is scheduled, not missing.

## 7. Did a reply rule say Don't reply? (Pro and Ultra)

A **Don't reply** rule keeps the agent silent even on questions. The rule editor shows which recent comments each rule affects.

## 8. Is it a kind of comment the agent answers?

By default the agent answers questions, purchase signals and requests. It leaves greetings, a lone emoji and people tagging friends alone unless a reply rule tells it otherwise. Praise gets a reply when thank-you replies are on (Pro and Ultra).

## 9. Is it a DM older than 7 days?

Meta allows replies to a Facebook or Instagram DM only within 7 days of the person's last message.

## 10. Is it an organic TikTok post?

Rypl handles comments on TikTok **ads**. Organic TikTok posts are not supported.

---

## Replies go out but are vague

- The answer isn't in the [knowledge base](../configuration/knowledge-base.md). Add it as Q&A.
- A document couldn't be read (Rypl marks it "couldn't read this file"). Upload a text-based version.
- The instructions are too general. Add specific guidance and examples.
- Run **Suggest improvements** on the agent to find the questions it answers badly.

---

## Still not working?

Email [hey@rypl.is](mailto:hey@rypl.is) with your Rypl account email, the channel, a link to the comment and when it was posted.

---

[Back to Troubleshooting](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
