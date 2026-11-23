---
layout: default
title: "Rypl FAQ: Comment Replies and Moderation"
description: "Answers about Rypl, the AI tool for Facebook, Instagram and TikTok ad comments: platforms, pricing, DMs, moderation, safety, the API and comparisons."
last_modified_at: 2026-11-23
faq:
  - title: About Rypl
    questions:
      - q: What is Rypl?
        a: |
          Rypl is AI software that replies to and moderates comments and DMs on Facebook and Instagram, plus comments on TikTok ads. AI agents answer buyers in your brand voice from your knowledge base, spam and hate are hidden automatically, and complaints wait for a person in one inbox. Brands and agencies running paid social use it so buyers get answers fast and the thread under the ad stays clean.
      - q: Which platforms does Rypl support?
        a: |
          Facebook (comments on ads and Page posts, and Messenger), Instagram (comments on ads, posts and Reels, and Direct messages) and TikTok (comments on ads). Every platform is on every plan. On TikTok, Rypl handles comments on ads and, once the TikTok account is connected, on its own posts; TikTok messages aren't supported.
      - q: Does Rypl work with Instagram?
        a: |
          Yes. Rypl answers and moderates comments on Instagram ads, posts and Reels and replies to Instagram Direct messages, including replies to your Stories, which arrive as DMs. An Instagram professional account connects through the Facebook Page it is linked to and shares that Page's agent and settings. See the [Instagram comment moderation tool](https://www.rypl.is/instagram-comment-moderation-tool).
      - q: Does Rypl work with TikTok?
        a: |
          Yes, for comments on TikTok ads, with the same agent, knowledge base and moderation as Facebook and Instagram. TikTok only lets advertisers hide other people's comments, so where a rule would delete, Rypl hides instead. Connect the TikTok account itself as well, and Rypl handles the comments on your own TikTok posts too. TikTok messages aren't supported. See the [TikTok ad comment moderation tool](https://www.rypl.is/tiktok-comment-moderation-tool).
      - q: Does Rypl handle organic posts or only ads?
        a: |
          Both, on Facebook and Instagram: comments on ads (including dark posts) and on regular posts. On TikTok too, once you connect the TikTok account as well as your TikTok ads.
  - title: Pricing
    questions:
      - q: How much does Rypl cost?
        a: |
          Simple is $19 a month, Pro $49 and Ultra $89, flat. Billed yearly, they cost $182, $470 and $854 a year ($15, $39 and $71 a month). Prices are in US dollars, before tax. Simple covers 1 account with AI replies on 3 channels, Pro 5 accounts and 20 channels, and Ultra has no limit on either. See [Pricing](pricing.md) and [RYPL pricing](https://www.rypl.is/pricing).
      - q: Does Rypl limit the number of comments?
        a: |
          No. No plan limits the number of comments. Plans differ in the number of accounts, channels with AI replies and agents, and in the rules and AI features included. A channel is a Facebook Page with its linked Instagram, or a TikTok ad account, and only channels with AI replies on count: moderation runs on every channel you connect.
      - q: Is there a free trial?
        a: |
          Yes. Every plan starts with 7 days free: $0 today, and you can cancel any time before the trial ends without being charged. On Pro and Ultra the trial includes the API and MCP server.
      - q: What happens if I cancel Rypl?
        a: |
          Rypl keeps working until your paid period runs out. After that, your agents, rules and channels are held for 60 days, so if you come back within that time you pick up where you left off.
  - title: Replies
    questions:
      - q: How fast does Rypl reply to comments?
        a: |
          On the default *Immediately* setting, replies go out in under 60 seconds: in RYPL's own measurement, 97% of Facebook replies went out within a minute. You can also have an agent wait a few minutes, up to an hour or up to a day.
      - q: Where do Rypl's answers come from?
        a: |
          From your knowledge base: your website, Q&A and documents. On Pro and Ultra the agent also reads the post or ad, so it knows which product someone is asking about. Keep the knowledge base current and the answers stay accurate.
      - q: Does Rypl reply in other languages?
        a: |
          Yes. It replies in the language each comment is written in, or in a language you set for the channel, and the same knowledge base works for all of them.
      - q: Can I check replies before they go out?
        a: |
          There is no approval step: Rypl posts replies on its own, so buyers get an answer while they're still looking at the ad. **Review first** applies to moderation rules, not replies. To stay in control:

          - read every reply under **AI replies** in the inbox, which shows the agent that wrote it; a reply posted on Facebook or TikTok can be edited or deleted from there;
          - on Pro and Ultra, use a reply rule with **My text** for wording that must be exact, and **Don't reply** or a moderation rule set to **I'll answer myself** for topics a person should handle;
          - switch **Replies** off on a channel to use Rypl for moderation only.
      - q: Does Rypl reply to DMs?
        a: |
          Yes, to Messenger and Instagram Direct messages. Meta gives the agent 24 hours from the person's last message to answer. Past that, someone on your team can still reply from the inbox for up to 7 days, provided your connection has Meta's Human Agent permission. If a chatbot or helpdesk app is the default app for your Instagram DMs, Rypl stays out of those conversations until you make Rypl the default in Meta's Instagram conversation routing. TikTok messages aren't supported.
  - title: Moderation
    questions:
      - q: How fast does Rypl hide spam?
        a: |
          The AI flags spam in about 1.7 seconds on average, and the comment is hidden within seconds (RYPL's own measurement). On Facebook, half of the comments Rypl hid were hidden within 13 seconds of being posted and 94% within a minute, with Meta's delivery time, about 7 seconds, included (RYPL data, Q3 2026).
      - q: Does Rypl hide negative comments?
        a: |
          Only if you choose to. **Filter by tone** is off by default; you can set it to hide or delete negative comments on a channel (on TikTok, hide only). By default, complaints go to **Needs attention** so a person answers them, because a complaint answered in public builds more trust than one that disappears.
      - q: What's the difference between hiding and deleting a comment?
        a: |
          A hidden comment disappears from public view, but its author still sees it (on Facebook, their friends may too), so they don't know it's hidden, and you can unhide it. A deleted comment is gone for everyone and can't be restored. On TikTok, Rypl can only hide.
      - q: Does blocking an author in Rypl block them on Facebook?
        a: |
          No. **Block author** quietly hides that person's comments on the channel where you block them, including every new one. They aren't notified and can still message your Page. **Unblock** is one click.
  - title: Safety
    questions:
      - q: Is Rypl safe for my Page and ad account?
        a: |
          Rypl connects through the official Meta Graph API and TikTok Marketing API, authorized by you through Meta and TikTok. There is no scraping or browser automation, and Rypl never sees your password. You can disconnect at any time from Rypl or from your Meta and TikTok settings.
      - q: Which AI does Rypl use?
        a: |
          The latest OpenAI models, upgraded automatically on every plan. Ultra uses the most powerful one.
  - title: API and MCP server
    questions:
      - q: Does Rypl have an API or an MCP server?
        a: |
          Yes. Pro and Ultra include both a REST API and an MCP server, and they work during the free trial too. To connect, go to **Settings** → **MCP and API Keys** → **Connect** and choose Claude Code, Cursor, VS Code or Gemini CLI, or **Other app or API** for a script or a data warehouse.

          Once connected, the app can pull your comments and DMs with the labels Rypl already gave each one (intent, sentiment, language, urgency), the reason behind every hidden comment, and the replies your agent posted. Ask it things like "which ad gets the most complaints?", get totals for a week or a month, or export the rows. Each connection has its own key, and you pick its channels, what it may read and when its access ends.

          Hiding, unhiding and editing your moderation rules stay off unless you switch them on, and even then nothing can be set to delete. No app can post a reply or delete a comment: replying stays your agent's job. Connectors inside claude.ai and ChatGPT aren't supported yet.

          See [API and MCP server](../configuration/api-and-mcp.md) and [Does Rypl have an API?](https://www.rypl.is/docs/api/does-rypl-have-an-api)
  - title: Comparisons
    questions:
      - q: How is Rypl different from NapoleonCat, Agorapulse, ReplyZen or ManyChat?
        a: |
          On every plan, Rypl's AI writes and posts replies and hides spam on its own, on Facebook, Instagram and TikTok ads, from $19 a month flat with no comment limit.

          - **ReplyZen** meters every AI reply (500 a month on its $29 plan). See [Rypl vs ReplyZen](https://www.rypl.is/blog/rypl-vs-replyzen).
          - **NapoleonCat** hides comments automatically only on its Expert plan ($119/mo billed yearly), and its AI drafts replies for a person to send. See [Rypl vs NapoleonCat](https://www.rypl.is/blog/rypl-vs-napoleoncat).
          - **Agorapulse** prices per user, handles ad comments from its Professional plan, and has no AI replies for comments. See [Rypl vs Agorapulse](https://www.rypl.is/blog/rypl-vs-agorapulse).
          - **ManyChat** is built for DM funnels; its public comment replies are pre-written lines, and its AI reaches comments only on Instagram, in beta. See [Rypl vs ManyChat](https://www.rypl.is/blog/rypl-vs-manychat).

          Rypl is built for comments and DMs, not publishing or reporting, and runs next to your suite or flow builder. All comparisons: [Rypl vs the alternatives](https://www.rypl.is/compare).
      - q: Is Rypl good for agencies?
        a: |
          Yes. Each client gets its own agent and knowledge base, Global rules cover every client and can be switched off or narrowed per channel, and Ultra has no limit on accounts or channels. On Pro and Ultra, the API and MCP server can count each client's comments for a period and export them. See [Marketing Agencies](../use-cases/agencies.md).
---

# Frequently Asked Questions

If your question isn't here, see the [Rypl help center](https://www.rypl.is/docs) or write to [hey@rypl.is](mailto:hey@rypl.is).

{% for section in page.faq %}
---

## {{ section.title }}
{% for item in section.questions %}
### {{ item.q }}

{{ item.a }}
{% endfor %}
{% endfor %}

## More on rypl.is

- [Rypl documentation](https://www.rypl.is/docs): the help center, one question per page
- [Does Rypl have an API?](https://www.rypl.is/docs/api/does-rypl-have-an-api): what a connected app can read and change
- [Facebook comment moderation tool](https://www.rypl.is/facebook-comment-moderation-tool): how Rypl answers and moderates comments on Facebook ads and posts
- [Instagram comment moderation tool](https://www.rypl.is/instagram-comment-moderation-tool): AI replies and moderation for Instagram ads, posts and DMs
- [TikTok ad comment moderation tool](https://www.rypl.is/tiktok-comment-moderation-tool): replies and moderation for comments on TikTok ads
- [Rypl vs the alternatives](https://www.rypl.is/compare): ReplyZen, ManyChat, NapoleonCat, Agorapulse, Respondology and BrandBastion compared, with sources
- [RYPL pricing](https://www.rypl.is/pricing): plans from $19 a month, no comment limit, 7-day free trial

---

[Back to Reference](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
