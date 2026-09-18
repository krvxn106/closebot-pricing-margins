# CloseBot Agency Pricing: What the $397/mo Agency Plan Actually Costs, When the $64 Business Plan Wins, and Where the Hidden Margins Sit

If you sell AI appointment setting to clients, the pricing question is not "how much does CloseBot cost." It is "does the agency plan pay for itself, or am I better off reselling a business plan and pocketing the difference." Those are different calculations, and CloseBot's pricing page does not answer them directly.

What follows is the current plan lineup pulled from CloseBot's own plans page, plus the usage costs that sit behind the headline number, plus the parts of the bill that show up on a different invoice entirely.

## CloseBot runs two separate pricing tracks

Most tools in this category have one ladder that scales with volume. CloseBot splits it: business plans for people running agents on their own pipeline, agency plans for people reselling agents to clients.

The split matters because the agency plan is not simply "the business plan with more seats." It is a different set of features built around one thing: letting you charge your clients more than CloseBot charges you.

Business plans include message costs in the base price. You pay $64/month at the entry level and your messages are covered up to the included ceiling, so your bill is predictable and your margin is not your problem, because there is no margin. You are the end customer.

Agency plans flip that. The base subscription is a flat fee, and messages, seats, storage and AI token costs get passed to you at cost, rebilled to clients at whatever markup you set through your own Stripe connection. You are the reseller.

## Full CloseBot plan comparison

Here is the current lineup as published on the official plans page. Every plan on that page is in this table, including the free tier.

