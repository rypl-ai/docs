---
layout: default
title: "Ad Comment Management for Agencies"
description: "How agencies use Rypl to answer and moderate comments on clients' Facebook, Instagram and TikTok ads, with one agent and knowledge base per client."
last_modified_at: 2026-11-19
---

# Marketing Agencies

An agency's comment problem is the same as a brand's, multiplied by the number of clients, each with its own products, voice and rules. In Rypl each client gets its own agent and knowledge base, while rules you write once can cover every client.

---

## Choosing a plan

| | Simple | Pro | Ultra |
|---|---|---|---|
| Accounts | 1 | Up to 5 | Unlimited |
| Channels with AI replies | Up to 3 | Up to 20 | Unlimited |
| AI agents | 1 | Unlimited | Unlimited |
| Moderation rules and reply rules | — | ✅ | ✅ |
| [API and MCP server](../configuration/api-and-mcp.md) | — | ✅ | ✅ |
| Conversation memory | — | — | ✅ |

- **An account** is a Facebook or TikTok login; one Facebook login can bring several Pages.
- **A channel** is a Facebook Page with its linked Instagram, or a TikTok ad account. Only channels with AI replies on count, so a client who only needs moderation can stay connected without using up the plan.

There is no comment limit on any plan, so a client's viral ad doesn't change the bill. Pro fits several clients with one agent each and rules; Ultra removes the account and channel limits. See [Pricing](../reference/pricing.md).

---

## Setting up a client

1. **Connect the client's channels.** Their Facebook Pages and Instagram accounts through Meta, and their TikTok ad account through TikTok. **Business profile** is the better choice for Pages in a client's Business portfolio: the connection doesn't need re-login. See [Connect your channels](../getting-started/connect-facebook.md).
2. **Create an agent for the client** and name it after them, so the inbox is easy to read.
3. **Fill the client's knowledge base.** Their website, files and Q&A.
4. **Write the agent's instructions.** The client's tone, what to say when the agent doesn't know, topics to avoid.
5. **Assign the agent.** On **Channels**, pick the client's agent on each of their channel rows and switch on **Replies**. Every login appears as a separate group on **Channels**, which keeps each client's Pages side by side. Channels you add after sign-up start with replies off.
6. **Check the client's moderation.** Click each new channel's row: **Filter by tone** and the **Spam & media filter** start off on channels added later. Add banned words **Only on this channel** (competitors, words the client never wants shown) and, on Pro and Ultra, rules for this channel on top of your global rules.
7. **Check the first week.** Read replies and hidden comments for that client every day.

---

## Rules across clients

- **Global rules** apply to every channel that uses them. Write the rules every client needs once: hide scam links, flag refund requests for a person.
- **Rules for this channel** add client-specific rules and banned words on top.
- On a channel, the **Global rules** switch turns them off for that client, and **Choose which** unticks single rules or the global banned words.
- **Review first or Apply automatically** is one setting for all your rules. Add new rules in Review first, so matches wait for you, and switch to Apply automatically once they catch the right comments.

---

## Running it day to day

- **One inbox for every client.** Each reply shows which agent wrote it, and filters narrow the view to one channel or platform.
- **Needs attention** collects what needs a person across all clients: complaints, urgent questions and rule matches. **Needs review** shows only what your rules flagged.
- **Suggest improvements** on each agent looks at that client's recent replies and unanswered questions and proposes Q&A and instruction edits.
- **Numbers for client calls** (Pro and Ultra). Connect the [API and MCP server](../configuration/api-and-mcp.md) and ask an AI app such as Claude Code or Cursor for one client's complaints this week, the ad that draws the most of them, or what was hidden and why, or export the comments to your own spreadsheet. You can limit each connection to selected channels.

---

## What to tell clients

- Replies are written by AI from the client's own facts and published automatically. Spam is flagged in about 1.7 seconds on average and hidden within seconds (RYPL's own measurement).
- Complaints go to a person by default; negative comments are hidden only if the client chooses that.
- Rypl connects through the official Meta Graph API and TikTok Marketing API, with no scraping or browser automation.
- Results to compare: reply time, hidden spam, and ROAS before and after. Across RYPL accounts, brands saw about +10% ROAS in the first month (RYPL's own measurement); the client's result depends on their comments and their knowledge base.

---

## Next Steps

- [Multiple accounts and pages](../configuration/multi-account.md)
- [Moderation](../configuration/moderation-rules.md)
- [API and MCP server](../configuration/api-and-mcp.md)
- [Pricing](../reference/pricing.md)


## More on rypl.is

- [Can I use Rypl for several brands or clients?](https://www.rypl.is/docs/before-you-start/can-i-use-rypl-for-several-brands-or-clients): how agencies usually set it up
- [How many accounts and Pages can I connect to Rypl?](https://www.rypl.is/docs/billing/how-many-accounts-and-pages-can-i-connect): accounts, channels with AI replies and the limits
- [Managing multiple Facebook Pages with AI: a guide for agencies](https://www.rypl.is/blog/facebook-automation-for-agencies): one agent per client
- [How to get Facebook, Instagram and TikTok ad comments through an API or MCP](https://www.rypl.is/blog/facebook-instagram-tiktok-comments-api): building it yourself or using one Rypl key
- [Rypl vs the alternatives](https://www.rypl.is/compare): ReplyZen, ManyChat, NapoleonCat, Agorapulse, Respondology and BrandBastion compared, with sources
- [RYPL pricing](https://www.rypl.is/pricing): plans from $19 a month, no comment limit, 7-day free trial

---

[Back to Use Cases](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
