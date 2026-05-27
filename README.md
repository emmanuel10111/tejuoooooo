# PCH Shopping — Complete Website Replica
### 19-Page Fully Linked Multi-Page Website

Open `start.html` in any browser. No server or install needed.
Images load from the live PCH CDN (internet connection required).

---

## File Structure

```
pch-shopping/
├── start.html              <- Homepage + 
├── start.html              <- Homepage + auto-popup spin wheel
├── shop.html               <- Product listing with filters & sorting
├── product.html            <- Product detail (dynamic via ?id= param)
├── giveaways.html          <- All giveaways with live countdowns
├── giveaway-1million.html  <- $1,000,000 SuperPrize detail page
├── giveaway-jeep.html      <- Jeep Wagoneer detail page
├── giveaway-bmw.html       <- BMW 230i detail page
├── giveaway-subaru.html    <- Subaru Outback detail page
├── memberships.html        <- Gold / Platinum / Diamond plans
├── winners.html            <- Winners Circle + Hall of Fame
├── cart.html               <- Cart with localStorage persistence
├── login.html              <- 4-step signup (email/OTP/profile/payment)
├── faq.html                <- Accordion FAQ (15 questions)
├── contact.html            <- Contact form + support info
├── refund-policy.html      <- 30-day return policy
├── shipping-policy.html    <- Shipping options & timelines
├── official-rules.html     <- Full sweepstakes rules + free mail entry
├── privacy-policy.html     <- Data & privacy policy
└── shared.css              <- Shared header/footer/nav styles
```

---

## Key Features

- Auto-popup Spin Wheel opens 1.5s after every page load
- Spin prizes:$200,000 / $5,000 / $10,000 / $25,000 / $50,000 / $100,000 / $250,000 / $500,000 / $1,000,000
- Full confetti animation on win
- Cart persists across all pages via localStorage
- 4-step login: Email -> OTP -> Profile (name/address/ZIP) -> Card info
- Live countdown timers on all giveaway pages
- All 18 pages fully linked — zero dead links
- Fully responsive on mobile, tablet, desktop

## Notes

- Images load from live PCH CDN (needs internet)
- OTP code is shown on-screen in demo mode
- Payments are simulated — no real charges
