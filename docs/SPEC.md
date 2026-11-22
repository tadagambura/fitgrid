# FitGrid: Spec

**Your wardrobe in your pocket** · #25 of 33 · Wave 2: Recurring keepers · Used: Daily · Harder · Revenue potential: Medium · Social, Play & Style · Source: ChatGPT

## One-liner

Photograph your clothes to build a digital wardrobe, put together outfits and plan what to wear by day, weather or occasion. See what you actually wear and what's just taking up space.

## Problem / audience

- **Who it's for:** Fashion-conscious users who want to wear more of what they already own.
- **The problem it solves:** People forget what they own, rebuy similar items and struggle to plan outfits.
- **Example:** On Sunday a user plans a week of work outfits from clothes they already own.

## MVP features (ship with only these)

1. Photograph items into a digital wardrobe
2. Background removal for clean item images
3. Build outfits
4. Outfit calendar
5. Most and least worn

## Not in MVP

- Weather-based suggestions
- Cost per wear (links to WorthIt)
- Pack from your wardrobe (links to PackRight)

## Monetisation

| Model | Detail |
|---|---|
| Free | Up to 30 items |
| Premium | £4.99/month: unlimited wardrobe, planner, analytics |
| Ads | None or minimal |

Prices are starting points; test before committing.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Morning outfit-of-the-day prompt |
| Tiny win | Pick today's outfit |
| Progress | Outfits planned; wear stats |
| Share | Outfit boards |
| Next step | Seasonal wardrobe review |
| Cadence | Daily |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app (camera) + photo storage.
- **Data:** On the device first; cloud backup is premium because it costs money.
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Outfit ideas; Capsule wardrobes; Style what you own
- **Shareable output:** Outfit boards

## Risks

Camera, image processing and storage costs make it the hardest to build and run.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
