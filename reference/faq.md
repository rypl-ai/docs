---
layout: default
title: "Rypl FAQ: Comment Replies and Moderation"
description: "Answers about Rypl, the AI tool for Facebook, Instagram and TikTok ad comments: platforms, pricing, languages, moderation, safety and how it compares."
last_modified_at: 2026-10-11
faq:
  - title: About Rypl
    questions:
      - q: What is Rypl?
        a: |
          Rypl is AI software that replies to and moderates comments and DMs on Facebook and Instagram, plus comments on TikTok ads. AI agents answer buyers in your brand voice from your knowledge base, spam and hate are hidden automatically, and complaints wait for a person in one inbox. Brands and agencies running paid social use it so buyers get answers fast and the thread under the ad stays clean.
      - q: Which platforms does Rypl support?
        a: |
          Facebook (comments on ads and Page posts, and Messenger), Instagram (comments on ads and posts, and Direct messages) and TikTok (comments on ads). Every platform is on every plan. Organic TikTok posts are not supported.
      - q: Does Rypl work with Instagram?
        a: |
          Yes. Rypl answers and moderates comments on Instagram ads and posts and replies to Instagram Direct messages. An Instagram professional account connects through the Facebook Page it is linked to. See the [Instagram comment moderation tool](https://www.rypl.is/instagram-comment-moderation-tool).
      - q: Does Rypl work with TikTok?
        a: |
          Yes, for comments on TikTok ads. TikTok doesn't allow deleting other people's comments, so on TikTok Rypl hides them instead. See the [TikTok ad comment moderation tool](https://www.rypl.is/tiktok-comment-moderation-tool).
      - q: Does Rypl handle organic posts or only ads?
        a: |
          Both, on Facebook and Instagram: comments on ads (including dark posts) and on regular posts. On TikTok, ads only.
  - title: Pricing
    questions:
      - q: How much does Rypl cost?
        a: |
          Simple is $19 a month, Pro $49 and Ultra $89. Billed yearly: $15, $39 and $71 a month. See [Rypl pricing](https://www.rypl.is/pricing).
      - q: Does Rypl limit the number of comments?
        a: |
          No. No plan limits the number of comments. Plans differ in the number of accounts, pages and agents, and in the rules and AI features included.
      - q: Is there a free trial?
        a: |
          Yes. Every plan starts with 7 days free: $0 today, and you can cancel any time before the trial ends without being charged.
      - q: What happens if I cancel Rypl?
        a: |
          You keep access until the end of the period you paid for. If you come back later, your agents, knowledge base and rules are still there.
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
          Yes. It replies in the language each comment is written in, or in a language you set for the channel.
      - q: Can I check replies before they go out?
        a: |
          Rypl posts replies automatically, so buyers get an answer while they're still looking at the ad. To stay in control:

          - choose *Within a few minutes*, *Within an hour* or *Within a day* in **How soon**;
          - read every reply in the inbox, which shows the agent that wrote it, and delete any reply (on Facebook you can also edit it);
          - on Pro and Ultra, use reply rules to keep the agent silent on topics a person should handle, and moderation rules set to **I'll answer myself**;
          - turn **Reply with AI** off on a channel to use Rypl for moderation only.
      - q: Does Rypl reply to DMs?
        a: |
          Yes, to Messenger and Instagram Direct messages. Meta allows replies within 7 days of the person's last message.
  - title: Moderation
    questions:
      - q: How fast does Rypl hide spam?
        a: |
          Spam is flagged in about 1.7 seconds on average and hidden within seconds (RYPL's own measurement). On Facebook, half of hidden comments are hidden within 13 seconds of being posted, and about 7 seconds of that is Meta delivering the comment.
      - q: Does Rypl hide negative comments?
        a: |
          Only if you choose to. **Filter by tone** is off by default; you can set it to hide or delete negative comments on a channel. By default, complaints go to **Needs attention** so a person answers them, because a complaint answered in public builds more trust than one that disappears.
      - q: What's the difference between hiding and deleting a comment?
        a: |
          A hidden comment stays visible to the person who wrote it and their friends, so they don't know it's hidden. A deleted comment is gone for everyone and can't be restored.
      - q: Does blocking an author in Rypl block them on Facebook?
        a: |
          No. **Block author** quietly hides that person's new comments on the channel. They aren't notified and can still message your Page. Undo is one click.
  - title: Safety
    questions:
      - q: Is Rypl safe for my Page and ad account?
        a: |
          Rypl connects through the official Meta Graph API and TikTok Marketing API, authorized by you through Meta and TikTok. There is no scraping or browser automation, and Rypl never sees your password. You can disconnect at any time from Rypl or from your Meta and TikTok settings.
      - q: Which AI does Rypl use?
        a: |
          The latest OpenAI models, upgraded automatically on every plan. Ultra uses the most powerful one.
  - title: Comparisons
    questions:
      - q: How is Rypl different from NapoleonCat, Agorapulse, ReplyZen or ManyChat?
        a: |
          On every plan, Rypl's AI writes and posts replies and hides spam on its own, on Facebook, Instagram and TikTok ads, from $19 a month flat with no comment limit.

          - **ReplyZen** meters every AI reply (500 a month on its $29 plan).
          - **NapoleonCat** starts automatic hiding on its Expert plan ($119/mo billed yearly), and its AI drafts replies for a person to send.
          - **Agorapulse** prices per user, starts ad comments on Professional, and has no AI replies for comments.
          - **ManyChat** is built for DM funnels; its public comment replies are pre-written lines, with AI comment replies only on Instagram, in beta.

          Rypl is built for comments and DMs, not publishing or reporting, and runs next to your suite or flow builder. Sources and details: [Rypl vs the alternatives](https://www.rypl.is/compare).
      - q: Is Rypl good for agencies?
        a: |
          Yes. Each client gets its own agent and knowledge base, global rules cover every client, and Ultra has unlimited accounts and pages.
---

# Frequently Asked Questions

If your question isn't here, write to [hey@rypl.is](mailto:hey@rypl.is).

{% for section in page.faq %}
---

## {{ section.title }}
{% for item in section.questions %}
### {{ item.q }}

{{ item.a }}
{% endfor %}
{% endfor %}

## More on rypl.is

- [Facebook comment moderation tool](https://www.rypl.is/facebook-comment-moderation-tool): how Rypl answers and moderates comments on Facebook ads and posts
- [Instagram comment moderation tool](https://www.rypl.is/instagram-comment-moderation-tool): AI replies and moderation for Instagram ads, posts and DMs
- [TikTok ad comment moderation tool](https://www.rypl.is/tiktok-comment-moderation-tool): replies and moderation for comments on TikTok ads
- [Rypl vs the alternatives](https://www.rypl.is/compare): ReplyZen, ManyChat, NapoleonCat and Agorapulse compared, with sources
- [Rypl pricing](https://www.rypl.is/pricing): plans from $19 a month, no comment limit, 7-day free trial

---

[Back to Reference](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
