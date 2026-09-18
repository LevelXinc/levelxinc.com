---
layout: post
title: "Your booking form is probably the leak"
date: 2026-07-22 09:00:00 +0000
tags: [forms, conversion, customer path]
description: "People who reach your booking form already want to buy. When they leave, it is usually the form's fault — not theirs. A field-by-field look at what to cut, what to keep, and which advice to ignore."
---

Somebody searched for what you sell, clicked your site, read enough to be convinced, and tapped "Book." Then they left.

That is the most expensive moment on your website, because you paid for everything that came before it. And it's the moment most owners never look at, because nothing shows up in the inbox to look at.

## The scale of the problem, honestly measured

The best-documented version of this is ecommerce checkout. The Baymard Institute maintains a rolling meta-analysis of documented cart abandonment studies; the current average sits around **70%** of carts abandoned. Their large-scale checkout usability research points at causes that have nothing to do with price: being forced to create an account, and a checkout that is simply too long or too complicated, each drive a meaningful share of abandonment. Baymard's benchmarking has found the average checkout runs to roughly **5 steps and 11 form fields**, where their usability testing suggests around **8 fields** is achievable for most.

A booking form is a checkout. Same psychology, smaller stakes, usually worse design — because a checkout gets optimized by a team and a booking form gets built once by whoever set up the website.

Two more numbers worth carrying around:

- Contentsquare's cross-industry benchmarking puts **desktop conversion around 3.4% against mobile around 2%**. Your form is probably being filled out on a phone, in a parking lot, one-handed. Design for that person, not for the version of the form you see on your laptop.
- Google's 2016 mobile-speed research found that **53% of mobile site visits are abandoned if a page takes longer than three seconds to load.** That figure is a decade old and specific to its methodology, so don't treat it as gospel — but nobody has since argued that slow forms convert better.

## What to cut

Go to your own booking form on your phone. Count the fields. Then, for each one, ask a single question: **can I do my job without this answer right now?**

- "How did you hear about us?" — You cannot, and it is not worth what it costs. Ask it after they book, or in the confirmation email.
- "Company name" — for a consumer service, dead weight.
- "Address" — needed for a site visit, not for a phone consult. Ask at the step where it's actually used.
- Separate first name and last name — one "Name" field.
- "Confirm email" — this doubles the typing to catch an error you can catch with a validation message.
- A long "Tell us about your project" textarea as a required field — people freeze. Make it optional, and label it as optional out loud.
- Account creation. Unless there's a portal they'll genuinely use, making someone invent a password to ask you a question is the most reliable way to lose them.

A useful benchmark: **name, one way to reach them, and one sentence about what they need.** Everything else is a question you can ask a person who has already said yes.

## The counterexample nobody mentions

Here is where most "cut your fields" advice gets dishonest.

In a well-documented test written up by Michael Aagaard at CXL, *removing* form fields **reduced** conversions. The shortened form pulled in more submissions of lower quality and less intent; the longer form's extra questions acted as a qualifier and a signal that the business took the work seriously.

So the rule is not "fewer fields always wins." The rule is: **every field must earn its place by either helping the customer get served or helping you sort real work from noise.** A question that qualifies is worth keeping. A question that only feeds a spreadsheet nobody reads is not. If you sell a $12,000 job, a couple of serious questions protect your calendar. If you sell a $90 appointment, they don't.

Test it if you can. If you can't run a real test — and most small businesses can't get enough traffic for a clean one — default to short, and add a question back only when you can name the decision it changes.

## Five fixes that don't require a redesign

1. **Show the form, don't link to it.** Every extra click is a place to leave. Put the booking form on the page, not behind a button that opens a new tool.
2. **Say what happens next, on the form itself.** "You'll get a confirmation now and a real reply from me within one business hour." Uncertainty is friction.
3. **Kill the surprise.** If a deposit is required, say so before the last step, not on it.
4. **Make errors survivable.** If a submission fails validation, keep everything they typed. Losing a filled-in form on a phone ends the relationship.
5. **Submit it yourself, monthly, from your phone, on cell data.** Not on wifi, not on your desktop. You will find something broken. Everyone does.

## The part that isn't the form

If your form works and inquiries still evaporate, the leak has moved downstream — to how fast anyone replies, or to whether the appointment gets kept. Those are separate problems with separate fixes, and the booking form usually gets blamed for both.

Fix the form first anyway. It's the one part of the customer path you fully control, and it's an afternoon's work.

---

### Sources

- [Baymard Institute — cart abandonment rate statistics](https://baymard.com/lists/cart-abandonment-rate) (rolling meta-analysis of documented studies; ~70% average) and Baymard's checkout usability research on abandonment causes and average checkout length.
- Michael Aagaard / CXL — documented test in which removing form fields reduced conversions.
- Contentsquare Digital Experience Benchmark — desktop vs. mobile conversion rates.
- Google / SOASTA mobile page speed research (2016) — 53% of mobile visits abandoned after three seconds. Dated; methodology-specific.
