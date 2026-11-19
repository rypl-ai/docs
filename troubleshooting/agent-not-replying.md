---
layout: default
title: "AI Agent Not Replying to Comments"
description: "Why a Rypl AI agent isn't replying to Facebook, Instagram or TikTok comments and DMs, and how to fix it."
last_modified_at: 2026-11-19
---

# Agent Not Replying

Work through these checks in order.

---

## 1. Is Replies on for the channel?

Open **Channels** and find the channel's row. It needs an agent (a row that reads **Choose agent** has none) and the **Replies** switch on. The switch saves at once.

## 2. Is the connection working?

A login marked **Login expired**, or a Page that says its access expired or that it's no longer shared with Rypl, needs reconnecting. See [Connection troubleshooting](facebook-connection.md).

## 3. Is your plan active?

A failed payment pauses replies and moderation at once, with **Payment required** in Settings. Rypl starts again when a new card goes through. See [Billing](billing.md).

## 4. Is Facebook limiting replies on the Page?

If Facebook restricts how a Page can comment, Rypl pauses AI comment replies there and the Page's row on **Channels** reads **Facebook is limiting replies**, with the time left. Messages still get answers. Click the line to see Facebook's reason. What helps:

- set **How soon** to *Within a few minutes* or slower, and reply to fewer comments;
- on Pro and Ultra, answer repeated questions with several **My text** versions in a reply rule, so the replies aren't identical;
- check recent replies for pushy or repeated wording, and link in fewer of them.

Replies resume on new comments when the restriction ends.

## 5. Was the comment hidden?

Comments hidden by moderation don't get a reply. Open **Hidden or deleted** in the inbox to see whether the comment is there, and what hid it: your rules, banned words, a channel filter or you. A banned word that matches too broadly is the most common cause.

## 6. Was it handed to a person?

A match for a moderation rule with the action **Flag for me** or **I'll answer myself** keeps the agent quiet, and while your rules are in **Review first**, Hide and Delete matches wait for you too. Look in **Needs attention**.

## 7. Is the agent set to reply there?

- **Replies to**: *Comments only* leaves DMs to you; *Messages only* leaves comments to you.
- **How soon**: anything other than *Immediately* delays the reply, from about a minute up to several hours.

## 8. Did a reply rule say Don't reply? (Pro and Ultra)

A **Don't reply** rule keeps the agent silent even on questions, and wins over other reply rules. The rule's preview shows which recent comments it affects.

## 9. Is it a kind of comment the agent answers?

By default the agent answers questions, purchase signals and requests.

- A complaint that only describes a problem waits for a person in **Needs attention**; one that asks something gets an answer.
- Praise gets a reply only with thank-you replies (**Praise and support**) on, on Pro and Ultra.
- People talking to each other are left alone unless they ask a question.
- Legal threats and emergencies always wait for a person, whatever your rules say.

## 10. Is it a DM older than 24 hours?

Meta gives the agent 24 hours from the person's last message to answer a Facebook or Instagram DM. Past that, someone on your team can still reply from the inbox for up to 7 days, provided your connection has Meta's Human Agent permission.

## 11. Does another app own your Instagram DMs?

If a chatbot or helpdesk connected to your Instagram is the default app for DMs, Rypl leaves those conversations to it, and the Page's row on **Channels** says Instagram DMs go to another app. Comments and Messenger aren't affected. See [Instagram DMs go to another app](facebook-connection.md#instagram-dms-go-to-another-app).

## 12. Was the comment posted before Rypl could see it?

Rypl answers comments that arrive after you connect a channel and switch it on. Comments posted earlier, or while a payment had failed, the channel was disconnected or Facebook restricted the Page, aren't answered later.

## 13. A few more cases

- **The test comment came from the Page itself.** Post test comments from a personal profile.
- **Someone already replied** to the comment.
- **The ad runs on a post owned by a different Page.** Rypl replies on whichever Page owns the post behind the ad.
- **It's on TikTok outside an ad.** Rypl handles comments on TikTok **ads** only; organic TikTok posts and TikTok messages aren't supported.

---

## Replies go out but are vague

- The answer isn't in the [knowledge base](../configuration/knowledge-base.md). Add it as Q&A.
- A document couldn't be read (Rypl marks it "couldn't read this file"). Upload a text-based version.
- The instructions are too general. Add specific guidance and examples.
- Run **Suggest improvements** on the agent to find the questions it couldn't answer.

---

## Still not working?

Email [hey@rypl.is](mailto:hey@rypl.is) with your Rypl account email, the channel, a link to the comment and when it was posted.


## More on rypl.is

- [Why isn't my Rypl agent replying?](https://www.rypl.is/docs/troubleshooting/why-isnt-my-agent-replying): the checks in the help center
- [Which comments does the Rypl agent answer?](https://www.rypl.is/docs/reply-rules/which-comments-does-the-agent-answer): what gets a reply by default
- [Why are replies paused on my Facebook Page in Rypl?](https://www.rypl.is/docs/troubleshooting/why-are-replies-paused-on-my-page): Facebook's reasons and what helps
- [Why can't Rypl reply to Instagram DMs?](https://www.rypl.is/docs/troubleshooting/why-cant-rypl-reply-to-instagram-dms): when another app owns the conversation
- [How to auto-reply to Facebook comments](https://www.rypl.is/guides/auto-reply-to-facebook-comments): Meta's own options and where AI replies fit
- [How to see and reply to comments on Facebook ads](https://www.rypl.is/blog/how-to-see-comments-on-facebook-ads): find every ad comment, dark posts included
- [How to auto-reply to Instagram comments](https://www.rypl.is/guides/auto-reply-to-instagram-comments): Instagram's own options and where AI replies fit

---

[Back to Troubleshooting](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
