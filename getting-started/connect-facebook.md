---
layout: default
title: Connect Your Facebook Page — Rypl Documentation
description: How to securely connect your Facebook Page to Rypl using Meta's Official Graph API for automated ad comment management.
---

# Connect Your Facebook Page

Rypl connects to your Facebook Page through **Meta's Official Graph API**, the same API that powers Meta's own tools. This means full compliance with Meta's policies and zero risk of account bans or restrictions.

---

## Prerequisites

Before connecting, make sure you have:

- **Admin access** to the Facebook Page you want to manage
- **An active Rypl account** ([sign up here](sign-up.md) if you have not yet)
- **A modern web browser** (Chrome, Firefox, Safari, or Edge)

---

## Connection Process

### Step 1: Initiate the Connection

From your Rypl dashboard, click **"Connect Facebook Page"** (or the equivalent button in your account setup flow). This will redirect you to Facebook's login screen.

### Step 2: Authenticate with Facebook

Log in to the Facebook account that has admin access to your Page. If you are already logged in, Facebook will ask you to confirm your identity.

### Step 3: Grant Permissions

Facebook will present a list of permissions that Rypl needs. These permissions allow Rypl to:

- **Read comments** on your Page's posts and ads
- **Reply to comments** on your behalf
- **Manage messages** in your Page inbox (for DM auto-replies)
- **Read Page content** to understand post context for AI replies
- **Moderate comments** (hide spam and negative comments)

All permissions are scoped to the specific Pages you select. Rypl cannot access your personal Facebook profile, friends list, or any information outside of the Pages you authorize.

### Step 4: Select Your Pages

If your Facebook account manages multiple Pages, you will see a list of all available Pages. Select the ones you want Rypl to manage. You can always add or remove Pages later.

The number of Pages you can connect depends on your plan:

| Plan | Pages |
|------|-------|
| Simple | Up to 3 |
| Pro | Up to 20 |
| Ultra | Unlimited |

### Step 5: Confirm and Return

After selecting your Pages and confirming permissions, you will be redirected back to the Rypl dashboard. Your connected Pages will appear in your account, ready for agent configuration.

---

## Security and Compliance

### Meta Official Graph API

Rypl is built entirely on Meta's Official Graph API. This is the sanctioned way to interact with Facebook Pages programmatically. Unlike unofficial tools that scrape or use browser automation:

- **No Terms of Service violations** — Rypl operates within Meta's approved API framework
- **No ban risk** — Your Page will never be flagged or restricted for using Rypl
- **Encrypted connections** — All data is transmitted over HTTPS
- **Token-based access** — Rypl stores secure API tokens, never your Facebook password

### Data Privacy

- Rypl only accesses data on the Pages you explicitly authorize
- Comment data is processed for AI replies and moderation, then stored securely
- You can revoke access at any time from both Rypl and Facebook's settings

---

## Managing Connected Pages

After the initial connection, you can manage your Pages from the Rypl dashboard:

- **Add more Pages** — Repeat the connection process to link additional Pages
- **Remove a Page** — Disconnect a Page to stop Rypl from managing its comments
- **Reconnect** — If a token expires or permissions change, you can re-authenticate to restore the connection

---

## Troubleshooting

If you run into issues during the connection process, check the [Facebook Connection Troubleshooting](../troubleshooting/facebook-connection.md) guide for solutions to common problems.

---

## Next Steps

With your Facebook Page connected, you are ready to [Create an AI Agent](create-ai-agent.md) to start managing comments.

---

[Back to Getting Started](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
