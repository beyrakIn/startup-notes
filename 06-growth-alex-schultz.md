# Alex Schultz — Growth (Lecture 6)

> Source: Stanford CS183B, Lecture 6 (Oct 9, 2014). Alex Schultz (VP of Growth, Facebook).
> Transcript: https://genius.com/Alex-schultz-lecture-6-growth-annotated
> The growth engine bolted onto [[04-product-users-growth-adora-cheung]]'s retention foundation.

Schultz did physics at Cambridge, then paid for college doing SEO and AdWords→eBay affiliate arbitrage. His definition of "growth" is unglamorous: **internet marketing using whatever channel gets the output you want.** The lecture has three parts: **retention** (the foundation), **operating for growth** (North Star · magic moment · marginal user), and **tactics**.

---

## Part 1 — Retention is the foundation
Great product → customers → they spread the word → **retention.**
> **"Retention is the single most important thing for growth."**

- **The retention curve** = % monthly active vs. days since acquisition. If it goes **asymptotic to a horizontal line** → you have a viable business and product-market fit (for some subset of the market). If it **slopes down and hits the X-axis** → no business. *(See the cohort curves in [[04-product-users-growth-adora-cheung]].)*
- **The cohort method works with ~10k users:** of users on day 1, what % are monthly active? Day 31, 32, 33… does it flatten? (Facebook predicted an advertiser's 1-year value to **97%** within 90 days of a 3-day-old product.)
- ⚠️ **If the curve doesn't flatten, do NOT run growth tactics** — no virality, no growth hacker. Fix product-market fit first. The #1 problem for both Facebook's new products and startups: **they think they have PMF and don't.**

### What's "good" retention? Use dimensional reasoning
Don't ask — estimate it (the G.I. Taylor story: he derived the atomic bomb's yield from one *Life* photo). Ballpark = usable internet users ÷ active users:

| Vertical | "Good" terminal retention |
|---|---|
| E-commerce | ~20–30% monthly active → you'll do very well |
| Social | first cohort must be ~80% retained, or no massive social site |

Find a comparable company in your vertical and ask: *am I anywhere close to what real success looks like here?*

---

## Part 2 — Operating for growth

![Operating for growth: North Star, Magic Moment, Marginal User](assets/operating-for-growth.svg)

> **Contrarian rule: a startup should NOT have a growth team. The whole company is the growth team, and the CEO is the head of growth.**

### 1. North Star metric
One number everyone drives toward — **set by the leader.** Past one person you have no control, only influence; the North Star makes the right priority clear *when you're not in the room.*

| Company | North Star | Not… |
|---|---|---|
| Facebook | **monthly active users** (Zuck published *active*, never *registered*) | sign-ups |
| WhatsApp | **sends** | downloads |
| Airbnb | **nights booked** | — |
| eBay | **gross merchandise volume** | revenue |

Pick one aligned with your mission — most metrics correlate (DAU↔MAU, content shared↔users), so choose one you'll commit to.

> **eBay 2004:** switched affiliate payouts from CRU (confirmed registered users) → **ACRU** (activated: confirm *and* bid/buy/list). Lost ~20% of CRUs but only ~5% of ACRUs, and ACRU growth *accelerated.* Why? Chasing CRUs dumps people on the registration page; chasing ACRUs lands them on the **search results** page — they see the thing they want, get excited (the magic moment), then register.

### 2. Magic moment
The instant a user gets hooked — get them there **as fast as possible.**

| Product | Magic moment |
|---|---|
| Facebook | **seeing a friend's face** → drove "10 friends in 14 days" |
| eBay | finding that collectible · a seller's first payment |
| Airbnb | finding that first cool listing · walking through the door · first payment |

LinkedIn, Twitter, WhatsApp all front-load showing you people to connect with. Connecting users to the magic moment moves the retention asymptote up (60% → 70%).

### 3. Optimize for the marginal user — not yourself
> Building a great **product** = optimize for power users. Driving **growth** = optimize for the **marginal user.**

