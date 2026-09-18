---
layout: post
title: "Showing up when your customer asks an AI instead of Google"
date: 2026-09-16 09:00:00 +0000
tags: [AEO, SEO, AI]
description: "Half of American adults now use AI chatbots, and a growing share ask them for local recommendations. Here is what is actually known about getting recommended — and which popular AEO tactics are demonstrably useless."
---

A new sentence is being spoken in kitchens and parked cars all over the country: *"Who's a good [whatever] near me?"* — typed into ChatGPT instead of Google.

There is now an entire consulting category selling you a fix for this, most of it invented in the last eighteen months. Some of what they sell is fine. Some of it is provably useless. Here's how to tell the difference.

## How big this actually is

Pew Research Center, surveying US adults in February 2026, found that **about half — 49% — now use AI chatbots**, with **44% using ChatGPT specifically.** That's roughly a doubling of ChatGPT use since 2023.

BrightLocal's 2026 consumer survey found **45% of consumers said they had used AI to get a local business recommendation.** One survey, one methodology — treat it as a signal, not a measurement.

And the traffic side, which is the part nobody selling AEO wants to discuss: Pew's 2025 browsing-behavior study — 900 US adults, 68,879 Google searches in March 2025 — found that visits where an AI summary appeared ended in a click on a traditional result **8% of the time, versus 15% without a summary**, and that links *inside* AI summaries were clicked on just **1%** of visits.

Read that honestly. AI answers are not a new traffic channel. They are a channel where **being mentioned is the win**, and the click may never come. If a vendor's pitch is "AI traffic," ask them which number they're forecasting.

## What Google says, which is inconvenient for the AEO industry

Google published explicit guidance on optimizing for its generative AI features. The headlines:

- **"Structured data isn't required for generative AI search, and there's no special schema.org markup you need to add."**
- On the AI text files the industry has been selling: **"You don't need to create new machine readable files, AI text files, markup, or Markdown to appear in Google Search."** Google states plainly that **Google Search ignores them** and that creating one will *"neither harm nor help your site's visibility or rankings."*
- The overall position: optimizing for generative search is optimizing for search — it is still SEO.

That includes `llms.txt`, the file half the AEO industry has been billing for. **No major AI company has documented using it as a ranking or retrieval input.** I keep one on my own site because it's a tidy plain-English summary of the business and costs nothing, but I'd be lying if I sold it as an AI visibility strategy, and so is anyone who does.

The practitioner research doesn't agree with itself either. Ahrefs and Semrush have published conflicting findings on how much AI citations overlap with traditional search rankings. When the two largest tool vendors in the field can't agree on the basic correlation, nobody has a formula.

## What there is actual reason to do

**1. Be crawlable by the right bots.** If you want to be cited, you have to be readable. These are the user agents that matter, and they do different jobs:

- **OpenAI:** `GPTBot` (training), `OAI-SearchBot` (search index), `ChatGPT-User` (live fetch when a user asks)
- **Google:** `Google-Extended` (Gemini / AI training; separate from Googlebot)
- **Anthropic:** `ClaudeBot`, `Claude-User`, `Claude-SearchBot`
- **Perplexity:** `PerplexityBot`, `Perplexity-User`

The distinction is worth a minute of thought. You can decline to feed model training while still allowing the search and live-fetch bots that get you *recommended*. Blocking everything is the most common own goal on this list.

**2. Write the page that answers the question.** Models cite sources that contain a clear, self-contained answer near the question. A page titled with the actual question, answering it in the first two sentences, then supporting it — that's the format. This is also just good writing, which is why Google keeps insisting it's still SEO.

**3. Put your facts where they can be read.** Hours, service area, what you do and don't do, pricing structure, who you serve. In text, on the page, not baked into an image or trapped in a PDF. An AI cannot recommend what it cannot parse.

**4. Get mentioned somewhere other than your own website.** The consistent pattern across every credible analysis is that models lean on third-party sources — directories, local press, forums, review sites — to decide who's real. Your own claim that you're the best carries no weight anywhere, with anyone.

**5. Keep your Google Business Profile accurate.** Local answers still lean heavily on it. That's covered in the previous post.

Notice what isn't on this list: any file, any markup, any keyword density trick. The work is having verifiable facts in readable places and a reason for someone else to mention you.

## And don't lie about your own AI

One adjacent thing, since it sits in the same bucket for most owners.

Estimates of how many small businesses actually use AI vary wildly depending on who's asking and how they define it — Census Bureau data from May 2026 found fewer than 20% of firms with four or fewer employees reported using AI, while industry surveys from the Chamber of Commerce and Intuit have reported 60% and 68%. That spread isn't a mystery; it's a definitional gap. "Used ChatGPT once" and "runs AI in production" are not the same claim.

Which matters because the FTC's **Operation AI Comply**, announced in September 2024, is an enforcement sweep specifically targeting deceptive AI claims — companies overstating what their AI does. The same standard applies to a five-person business on a landing page as to a startup with a Series B.

Say what you actually run. It's a shorter sentence, and it's the one you can defend.

---

### Sources

- [Pew Research Center, "Americans and AI 2026," June 17 2026](https://www.pewresearch.org/internet/2026/06/17/americans-and-ai-2026-chatbots-smart-devices-and-views-on-impact/) — 49% of US adults use AI chatbots; 44% use ChatGPT. Surveyed Feb 17–23, 2026.
- [Pew Research Center, July 22 2025 — "Do people click on links in Google AI summaries?"](https://www.pewresearch.org/short-reads/2025/07/22/google-users-are-less-likely-to-click-on-links-when-an-ai-summary-appears-in-the-results/) — 8% vs. 15% click-through with and without AI summaries; 1% of visits click inside a summary.
- [BrightLocal, Local Consumer Review Survey 2026](https://www.brightlocal.com/research/local-consumer-review-survey/) — 45% have used AI for a local business recommendation. Single-source; directional.
- [Google Search Central, "Optimizing for generative AI features"](https://developers.google.com/search/docs/fundamentals/ai-optimization-guide) — structured data not required; AI text files including llms.txt are ignored by Google Search.
- Ahrefs and Semrush published research on AI citation vs. ranking overlap — conflicting findings.
- [US Census Bureau, Business Trends and Outlook Survey — AI use by firm size, May 2026](https://www.census.gov/library/stories/2026/05/ai-use-businesses.html) — under 20% for firms with four or fewer employees; 37% for firms with 250+; compare with US Chamber of Commerce and Intuit small-business AI surveys.
- [FTC, "Operation AI Comply," September 2024](https://www.ftc.gov/news-events/news/press-releases/2024/09/ftc-announces-crackdown-deceptive-ai-claims-schemes).
