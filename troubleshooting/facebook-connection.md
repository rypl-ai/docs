---
layout: default
title: "Fix Facebook, Instagram and TikTok Connection"
description: "Fix connecting Facebook Pages, Instagram accounts and TikTok ad accounts to Rypl: missing Pages, expired logins, Instagram DMs owned by another app."
last_modified_at: 2026-11-23
---

# Connection Troubleshooting

---

## A Facebook Page doesn't appear

1. **Check the Pages you ticked.** If you left the Page unticked in Facebook's window, open **Channels**, choose **Add or remove Pages** in the login's **⋯** menu and tick it. Keep your other Pages ticked: an unticked Page drops off.
2. **Check the profile you signed in with.** It must manage the Page. If you manage Pages from more than one Facebook profile, connect the one that manages this Page with **Connect channel**.
3. **Try Business profile.** If the Page belongs to a Meta Business portfolio, connect with **Business profile**; what counts is your access to the Page inside that portfolio.
4. **Check your plan.** "You've reached your account limit" means your plan's accounts are all in use; see [Pricing](../reference/pricing.md).

---

## "Facebook permissions declined"

Rypl needs every permission it asks for to read comments and messages, reply, and hide or delete comments. If one was unticked, Rypl shows "Facebook permissions declined" or "Missing required permission(s)". Run the connection again and leave every permission ticked. Rypl can't see your ad budgets or payment methods through them.

---

## "Login expired" or "Needs reconnect"

Facebook and TikTok sometimes cut a login off, for example after a password change, when you lose your role on the Page or in the Business portfolio, or when Rypl's access is removed in your Facebook or TikTok settings. Rypl then can't read or answer comments on those channels. What you see on **Channels**:

| Label | What to do |
|---|---|
| **Login expired** next to a login, and its channels stopped | Click **Reconnect** and sign in again |
| A Page whose access expired | Click **Reconnect** on that Page's row |
| **No longer shared with RYPL** on a Page | Reconnect and tick the Page in Facebook's window |
| **Turned off** on a login | The login was connected at sign-up, but no plan was started within 3 days. Starting a plan switches it back on without reconnecting |
| **Moved to another RYPL account** | The same login was connected in a different Rypl account. If it belongs here, connect it again |

To list every channel with a problem, set the **Status** filter on **Channels** to **Needs reconnect**. Your settings, agents and rules stay as they are, but comments posted while a channel was disconnected aren't answered later.

Connections made with **Business profile** go through your Business portfolio and avoid most re-logins. A Page connected earlier with **Personal profile** stays on that login even if you connect it again with **Business profile**. To move it, remove the old login first (**⋯** → **Remove this login**), which also erases its history in Rypl.

---

## The Instagram account doesn't appear

- It must be a **professional** (business or creator) account.
- It must be **linked to the Facebook Page** you connected, in Meta Business Suite.
- Once it's linked, use **Reconnect** from the login's **⋯** menu on **Channels**.

The Instagram account then shows under the Page's name and uses the Page's agent and settings.

---

## Instagram DMs go to another app

Meta allows a single app to control each Instagram conversation. If a chatbot, a helpdesk or another app linked to your Instagram is set as the default for DMs, Rypl leaves those conversations to it. The Page's row on **Channels** then shows an orange line, **Instagram DMs go to another app**. Instagram comments and Messenger aren't affected.

Click the line and choose one way out:

- **Keep the other app for DMs.** Rypl stops trying to answer that Instagram account's DMs, and everything else stays as it is. The same choice is **Instagram DMs** → **Leave to another app** in the channel's **Replies** settings. Don't use the agent's **Replies to** for this: it would stop DMs on every channel that agent serves.
- **Make Rypl the default app.** As an admin of the linked Facebook Page, open the Page's settings on Facebook, then **Instagram conversation routing**, choose Rypl as the default routing app, allow it to take control of conversations, and save.
- **Take over (beta).** Rypl pulls each conversation away from the other app just before replying. This works only if the Page lets Rypl take control of conversations; otherwise the line reads **Facebook won't hand over Instagram DMs**. If the other app's DM automation stays on, customers may get answers from both.

A reply you send yourself from the inbox takes the conversation over too, as long as the Page allows it.

---

## TikTok problems

| What you see | What to do |
|---|---|
| "TikTok connection was cancelled or required permissions were not granted." | Connect TikTok again and allow every permission it asks for |
| The TikTok login expired or Rypl's access was revoked | Reconnect it from **Channels** |
| An ad account is missing | Connect TikTok again with a login that has access to the ad account, and authorize Rypl for it |
| **TikTok is still reviewing this ad account** | Wait for TikTok to approve the ad account |
| **Not active in TikTok Ads** | Check the ad account in TikTok Ads Manager |

Comments on your own TikTok posts come through a separate **TikTok account** channel, connected from the same **Connect channel** menu. TikTok messages aren't supported.

---

## Removing a Page or a login

There's no button that removes one Page. To stop Rypl on it, switch off **Replies** and its moderation, or untick it under **Add or remove Pages**: its history and settings are kept, and ticking it again brings it back. **Remove this login** in the login's **⋯** menu disconnects every channel under it and erases their history in Rypl. Nothing changes on Facebook or TikTok either way.

---

## Still stuck?

Email [hey@rypl.is](mailto:hey@rypl.is) with your Rypl account email, the Page or ad account, the message you see and when it started.


## More on rypl.is

- [Why doesn't my Page or Instagram account appear in Rypl?](https://www.rypl.is/docs/troubleshooting/why-doesnt-my-page-appear): the usual causes
- [What does Needs reconnect mean in Rypl?](https://www.rypl.is/docs/troubleshooting/what-does-needs-reconnect-mean): where you see it and what fixes it
- [Why can't Rypl reply to Instagram DMs?](https://www.rypl.is/docs/troubleshooting/why-cant-rypl-reply-to-instagram-dms): Instagram conversation routing, step by step
- [Do I need a Meta Business portfolio to use Rypl?](https://www.rypl.is/docs/getting-started/do-i-need-a-business-portfolio): Business profile or Personal profile
- [Instagram ad comment automation guide](https://www.rypl.is/blog/instagram-ad-comment-automation-guide): permissions, Reels and DMs
- [How to manage comments on TikTok ads](https://www.rypl.is/blog/how-to-manage-tiktok-ad-comments): the complete guide
- [Facebook comment moderation tool](https://www.rypl.is/facebook-comment-moderation-tool): how Rypl answers and moderates comments on Facebook ads and posts

---

[Back to Troubleshooting](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
