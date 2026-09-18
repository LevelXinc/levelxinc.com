---
layout: post
title: "What happens to the calls you don't answer"
date: 2026-08-05 09:00:00 +0000
tags: [phone, missed calls, AI]
description: "The phone is still where the money is for a lot of small businesses, and it is the channel with the least structure around it. What the call data actually shows, and how to cover the phone without pretending a robot is you."
---

You can see every form submission. You can see every email. The calls that ring out at 2:15 on a Thursday leave no trace at all. No notification, no row in a spreadsheet, nothing to feel bad about later. That's what makes the phone the most under-managed part of most small businesses.

I want to be careful here, because this topic is a swamp of invented statistics. You will find confident claims that a specific percentage of small business calls go unanswered, and a specific dollar figure lost per year. I could not trace those to a real study, so I'm not going to repeat them, and you should be suspicious of any agency that does.

Here's what's actually documented.

## The phone converts, when it connects

Invoca's *Call Conversion Industry Benchmarks Report, 2025* analyzed over 60 million phone calls across nine industries. Two findings matter for a small business:

- **61% of callers to businesses speak with a person.** The rest hit a menu, a voicemail, a queue, or nothing.
- **37% of phone leads convert during the call itself**, and in home services, **46%**.

Sit with the second one. A call that reaches a human converts at a rate that no other channel in a small business touches. Roughly a third of the time, the sale closes inside the conversation. Which makes the first number the expensive one.

And it's Invoca's own data from their own customers. Businesses sophisticated enough to be paying for call analytics. It's fair to assume the long tail of small businesses does worse, not better.

## Google quietly removed the safety net

If you relied on Google to catch calls for you, note that Google **discontinued the call history and chat features in Google Business Profile as of July 31, 2024**, in its own words, "As of July 31, 2024, the chat and call history features are no longer available in your Business Profile." Calls placed from your Google listing now just go to your phone, and if nobody picks up, there's no record inside Google to go back to. Anything you had there is gone.

That's worth saying out loud because a lot of owners still believe Google is quietly holding their messages.

## The fix, in order of how much it costs you

**1. A voicemail greeting that's a promise, not an apology.** Most greetings say the business is unavailable and to leave a message. Better: say *when* you call back and give the alternative. "You've reached [business]. We're on a job right now. Leave your name and number and you'll get a call back before end of day, or text this same number and we'll usually answer faster." That's a free change that converts a dead end into two live paths.

**2. Let people text the number they're already calling.** Many people would rather text. If your business line can receive texts, say so on the website, in the greeting, and on the Google listing.

**3. Route after hours somewhere honest.** Forwarding to a personal cell that gets answered while driving is worse than voicemail. Pick one.

**4. Make a rule for callbacks.** Not "when I get to it." A named window. The previous post on this blog covers why the window matters more than the polish.

**5. Then, and only then, consider AI answering.**

## The part about AI, said plainly

I build AI systems for a living, so read this with that in mind: **an AI phone answerer is a real tool and it is oversold.**

What the evidence says about customer appetite: Gartner's 2024 consumer survey found that **64% of customers would prefer that companies didn't use AI for customer service**, and **53% said they would consider switching to a competitor if they found out a company was going to use AI for customer service.** That's not an argument against AI. It's an argument against *hiding* it, and against putting it between a ready-to-buy caller and a human.

There are also hard legal edges, and they're moving fast:

- The FCC ruled in **February 2024** that AI-generated voices in robocalls fall under the TCPA. Meaning **AI voices in unsolicited outbound calls are illegal** without the consent the law requires. Answering inbound calls is a different thing from dialing out. Don't blur them.
- In **Moffatt v. Air Canada (2024)**, a British Columbia tribunal held the airline responsible for what its chatbot told a customer. Your AI's promises are your promises. "The bot said it" is not a defense.
- California's **B.O.T. Act** requires disclosure when a bot is used to incentivize a sale or influence a vote. Other states are adding rules. Disclosure is the cheap side of this trade.

So the version I'd actually build for a small business:

- It answers when a human can't. After hours, or on the fourth ring, not the first.
- It says what it is in the first sentence. "Hi, this is the automated assistant for [business]."
- It has exactly two jobs: capture name, number and what they need; and book or promise a callback.
- It never negotiates price, never invents availability, never makes a claim about the service.
- It hands off to a human on request, immediately, with no loop.
- Every call produces a transcript that lands where you'll see it.

That system is worth building. A system that tries to *be* you on the phone isn't. Customers notice, the Gartner numbers say what they think about it, and the legal exposure lands on you, not the vendor.

## The one measurement to start with

For two weeks, log every inbound call: time, whether a human answered, and whether it turned into work. You don't need software. A notes app is enough.

Most owners are genuinely surprised by the result, in both directions. Some find the phone is fine and the real leak is somewhere else. Others find an entire afternoon of the week where nobody is home. Either way, you stop guessing, and you stop paying consultants who quote statistics they can't source.

---

### Sources

- [Invoca, *Call Conversion Industry Benchmarks Report, 2025*](https://www.invoca.com/press-release/invoca-releases-definitive-cross-channel-and-cross-industry-buyer-conversion-benchmark-report). 60M+ calls; 61% of callers reach a person; 37% of phone leads convert on the call; home services 46%.
- [Google Business Profile Help. Call history and chat discontinued July 31, 2024](https://support.google.com/business/answer/14919056?hl=en).
- [Gartner press release, July 9 2024, 64% of customers would prefer companies didn't use AI for customer service; 53% would consider switching](https://www.gartner.com/en/newsroom/press-releases/2024-07-09-gartner-survey-finds-64-percent-of-customers-would-prefer-that-companies-didnt-use-ai-for-customer-service).
- [FCC, February 8 2024. AI-generated voices in robocalls are illegal under the TCPA](https://www.fcc.gov/document/fcc-makes-ai-generated-voices-robocalls-illegal).
- [Moffatt v. Air Canada, 2024 BCCRT 149](https://www.americanbar.org/groups/business_law/resources/business-law-today/2024-february/bc-tribunal-confirms-companies-remain-liable-information-provided-ai-chatbot/), company held responsible for its chatbot's statements.
- California Business & Professions Code §17941 (the "B.O.T. Act"), bot disclosure requirement.
