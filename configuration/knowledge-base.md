---
layout: default
title: Knowledge Base Configuration — Rypl Documentation
description: How to build and manage your Rypl AI agent's knowledge base using product catalogs, FAQs, website content, and more.
---

# Knowledge Base Configuration

The knowledge base is what transforms your AI agent from a generic chatbot into a knowledgeable sales assistant. It contains everything your agent needs to answer product questions, quote prices, explain policies, and provide accurate information to your customers.

Available on **Pro** and **Ultra** plans.

---

## Why a Knowledge Base Matters

Without a knowledge base, your AI agent can only provide generic responses. With one, it can:

- Answer specific product questions ("Does this come in size XL?")
- Quote accurate prices and promotions ("How much with the discount?")
- Explain shipping policies ("Do you ship to Canada?")
- Reference your return policy ("Can I return this if it doesn't fit?")
- Recommend products based on customer needs

The more comprehensive your knowledge base, the more helpful your agent becomes — and the more sales it drives.

---

## Supported Source Types

Rypl supports seven types of knowledge base sources. You can use any combination to build a comprehensive information foundation for your agent.

### 1. Product Catalog (PDF)

Upload your product catalog as a PDF file. Rypl extracts product names, descriptions, specifications, prices, and other details.

**Format requirements:**
- PDF format (standard, not scanned images)
- Structured content with clear product entries
- Include product names, descriptions, prices, and key specifications
- Maximum file size depends on your plan

**Tips:**
- Keep product information up to date — outdated prices lead to customer frustration
- Include all product variants (sizes, colors, configurations)
- Add any current promotions or discounts

### 2. FAQ Answers (CSV)

Upload your frequently asked questions and their approved answers in CSV format.

**Format requirements:**
- Two columns: Question, Answer
- CSV encoding: UTF-8
- One Q&A pair per row
- Answers can include links, markdown, or plain text

**Example CSV:**
```
Question,Answer
"How long does shipping take?","Standard shipping takes 3-5 business days. Express shipping is 1-2 business days."
"What is your return policy?","We accept returns within 30 days of purchase. Items must be unused and in original packaging."
"Do you offer gift wrapping?","Yes! Gift wrapping is available for $5 per item at checkout."
```

**Tips:**
- Include your 20-30 most common questions
- Write answers in your brand voice
- Cover pre-sale questions (they drive conversions)

### 3. Brand Voice (TXT)

Upload a text file with detailed brand voice guidelines, do's and don'ts, and communication standards.

**Format requirements:**
- Plain text (.txt) format
- Include tone guidelines, example phrases, and terms to avoid

**Tips:**
- This supplements the brand voice configuration in your agent settings
- Include competitor names to avoid mentioning
- List trademarked terms and how they should be used

### 4. Website URLs

Provide your website URLs and Rypl will crawl and extract relevant content.

**Format requirements:**
- Full URLs (e.g., `https://yourstore.com/products`)
- Publicly accessible pages (no login-required content)

**Tips:**
- Start with your product pages and FAQ page
- Include your About page for brand context
- Add your shipping and return policy pages
- The agent uses this content to ground its replies in your actual website information

### 5. Database

Connect structured data sources for real-time product information.

**Format requirements:**
- Structured data format
- Clear field names and data types

**Tips:**
- Useful for inventory-level information
- Connect pricing databases for up-to-date pricing
- Ideal for large catalogs with frequently changing data

### 6. User Comments

Allow the agent to learn from historical comment interactions on your page.

**Tips:**
- Helps the agent understand common questions your audience asks
- Provides context about your community's communication style
- Useful for identifying patterns in customer inquiries

### 7. Conversation History

Feed past conversation logs to help the agent understand customer interaction patterns.

**Tips:**
- Include successful sales conversations as positive examples
- Help the agent learn what follow-up questions to expect
- Provides context for multi-turn conversations (Ultra plan with full conversational memory)

---

## Building an Effective Knowledge Base

### Start With the Essentials

If you are setting up your knowledge base for the first time, prioritize these sources:

1. **FAQ Answers** — Fastest way to give the agent useful, accurate responses
2. **Website URLs** — Pulls your existing content without manual formatting
3. **Product Catalog** — Enables specific product recommendations and pricing

### Keep It Current

Your knowledge base is only as good as the information in it. Schedule regular updates:

- **Weekly:** Update prices, promotions, stock levels
- **Monthly:** Review FAQ answers, add new common questions
- **Quarterly:** Refresh product catalogs, review website URLs

### Quality Over Quantity

A focused, accurate knowledge base outperforms a massive but outdated one. Prioritize:

- Accuracy of information
- Relevance to common customer questions
- Currency of pricing and availability data

---

## Next Steps

With your knowledge base in place, learn how to leverage [Intent Detection](intent-detection.md) to understand what your customers want and respond accordingly.

---

[Back to Configuration](index.md) | [Back to Documentation](../index.md) | [Visit Rypl](https://www.rypl.is)
