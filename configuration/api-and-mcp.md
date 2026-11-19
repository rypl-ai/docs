---
layout: default
title: "Rypl API and MCP Server"
description: "Connect Claude Code, Cursor, VS Code, Gemini CLI or a script to Rypl on Pro and Ultra to ask about and export comments and DMs. Apps can't reply or delete."
last_modified_at: 2026-11-19
faq:
  - title: Questions about the API and MCP server
    questions:
      - q: Does Rypl have an API?
        a: |
          Yes. Since 12 November 2026 Rypl has an API and an MCP server on the Pro and Ultra plans, the 7-day free trial included. A connected app or script can read your comments and DMs with Rypl's analysis, see what was hidden and why, count and rank them, and export them. Setup is in Settings, under MCP and API Keys.
      - q: Which AI apps can connect to Rypl?
        a: |
          Claude Code, Cursor, VS Code (with GitHub Copilot) and Gemini CLI each have their own tile in Rypl's connect window. Other MCP clients, your own scripts and data warehouses connect through "Other app or API". The claude.ai and ChatGPT connectors aren't supported yet.
      - q: Can a connected app reply to comments or delete them?
        a: |
          No. Replies stay with your Rypl agent, so they follow your brand voice, knowledge base and reply rules whatever app you use, and nothing can be deleted through the API. If you allow it, an app can hide and unhide comments, mark them as reviewed, and add or edit moderation rules, but never set anything to delete.
      - q: Is the API included on the Simple plan?
        a: |
          No. The API and MCP server are part of Pro ($49 a month) and Ultra ($89 a month), and you can use them during the free trial. On Simple, the MCP and API Keys block in Settings says it is part of Pro and Ultra.
      - q: How do I stop an app from reading my data?
        a: |
          In Settings, under MCP and API Keys, click Disconnect next to the app and confirm. Its key stops working at once, and your other connections keep working. You can also give an app an end date when you connect it: in 30 days, 90 days or 1 year.
      - q: Can I export Rypl comments to a spreadsheet or data warehouse?
        a: |
          Yes. Connect "Other app or API" to get a key, then pull comments and messages into your script or warehouse, filtered by date, channel, platform, sentiment or intent, and fetch only what changed since your last export. The request details are in the API docs on rypl.is.
---

# Rypl API and MCP Server

Rypl has an **API** and an **MCP server** that let an AI app or your own script work with the comments and DMs Rypl handles. Connect **Claude Code**, **Cursor**, **VS Code** (with GitHub Copilot) or **Gemini CLI** and ask about your customers in plain words, or connect a script or data warehouse and export the data. Both launched on 12 November 2026 and are part of the **Pro** and **Ultra** plans, the free trial included.

A connected app works next to your agent, not instead of it: **no app can reply or delete**. Replies stay with the agent, with your brand voice, knowledge base and reply rules.

---

## What a connected app can do

- **Read comments and DMs**: comments on your Facebook and Instagram posts and ads and on your TikTok ads, and Messenger and Instagram Direct messages. Each comes with Rypl's reading of it: language, sentiment, intent, urgency and whether it asks a question.
- **See what was hidden and why**: banned words, one of your rules, a channel filter or a blocked author, and which rule it was.
- **Read your agent's replies**, with how long each took to go out.
- **Count and rank**: how many comments and messages came in over a period, split by day, channel, platform, sentiment, intent or language, and which posts and ads collect the most comments or complaints.
- **Read Needs attention**, ordered as it is in your Inbox.
- **Look at your setup**: agents, Global rules and the settings of each channel.
- **Moderate, only with your permission**: hide or unhide comments and mark flagged ones as reviewed.
- **Edit moderation rules, only with your permission**: add or change Global rules and banned words, and move between Review first and Apply automatically. It can never make anything delete comments.

## What it can't do

- **Reply** to a comment or a message. Replies come only from your agent.
- **Delete** anything. A connected app can hide; deleting can't be undone, so it stays with you.
- **Change agents or channel settings.** It can read them, nothing more.
- **Work as a claude.ai or ChatGPT connector**, for now. Claude Code, Cursor, VS Code, Gemini CLI and other MCP clients do work.

---

## Plans

| | Simple | Pro | Ultra |
|---|---|---|---|
| API and MCP server | — | ✅ | ✅ |

The free trial includes it. On Simple, the **MCP and API Keys** block in Settings says it is part of Pro and Ultra. Each account can have up to 10 connections, and every connection has its own key.

---

## How to connect an app

1. Go to **Settings** in Rypl and click **Connect** in the **MCP and API Keys** block. A window called **Connect an AI app** opens.
2. Check **What the app can read and change** under the app tiles, and click **Change** to narrow it before you go on (see the next section). The choice can't be edited once the app is connected.
3. Choose a tile. There are four named apps (**Claude Code**, **Cursor**, **VS Code**, **Gemini CLI**) and **Other app or API**, which covers every other MCP client, scripts and data warehouses. For **Other app or API**, give the connection a **Name** and click **Create key**.
4. Do what the window shows for your app. Depending on the app that is one terminal command, an **Add to Cursor** or **Add to VS Code** button, or an address and a key to paste into your own tool. Rypl fills your key in for you.
5. Wait for the window to switch to **Connected**, which happens as soon as the app makes its first request, then click **Done**. In Claude Code and Gemini CLI, start a new session: one that was already open won't see Rypl.

