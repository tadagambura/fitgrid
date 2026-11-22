# FitGrid: Spec

**Rank in portfolio:** #15 of 15 (easiest → hardest) · **Difficulty:** Medium

## One-liner

Your wardrobe in your pocket: build outfits and plan what to wear.

## Problem / audience

- **Who it's for:** Fashion-conscious users who want to wear more of what they own.
- **The problem it solves:** People forget what they own and rebuy; planning outfits is hard.

## MVP features (ship with only these)

1. Photograph clothes, add to a digital wardrobe
2. Background removal for clean item images
3. Build outfits from items
4. Plan outfits on a calendar

## Not in MVP

- Weather-based suggestions
- Seasonal analytics (cost per wear, most worn)
- Higher wardrobe limits

## Monetisation

| Model | Detail |
|---|---|
| Free | Limited wardrobe size |
| Paid | £4.99/month: unlimited wardrobe, planner, analytics |
| Ads | None or minimal |

Prices are starting points from the portfolio brief; test before committing.

## Platform & stack

- **Platform:** Expo (camera) + storage backend for photos.
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob). See the portfolio roadmap.
- **Data:** Photos: device first; cloud backup costs money, so it should be premium.

## Growth engine hooks

- **Shareable output:** Outfit boards and outfit-of-the-day posts.
- **Content pillars:** Outfit ideas; Capsule wardrobes; Cost per wear; Style from what you own

## Notes

Most moving parts: camera, image processing, photo storage costs. Last on the list for a reason.

## Launch checklist

- [ ] Name checked on App Store / Play Store / trademark search
- [ ] MVP features done and tested
- [ ] Privacy policy + terms
- [ ] Landing page
- [ ] Analytics wired
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
