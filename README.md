# Lovable pricing: how credits, grants and plans actually work

*Unofficial community guide for Lovable pricing. Not affiliated with Lovable. All trademarks belong to their owners.*

Lovable pricing is credit-based, and most of the confusion people run into comes from mixing up three different pools: the daily build grant, the monthly Cloud grant and the paid credit balance. This guide collects what Lovable's own pricing page and documentation say about each pool, how credits are consumed, when they expire and what happens when you cancel, so you can estimate what a project will cost before you start typing prompts.

> Building a static marketing site or an Expo app and you mainly want the files? [Try Begin.sh - turn a prompt or a URL into a downloadable static site or Expo app](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=lovable-pricing&utm_content=readme-top&utm_term=tier-r). There is no hosting, backend or auth layer, so there is no balance to watch for running the app afterwards.

## What Lovable is

Lovable describes itself as an AI software engineer: you chat with it and it builds websites and web apps, with no technical knowledge required. A June 2025 write-up in The Bill, Please (Lago's newsletter) reported that the Stockholm-based company reached $75m ARR seven months after launch with roughly 35 people.

Everything you do in Lovable is metered in credits: building by sending messages, running deployed apps on Cloud, and powering AI features inside the apps you ship. Two details are easy to miss. Every plan belongs to a workspace, and everyone invited into it shares its credits. And the value of a credit and the rate at which it is consumed depend on the plan and the feature, so credits are not necessarily worth the same across plans.

## Getting started

1. Create an account at [lovable.dev](https://lovable.dev/signup?redirect=%2Fpricing). Starting to build is free.
2. Your free workspace receives a daily grant of 5 build credits (up to 30 a month), a monthly grant of 20 Cloud credits, and 4 credits for AI features built into user apps.
3. Pick a building mode. Default mode charges a variable number of credits based on task complexity; Plan mode charges 1 credit per message.
4. Check what each message cost by hovering over the three dots of a message in the message history.
5. When the daily grant becomes the bottleneck, look at the paid tiers on the [pricing page](https://lovable.dev/pricing). Pro and Business are the named self-serve tiers; there is also an [Enterprise](https://lovable.dev/enterprise-landing) offering.

## Pricing and limits

The pricing page does not expose per-plan dollar amounts in a form that can be quoted reliably here, so check the [pricing page](https://lovable.dev/pricing) for current rates. What the page and the [credits and usage docs](https://docs.lovable.dev/introduction/credits-and-usage) do state:

- Free plan: daily grant of 5 build credits (up to 30 a month), monthly grant of 20 Cloud credits, and 4 credits for in-app AI features.
- Paid plans: the plan's credits are added to your balance monthly and can be spent on building, Cloud and in-app AI features. Subscriptions keep the daily grant of 5 build credits (some regional plans cap this at 30 per month) and the monthly 20 Cloud credits; Pro and Business also include grants for building and hosting with Cloud.
- Building cost by mode: Default mode varies with complexity, Plan mode is 1 credit per message.
- Published example costs: make the button gray, 0.50 credits; remove the footer, 0.90; add authentication with sign up and login, 1.20; build a landing page with images (3 generated images, a theme and 5 sections), 1.70.
- Expiry: monthly plan credits expire two months after they are issued; annual plan credits expire one month after the annual period ends; top-up credits last twelve months from purchase; daily build grants expire at the end of each day and do not roll over.
- Refunds: credits are not refundable or redeemable for cash.

## Practical notes and gotchas

1. Use Plan mode when you are thinking and Default mode when you are editing. Plan mode is a flat 1 credit per message; Default mode is where the variable costs live.
2. The daily 5 build credits are use-it-or-lose-it. On the free plan, small edits spread across days stretch the 30-a-month ceiling further than one long session.
3. Hosting is not free in credits. A deployed app on Cloud draws from the 20 monthly Cloud credits and, on paid plans, from the balance. Budget for running the app, not only building it.
4. Cancelling does not delete your balance immediately. You keep remaining credits until the end of the billing period, then the workspace drops to Free; unused paid credits reactivate if you re-subscribe before they expire.
5. Credits are shared per workspace, so one heavy user can drain a team's balance. To fund a class or community, upgrade one workspace and invite people into it.
6. The example costs are examples, not a rate card. Hover the message to see the real number.

## Comparison

| | Lovable Free | Lovable Pro / Business | Begin.sh |
| --- | --- | --- | --- |
| What you build | websites and web apps by chat | same, with a monthly credit balance | a static site or an Expo app from a prompt or a URL to clone |
| Build allowance | 5 build credits a day, up to 30 a month | plan credits monthly plus the daily grant | output is a zip you download |
| Hosting | 20 Cloud credits a month | 20 Cloud credits a month plus Cloud grants | none, you host the files yourself |
| Backend and auth | Cloud and in-app AI features | same | none by design |
| Credit expiry | daily grants expire end of day | monthly credits expire two months after issue | no credit balance to expire |

## FAQ

**Is Lovable free to use?** Yes, starting to build is free. The free plan gives 5 build credits a day (up to 30 a month), 20 Cloud credits a month and 4 credits for in-app AI features.

**What does one message cost?** In Plan mode, 1 credit. In Default mode it depends on the task: the published examples range from 0.50 credits for a style change to 1.70 for a landing page with generated images.

**Do unused credits roll over?** Daily build grants do not. Monthly plan credits last two months after issue, annual plan credits one month after the annual period ends, top-ups twelve months from purchase.

**Can I get a refund on credits?** No. Credits are not refundable or redeemable for cash.

**What happens if I cancel?** You keep remaining credits until the end of the billing period, then the plan switches to Free. Unused paid credits come back if you re-subscribe before they expire.

## When Begin.sh is the better fit

Lovable is a good match when you need a running web app with a backend, hosting and AI features, paid for from one credit balance. If your job is narrower, a landing page, a documentation site, a portfolio or an Expo app prototype, and you want to own the files rather than keep a balance topped up, [Try Begin.sh - turn a prompt or a URL into a downloadable static site or Expo app](https://begin.sh?utm_source=github&utm_medium=ugc&utm_campaign=lovable-pricing&utm_content=readme-top&utm_term=tier-r). Describe the site or paste a URL to clone, download the zip, and host it wherever you already host things. No hosting, backend or auth is bundled, so nothing keeps consuming credits after the build is done.
