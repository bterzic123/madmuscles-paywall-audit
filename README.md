# Paywall Audit — MadMuscles

**Live:** https://bterzic123.github.io/madmuscles-paywall-audit/

Four ranked paywall ideas for MadMuscles: Workouts & Diet, each backed by a number from Adapty's
State of Paywalls 2026, plus a scorecard of the live paywall against the report and a clickable
rebuild of the main paywall and the close moment, in MadMuscles' own design (Today / Proposed).

## The ideas

| # | Idea | Report anchor | Outcome |
| :-- | :-- | :-- | :-- |
| 1 | Open on your 6-month plan | Health & Fitness: annual pre-selected on 63.5% of paywalls, 62% of revenue; plan-duration tests raise LTV in 59% of tests | Report finding (no lift range) |
| 2 | Offer a smaller first step on close | Only 4% of apps show a second paywall; converts at 0.88× the main one, beats it in 45% of apps | ARPU +10–15% · based on Adapty data |
| 3 | Put their answers in the headline | Only 2% of top paywalls personalize; onboarding personalization in winning tests | CR +8–17% · observed in winning A/B tests |
| 4 | Show your 4.4 where the price is | Only 27% of top paywalls show social proof; social proof on the paywall in winning tests | CR +10–30% · observed in winning A/B tests |

**Benchmark slice:** Health & Fitness, US (MadMuscles' largest App Store market). Category-wide
figures are labelled as such. App Store data, Oct 2025–Sep 2026.

**Report:** [State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=madmuscles)

## Grounding

Every price on the paywall and the offer sheet (9,99 € / 19,99 € / 29,99 € / 129,99 €) comes from
MadMuscles' live paywall as recorded in October 2026. The 4.4 rating and 134K ratings come from the
US App Store listing, and the quote is a verbatim App Store review. The offer sheet introduces no
new price or discount. Impact ranges are observed lifts from winning A/B tests in State of Paywalls
2026 and Adapty's own data, not measured lift for MadMuscles.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000. Add `?open=proto` to land on the prototype and `?for=<name>` to
change the name in the prototype.
