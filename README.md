# Trade with MAK — Building and Running a Paid Trading Community (2021–2023)

A business case study of MAK Trading LLC ("Trade with MAK"), a paid day-trading community I co-founded (Kansas LLC, 50% owner) and ran as the public face from 2021 to 2023.

## What it was

Trade with MAK was a subscription community for options day traders. Members paid a monthly fee for access to a private Discord server where I livestreamed my trading during market hours, posted real-time trade alerts with entries and exits, ran daily market analysis, and published recap videos after the close. Around that core sat an education arm (MAK Trading School), weekly chart reviews with member requests, options-flow and news feeds, and small-account-focused coaching.

## Timeline

- **Late 2021** — Brand development and groundwork: logo and identity work, Discord server build-out, content templates, early social presence.
- **January 2022** — Public launch. Subscriptions ran through LaunchPass and Stripe, gating the Discord server. Launch marketing included an early-bird promotion ($29.95/month for the first three months against a regular price of $89.95/month), a launch review contest, and a MacBook community contest.
- **2022** — Growth and product development: the trading school curriculum, the livestreamed $25k-to-$100k account challenge (see the companion `mak-25k-challenge` repo), daily video recaps, Sunday talks, and a steady promotion calendar (Black Friday, Christmas, and other seasonal campaigns under the later "MAK — Trade with the best" branding at TheMAKtrading.com).
- **Late 2022** — Migration from LaunchPass to a self-hosted WordPress site with MemberPress handling subscriptions, giving the business direct control of billing, onboarding, and content delivery.
- **2023** — Wind-down of the community and the LLC.

## Scale

- Peak of **245 subscribers at $89.95/month** during the LaunchPass/Discord era.
- The later MemberPress site ran with **130–176 members**.

No revenue, P&L, or member-level data is published in this repository.

## What I built

- **Community operations** — Discord architecture (trading floor, trade log, alert channels, options flow, news, bot integrations, live voice for market hours), moderation and admin team, member onboarding, contests and member-recognition programs.
- **Content pipeline** — a repeatable daily cycle: premarket analysis and audio, live trading with commentary, real-time alerts, after-hours commentary docs, and edited daily recap videos; plus weekly charts and watchlists.
- **Brand** — the tradewithMAK identity in this repo's `brand/` folder, and the later "Trade with the best" refresh; all campaign creative in `marketing/`.
- **Education** — a structured curriculum for options basics, account and risk management, and trade setups (see the `mak-trading-school` repo).
- **Commerce stack** — LaunchPass + Stripe at launch; later WordPress + MemberPress with coupon-driven campaigns (early bird, Black Friday, seasonal promos).

## What I learned

- **Retention is the business.** Acquisition promos fill the top of the funnel, but a paid community lives or dies on the daily content cadence. The days I showed up consistently were the days the community stayed.
- **Transparency sells better than claims.** Livestreaming real trading — including losses — built more trust than any marketing asset. That insight became the 25k challenge product.
- **Owning the stack matters.** Moving from LaunchPass to MemberPress traded convenience for control of billing, pricing experiments, and member data — worth it, but migration has real churn costs.
- **A one-person content engine has a ceiling.** Being the founder, trader, educator, editor, and support desk at once caps growth and burns out the founder; systems and delegation should come earlier.
- **Community data is a liability as much as an asset.** Everything in this public repo was screened so that no member names, handles, or account data appear; internal archives with member information stay private.

## Repository contents

- `brand/` — final logo and banner assets (light/dark banners, square and wide transparent marks).
- `marketing/` — representative campaign creative from launch (January 2022) through Black Friday 2022: early-bird banner, premium comparison sheet, launch review contest, standard join banner at the $89.95 price point, MacBook contest, and the Black Friday poster.