| Plan | Who it's for | What's included | Price | Billing cycle | Get started |
| --- | --- | --- | --- | --- | --- |
| **Free** | Testing the platform, low-volume solo operators | 100 AI messages/mo, 1 agent, 1 user seat, 1 MB knowledge storage, unlimited account connections | **$0** | Free forever | [Start on the free plan](https://app.closebot.com/a?fpr=li87) |
| **Core (Business)** | Businesses running agents on their own pipeline | Message costs included in base price, 500 messages/mo included, 15+ templates, human support, add-on seats ($5 each), add-on storage, add-on agents | **$64/mo** monthly, **$53/mo** billed annually as $640/yr | Monthly or annual | [See business plan pricing](https://app.closebot.com/a?fpr=li87) |
| **Core (Agency)** | Agencies building and reselling agents for clients | Unlimited agents and sources, white-label client portal, rebilling on messages, seats, storage and tokens, 15+ templates, human support | **$397/mo** monthly | Monthly or annual | [Check the agency plan](https://app.closebot.com/a?fpr=li87) |
| **Growth** | Teams needing SLAs, compliance work or very high volume | HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support, 50+ templates | **Custom quote** | Custom | [Request Growth pricing](https://app.closebot.com/a?fpr=li87) |

Two things worth flagging before you screenshot the table.

The business plan price is not a single number. The plans page has a message-volume slider that runs from 100 monthly replies up to 100K+, and the price moves with it. $64/month is the entry point at 500 messages. If you need 5,000 or 50,000 messages, your quote is higher, and the page does not publish the full ladder without the slider in front of you.

The agency annual rate is not shown as a plain figure on the page itself. CloseBot's page displays annual pricing of $53/mo on the business plan (billed as $640/yr). Third-party reviews published in 2026, including ColdIQ and several other tool directories, list the agency plan at $331/month when billed annually, which is roughly two months free. Treat that as a figure to confirm at checkout, not one to budget against blindly.

## The usage costs that sit behind the agency plan

The $397 headline is the smallest part of the agency math. What actually determines whether you make money is the four meters CloseBot lets you rebill.

**Messages.** Agency accounts pay per message and pass the cost through. On this, CloseBot's two documentation pages disagree with each other. The plans page FAQ states agencies are billed a flat $0.012 per message. The help center article on Free, Business and Agency Plans states $0.006 per message. One of them is out of date.

> Before you build a margin model on the message rate, confirm the current number with CloseBot support. The difference between $0.006 and $0.012 is double, and it lands directly on your profit per client.

**Knowledge library storage.** Agency accounts are billed per MB per day for the documents and websites your agents pull from, and the help docs put that at $0.006/MB/day. For context, 1 MB of text is roughly 1,000 pages. This is a small line item for most niches, but it is rebillable, which makes it free money at the margin.

**User seats.** One seat comes with the base plan. Additional seats are $5 each, whether they go to your own team or to a client who wants to log in and watch their dashboard. Agencies can mark these up.

**AI provider tokens.** If you switch on the Agent Node's "unlimited potential" mode, message billing changes shape. Instead of one segment per message, you are billed token costs, which means a single message can consume several segments. Moderate agents stay on the flat segment model. Heavy agents with many tools and long instructions will cost more than the per-message rate suggests, so budget conservatively if your agents are complex.

That is the real agency pricing structure: a flat subscription for access, a usage layer you pay at cost, and a rebilling dashboard that lets you decide how much of that usage layer to mark up.

## Where the margin actually comes from

CloseBot's own pitch is that agencies using it bill around $500 per client per month, against a comparison point of roughly $100/month for a HighLevel-only AI product. Read that number the way you should read any vendor poll: it is a marketing figure from a company that sells to agencies, not an audited statistic.

The mechanics behind it are worth understanding anyway, and they are straightforward. Your client tops up a wallet that pays into your Stripe account. You top up a wallet that pays CloseBot. The gap between the two, multiplied across clients and messages, is your gross margin on AI delivery. CloseBot exposes four separate places to set that gap: messages, seats, storage, tokens. You can mark up one, all four, or none and price the service as a flat retainer instead.

If your clients send 20,000 messages a month across the book and you bill messages at three times cost, the spread is meaningful. If they send 400 messages a month, the spread is a rounding error and your actual revenue is the retainer you charge for building and maintaining the agents. That distinction decides whether the agency plan is a pricing model or just a feature you wanted.

## What the agency plan does not include

This is the part that most agency pricing breakdowns skip, and it is the part that changes the total.

CloseBot is CRM-native. It connects to HighLevel, HubSpot, LeadConnector or a custom CRM, then takes over the text-based channels already running inside that CRM. It does not connect to Instagram, WhatsApp or Messenger on its own.

For an agency whose clients already live in GoHighLevel, that is fine. You are paying a CRM bill regardless. For an agency considering CloseBot for clients who are not on a CRM, the subscription is only half the cost. GoHighLevel's own entry plans start around $97/month, and each client sub-account or CRM seat adds to that stack. Third-party reviewers have flagged this as the single biggest reason solo operators walk away from CloseBot, since they end up buying an agent and a CRM to run it.

The agency plan also has no bring-your-own-key option per the plans page FAQ, which CloseBot frames as a security and compliance decision. What you can do is push token costs to clients as a rebillable line, which is arguably better for an agency anyway.

And there are no refunds. CloseBot states this plainly. What you get instead is a free-forever plan under 100 messages a month and a 7-day trial of any paid plan, including the agency plan, before the first charge hits. Plans run month to month with no contract, so downgrading later is not a fight.

## Agency plan or business plan: the decision in one pass

Take the agency plan if:

- You are building agents for client accounts and want to bill for them under your own brand

- You need the white-label client portal, because your clients will see this interface

- You want usage costs to flow through your Stripe account so you can mark them up

- You manage enough clients that per-seat and per-message rebilling adds up to real revenue

Take the business plan if:

- The agents are working your own pipeline, not clients'

- You want a predictable bill with message costs already inside the price

- You do not need a client-facing branded portal

- You are testing whether AI appointment setting works for your own business before selling it to anyone else

There is a third case that gets missed: agencies with a small number of clients where you are effectively the only user. The agency plan's value is concentrated in rebilling and white labeling. If your two clients never log in and you charge a flat monthly retainer, you are paying $397 for features you are not using, and a business plan pointed at each client's pipeline may cover the same ground for less. That setup gets messy at scale, which is exactly the point at which the agency plan starts earning its fee.

> The business plan does not give you access to rebilling and white labeling, even inside the 7-day agency trial. If you want to test the agency workflow, test it on the agency trial, not the business trial.

## A quick note on annual billing

CloseBot's business plan shows $53/mo when billed annually, at $640 for the year, against $64/mo monthly. That is roughly 17% off, or about two months free. Annual billing also unlocks a larger template library, which the plans page marks as available on annual plans only.

If you are committed to the platform, annual is the cheaper line item. If you are still deciding whether your clients will actually pay for AI appointment setting, monthly is worth the premium, because the agency workflow takes a few weeks to prove out and there are no refunds if it does not.

## What to check before you commit

Confirm the current per-message agency rate in writing, because the $0.006 and $0.012 figures are both live on CloseBot's own properties right now.

Run the numbers on your top three clients' actual monthly message volume. A client sending 300 messages a month is a retainer client, not a rebilling client, and pricing them as the latter will make your margins look worse than they are.

Check whether your clients' channels are already inside a CRM. If they are not, add the CRM subscription to your cost model before you quote anyone.

Use the 7-day agency trial to test the white-label portal and the Stripe rebilling flow end to end. Those two features are the reason the plan costs what it costs, and they are also the two things that are hardest to evaluate from a demo call.

## FAQ

**Does the agency plan include messages?**

No. Agency accounts pay per message, currently quoted at $0.012 on the plans page FAQ and $0.006 in the help center, and rebill that cost to clients at your own markup.

**Can I use the agency plan for my own business instead of clients?**

Technically yes, but you would be paying for white labeling and rebilling tools you are not using. A business plan is cheaper for that job.

**Is there a free trial of the agency plan?**

Yes, 7 days on any paid plan before you are billed. There is also a free-forever plan capped at 100 messages per month that works for testing basic agent builds.

**What is the annual discount?**

CloseBot's page shows the business plan at $53/mo billed annually versus $64/mo monthly. Third-party reviews list the agency plan at $331/mo on annual billing. Both work out to roughly two months free.

**Can I cancel or downgrade later?**

Plans are month to month with no contract, so yes. There are no refunds on charges already made.

---

The short version: CloseBot's agency pricing is a platform fee plus four rebillable usage meters, and it only makes sense if you have enough client volume for those meters to produce margin. Under a few thousand messages a month across your book, or with clients who never touch the portal, 👉 [the $64 business plan](https://app.closebot.com/a?fpr=li87) does the same job for a fraction of the subscription. Above that, the rebilling dashboard is where the money is, and 👉 [starting on the agency trial](https://app.closebot.com/a?fpr=li87) is the only way to see whether your client list can actually support it.