**The key is shown only once.** Rypl can't show it again, it doesn't open the Rypl dashboard, and anyone who has it can read what the connection allows. Treat it like a password. If you lose it, disconnect the app and connect it again.

Step-by-step instructions for each app are on rypl.is: [How do I connect Claude Code, Cursor or another AI app to Rypl?](https://www.rypl.is/docs/api/how-do-i-connect-an-ai-app)

---

## Permissions you choose

| Switch | What it covers | Starts |
|---|---|---|
| **Comments** | Comments on your posts and ads, with your replies to them | On |
| **Direct messages** | Your Messenger and Instagram conversations | On |
| **Settings** | Agents, moderation rules, channel settings (read only) | On |
| **Moderate comments** | Hiding, unhiding, marking as reviewed | Off |
| **Change moderation rules** | Editing Global rules, banned words and the rule mode | Off |

- **Moderate comments** works only with **Comments** on. **Change moderation rules** needs **Settings** on and **All channels**, because Global rules are shared by every channel.
- **Channels**: **All channels**, which includes the ones you connect later, or **Only selected**, for example one client's Pages.
- **Access ends**: never, or automatically after 30 days, 90 days or a year.
- **Changes are logged.** When an app hides a comment or changes a rule, Rypl records which connection did it.
- To change an app's access, disconnect it and connect it again with the new choice.

Give each app only what it needs: whatever it reads leaves Rypl and goes to that app.

---

## Disconnecting an app

Find the app in the **MCP and API Keys** list in **Settings**, click **Disconnect** and confirm. Its key stops working at once; your other connections carry on. The list shows when each connection was last used, which helps you spot the ones you no longer need.

---

## What people ask a connected app

- "Any complaints this week? What are they mostly about?"
- "Which of my ads draws the most negative comments?"
- "What did Rypl hide yesterday, and why?"
- "Which questions are still waiting for an answer?"
- "How long does my agent take to reply on Instagram?"
- "What's in Needs attention right now?"
- "How did last week compare with the week before?"
- With **Moderate comments** on: "Hide that comment and mark the other two as reviewed."
- With **Change moderation rules** on: "Add a rule that hides comments with links to other shops."

Name the period, channel or platform when it matters ("on the TikTok ad account", "since Monday"). The app sees only what its connection allows, and its data can be a few seconds behind the Inbox.

---

## Exporting to a script or data warehouse

Connect **Other app or API** to get a key, then pull comments and messages into your own tools, filtered by date, channel, platform, sentiment or intent, with Rypl's analysis and moderation on every row. After the first export you can fetch only what is new or changed. The addresses, fields and request details are documented on rypl.is: [What endpoints does the Rypl API have?](https://www.rypl.is/docs/api/what-endpoints-does-the-rypl-api-have)

---

## Frequently asked questions
{% for section in page.faq %}{% for item in section.questions %}
### {{ item.q }}

{{ item.a }}
{% endfor %}{% endfor %}

## More on rypl.is

- [Does Rypl have an API?](https://www.rypl.is/docs/api/does-rypl-have-an-api): the API and MCP server, plans and limits
- [How do I connect Claude Code, Cursor or another AI app to Rypl?](https://www.rypl.is/docs/api/how-do-i-connect-an-ai-app): the connect window, app by app
- [What can a connected app read and change?](https://www.rypl.is/docs/api/what-can-a-connected-app-read-and-change): every switch, channel and end-date option
- [What can I ask an AI app about my comments?](https://www.rypl.is/docs/api/what-can-i-ask-an-ai-app-about-my-comments): questions that work, and what the app looks at
- [Can a connected app hide comments or reply for me?](https://www.rypl.is/docs/api/can-a-connected-app-hide-comments-or-reply): moderation by an app
- [Can a connected app change my moderation rules?](https://www.rypl.is/docs/api/can-a-connected-app-change-my-moderation-rules): what it can change, and why never to delete
- [How do I export comments and messages with the Rypl API?](https://www.rypl.is/docs/api/how-do-i-export-comments-and-messages): exports for scripts and data warehouses
- [What endpoints does the Rypl API have?](https://www.rypl.is/docs/api/what-endpoints-does-the-rypl-api-have): the API reference
- [How do I disconnect an app or revoke its key?](https://www.rypl.is/docs/api/how-do-i-disconnect-an-app): cutting one app off
- [Why can't my app connect to Rypl?](https://www.rypl.is/docs/api/why-cant-my-app-connect-to-rypl): connection problems and what each error means
- [How to Get Facebook, Instagram and TikTok Ad Comments Through an API or MCP (2026)](https://www.rypl.is/blog/facebook-instagram-tiktok-comments-api): building it on the platforms' APIs, or one Rypl key
- [Rypl Pricing: Plans From $19/mo, 7-Day Free Trial](https://www.rypl.is/pricing): the API and MCP server are part of Pro and Ultra

---

[Back to Configuration](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