The notifications trap: power users aren't churning over too many notifications (they can filter). The user who matters is the **marginal one** — low friend count, churning or resurrecting. **Growth accounting** = new + resurrected (back after 30 days) + churned; resurrected and churned *dominate* new once you're a few years in. Those users had low friend counts → get them to ~10 friends.

> **Everything has to come from the top.**

---

## Part 3 — Tactics
"Build it and they will come" is **false** — you have to do the work. (Pinterest grew via *marketing*, not just engineering.)

### Internationalization
Facebook internationalized **too late** — local clones (StudiVZ's literal `Fakebook.css`, Mixi, Cyworld, Orkut) were the barrier. Growth came from **knocking down barriers** (college-only → high schools → everyone → 50M → brick wall → the growth team forms). They did it right by:
- **Moving slow to move fast** — built the FBT string-extraction tool + a **community translation platform** (French in 12 hours; 104 languages, 70 community-translated).
- **Prioritizing the right languages** for where the world is *going*, not where it is (Hindi quadrupled). Building for today's distribution is an easy, costly mistake.

### Virality (Sean Parker's model)

![Virality = payload × conversion × frequency](assets/virality.svg)

> **Virality = payload × conversion rate × frequency.**

| Product | What drove it |
|---|---|
| **Hotmail** | low payload, **high frequency** (same people, repeatedly) + **high conversion** ("PS: get your free email") |
| **PayPal** | **high conversion** (who refuses money? + $10 referral) — viral mechanism was *eBay* |
| **Facebook** | **word of mouth** — no native way to reach non-users; grew because the product was worth telling friends about |

- **Remove friction** (online ad vs. a billboard URL you must memorize).
- **Frequency ↔ conversion:** the more you hit someone with the *same* message, the less they convert → rotate creatives (creative exhaustion).
- **K-factor funnel** (Ed, now Uber): import contacts → invites sent → clicks → sign-ups → import. Multiply the rates; **K > 1 = viral.** But **K > 1 with bad retention is worthless** — only chase virality *after* strong retention.

### SEO — three things
1. **Keyword research** — supply (who else ranks) × demand (search volume) × value. (His cocktail site ranked "cocktail making," ~500 searches/mo, instead of "cocktail recipes"/"drink recipes." Wrong word.) Best tool: Google Keyword Planner.
2. **Links** — valuable links from high-authority sites (PageRank). White-text-below-the-fold is long dead.
3. **Internal linking** — distribute the "link love." Facebook's public profiles were buried and got no traffic; adding a **directory** so Google could reach every page **100×'d** SEO traffic. (Plus table stakes: XML sitemaps, headers.)

### Email / SMS / Push — all behave the same
- **Deliverability first** — *"to finish first, first you have to finish."* Don't spam, avoid dirty/shared IPs, respect hard bounces (retry once or twice, then stop). Grey-route SMS always gets shut down. Spam your power users and they opt out — and you can **never reach them again.**
- **Newsletters are stupid** (same message to everyone regardless of tenure). The most effective sends are **notifications + triggered campaigns**: a new user's first "like" is a magic moment (turn notifications on for *low-engaged* users only); eBay's "first cross-border transaction" trigger email had the best CTR.
- Then optimize **open rate** (subject line) and **click rate**.

---

## Closing
> Patton: *"A good plan, violently executed today, is better than a perfect plan tomorrow."*

Move fast, don't be afraid to break things. Run more experiments than the next person, fight for every extra user. Zuckerberg: *"we won because we wanted it more."* Not crazy-smart — just worked really hard and executed fast. **"Growth is optional."**

---

## My action items
- [ ] **Retention first:** Does my cohort curve flatten? If not, I stop all growth tactics and fix PMF.
- [ ] **North Star:** One metric, set by me, that everyone can drive toward without me in the room.
- [ ] **Magic moment:** What is it, and how fast can I get a new user there?
- [ ] **Marginal user:** Am I optimizing growth for the churning/low-engagement user, not myself?
- [ ] **One channel:** Pick a tactic (virality / SEO / notifications), nail deliverability, and run more experiments than anyone.
