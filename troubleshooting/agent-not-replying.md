---
layout: default
title: Agent Not Replying — Rypl Documentation
description: Troubleshooting guide for when your Rypl AI agent is not replying to Facebook ad comments. Complete diagnostic checklist.
---

# Agent Not Replying

Your AI agent is set up but comments are going unanswered? This guide walks through every potential cause and how to fix it.

---

## Quick Diagnostic Checklist

Run through these checks in order. Each step addresses the most common causes first:

### 1. Is the Agent Active?

**Check:** Open your Rypl dashboard and verify the agent status shows "Active."

**If inactive:** Toggle the agent to active. An inactive agent does not process any comments.

**If it was deactivated unexpectedly:** Check if your trial has expired or if there is a billing issue (see [Billing Troubleshooting](billing.md)).

---

### 2. Is the Facebook Page Connected?

**Check:** Go to your account settings and verify the Facebook Page shows a connected/active status.

**If disconnected:** Reconnect the Page through the OAuth flow. See [Facebook Connection Troubleshooting](facebook-connection.md) for guidance.

**If showing an error:** The most common cause is an expired API token. Click reconnect or re-authenticate to refresh the connection.

---

### 3. Is the Agent Assigned to the Right Page?

**Check:** Verify that the active agent is assigned to the Facebook Page where comments are appearing.

**If unassigned:** Assign the agent to the correct Page in the agent settings.

**Common mistake:** If you manage multiple Pages, the agent might be assigned to a different Page than the one receiving comments.

---

### 4. Is Your Plan Active?

**Check:** Verify your subscription status in the billing section.

**If trial expired:** Your 7-day trial may have ended without a paid subscription. Subscribe to a plan to reactivate your agent.

**If payment failed:** A failed payment can pause your account. Update your payment method in the Lemon Squeezy billing portal.

---

### 5. Are Moderation Rules Blocking Replies?

**Check:** Review your moderation rules and recent moderation logs.

**Possible issue:** Overly aggressive moderation rules might be hiding comments before the AI has a chance to reply. If comments are being hidden, the agent will not generate replies for them.

**Fix:** Reduce moderation sensitivity or review your keyword blocklist for terms that might match legitimate comments. Check the moderation log to see if the comments you expected replies on were hidden instead.

---

### 6. Is the Knowledge Base Uploaded? (Pro and Ultra)

**Check:** On Pro and Ultra plans, verify that your knowledge base has been uploaded and processed.

**Possible issue:** If the knowledge base is empty or failed to process, the agent may struggle to generate meaningful replies and may not respond at all.

**Fix:** Upload or re-upload your knowledge base sources. Check for processing errors in the knowledge base section of your dashboard.

---

### 7. Are Comments on Ads (Not Organic Posts)?

**Check:** Verify that the comments you expect replies on are on ad posts, not organic Page posts.

**Note:** Rypl is designed for Facebook ad comment management. Depending on your configuration, it may not reply to comments on organic (non-promoted) posts.

---

### 8. Is There a Delay?

**Normal behavior:** AI replies are generated in under 60 seconds, but occasionally processing may take slightly longer during high-traffic periods.

**If delays are consistent:** Check if you are on the Simple plan during peak hours. Pro and Ultra plans have fast queue priority for faster processing.

---

## Specific Scenarios

### Agent Was Working but Stopped

If your agent was replying successfully but has stopped:

1. **Check for token expiration** — Facebook API tokens expire. Reconnect your Page.
2. **Check billing status** — A failed payment can pause your account.
3. **Check for Facebook changes** — If you changed your Facebook password, enabled 2FA, or modified Page roles, tokens may have been invalidated.
4. **Check for moderation rule changes** — Recent changes to moderation rules might be hiding comments that previously received replies.

### Some Comments Get Replies, Others Do Not

If replies are inconsistent:

1. **Check moderation rules** — Some comments may be triggering moderation (hidden) while others pass through
2. **Check comment content** — Very short comments (single emoji, ".", etc.) may not trigger a reply
3. **Check for duplicate comments** — If multiple identical comments appear, the agent may reply to one and skip duplicates
4. **Check language** — While all languages are supported, some edge cases in rare scripts might need review

### Replies Are Posting but Are Generic

If replies are being posted but lack specific product information:

1. **Knowledge base issue (Pro/Ultra)** — Your knowledge base may not contain the information needed to answer specific questions. Update your knowledge base with relevant product details.
2. **Brand voice too vague** — If your brand voice configuration is too general, replies will be generic. Add specific examples and guidelines.
3. **Plan limitation (Simple)** — The Simple plan uses GPT-4 mini without knowledge base integration. Context-aware replies require the Pro or Ultra plan.

---

## Testing Your Agent

To verify your agent is working:

1. **Post a test comment** on one of your active Facebook ads
2. **Wait 60 seconds** for the AI reply to appear
3. **Check the Rypl dashboard** to see if the comment was detected and processed
4. **Review the reply** for quality and accuracy

If the test comment does not appear in the Rypl dashboard, the issue is likely with the Facebook Page connection. If it appears but no reply is generated, the issue is with the agent configuration.

---

## Still Not Working?

If you have worked through every step above and your agent is still not replying:

- Email [hey@rypl.is](mailto:hey@rypl.is) with:
  - Your Rypl account email
  - The affected Facebook Page name
  - When the issue started
  - Which diagnostic steps you have completed
  - Any error messages from the dashboard

---

[Back to Troubleshooting](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
