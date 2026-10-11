# Growth Audit — Clean Manager

**Live:** https://plykhvar-glitch.github.io/cleanmanager-flow-rebuild/

Five ranked ideas for Clean Manager’s onboarding and paywall, plus a clickable prototype of the flow rebuilt in Clean Manager’s own design: the black screens, the blue pill, the Photos and iCloud tiles with red badges, the three story screens, the trial toggle and the payment timeline. The new screens (photo access, scan, result, offer on close) are built from parts of the app people already know: the Storage card with its coloured bar, the red GB pills, the Before / After card, the red checkboxes and the two-line Delete button. The overview uses the royal blue and black cards of Clean Manager’s App Store page.

Open it on a phone and the prototype runs full-screen. The toolbar above the phone switches English / French / German and light / dark, and plays a 30-second walkthrough.

## The five ideas

| # | Idea | Potential outcome |
| :-- | :-- | :-- |
| 01 | Show their own scan before the price | CR +10–20% |
| 02 | Put their gigabytes in the paywall headline | CR +15–20% |
| 03 | Offer the year when they close | ARPU +10–15% |
| 04 | Explain photo access before iOS asks | CR +5–15% |
| 05 | Put your 4.2 rating beside the button | CR +10–15% |

## Where the numbers come from

Every price, rating and feature line comes from Clean Manager’s own App Store listing, its in-app purchase list and its in-app screens: 9,99 € a week with a 7-day trial (the paywall), the Yearly subscription at 31,99 € (French App Store) and 29,99 € (German App Store), and 4.2 stars from 13K ratings (US App Store). The library figures in the prototype (photos, videos, gigabytes found) are a sample; on a device they come from the scan the app already runs.

Impact ranges are Adapty’s expected effect from teardowns and A/B tests across subscription apps — not measured lift for Clean Manager.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.
