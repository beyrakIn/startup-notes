# Company Culture & Building a Team, Part II (Lecture 11)

> Source: Stanford CS183B, Lecture 11 (Oct 28, 2014). Panel: Ben Silbermann (Pinterest), Patrick & John Collison (Stripe), moderated by Sam Altman.
> Transcript: https://genius.com/Patrick-collison-lecture-11-company-culture-and-building-a-team-part-ii-annotated
> The practitioner's sequel to [Culture & Team (I)](10-culture-and-team-part-i.md).

The applied half: hiring the first ten, spotting talent when you're inexperienced, onboarding, and scaling culture from 2 → 1,000.

---

## The core pieces of culture
- **Ben (Pinterest):** four dimensions — *who you hire* (and what they value), *what you do every day and why*, *what you communicate*, and *how you celebrate.* (The converse is what you punish — but running on celebration beats running on punishment.)
- **John (Stripe):** heavy emphasis on internal **transparency.** If everyone believes the mission and has a clear picture of the company's state, you work productively — and it *forgives* a lot of what breaks as you grow. At 170 people that's a firehose, so it needs tooling.
- **Patrick (Stripe):** **culture is the resolution to a bandwidth problem.** You can't be in every decision; as headcount grows, the fraction you're in shrinks exponentially. **Culture is the invariant you maintain** as you step out of more and more decisions.

---

## Hiring the first ten

![Your first 10 hires are really your first 100](assets/first-ten-multiplier.svg)

> The first ten hires aren't ten — **each brings ~ten more, so you're really choosing the next 100.** Think about which 90 you want them to bring.

- **It's brutally hard.** Nobody's heard of you; friends tell recruits *not* to join (Stripe's second employee's friends ran a "full-on assault" the night before — he joined anyway). No later batch of ten matters as much.
- **It's not a LinkedIn dollar menu** — it's a long slog through friends-of-friends. **No wrong place to find people:** Craigslist ads, tech talks, office BBQs, the coffee shop next door. The good ones are busy doing something else — *go seek them out.*
- **Have a great elevator pitch** — everyone you meet is a recruit 6–12 months out. Recruiting takes forever, so get them excited early.

### Hire like a value investor

![Hire like a value investor: find undervalued human capital](assets/value-investor-hiring.svg)

> Look for **human capital the market undervalues.** Don't chase already-discovered Google/Facebook stars (harder to convince anyway). You can relax *one* constraint — relax **how apparent the talent is, never the talent itself.**

Stripe's early hires were **early-career or undervalued**: an 18-year-old designer in Sweden, a CTO still in college. The traits both teams converged on:

| Team | Traits they hired for |
|---|---|
| **Pinterest (Ben)** | works hard · high integrity · **low ego** · creative & curious (quirky hobbies) · wants to build something *bigger than themselves* |
| **Stripe (Collisons)** | **genuine/straight** (trusted, intellectually honest) · **care a great deal** (offended when something's a little off) · **finish things** (many love starting; few love completing) |

(Stripe's caring-too-much: every API error paged all of them; they cc'd each other on typos. They're skeptical of GitHub-resume hiring — they'd rather someone went *deep* in one area for two years.) And avoid an **overly niche idea** — "build a rocket to Mars" is easy to recruit for; a narrow class-project idea is not.

---

## Identifying talent when you're inexperienced
- **You never know 100% until you work together.** If it's not a fit, you owe them feedback — then fire.
- **Define "world-class" first.** Before interviewing for a discipline you don't know, call people who *are* world-class and ask: what traits, what questions, and *where does the next great one work right now?*
- **Don't whitewash the risk.** Great people want hard problems (PayPal: "Mastercard wants to kill us"; iPhone: "you won't see your families for three years, but your kids' kids will remember"). The right people self-select **in**; the wrong ones select **out.**
- **Interview your own way** (John) — don't co-opt whiteboard rituals if that's not your strength. Stripe flew a candidate out and *coded with him for a weekend*; for business roles, give a real project. Beat interviewing **imposter syndrome.**
- **Work with the first ten before hiring** (Patrick) — a week if you can; it's hard to fake for a week. Forget "10×" — ask **"is this the best engineer this engineer knows?"**
- **Reference aggressively** (Ben) — not to verify the resume (assume it's true) but to learn what they're like to work with. **Force scarcity:** "top 1%, 5%, or 10% of people you've worked with?" and "if I asked Jonathan what you're best at, what would he say?" (creates social accountability). Spend ~15 minutes; don't accept "they're awesome." (References are also a great recruiting source.)

> Remember: in media we over-focus on founders, but **~99% of what the company does is done by people who aren't you.** (Steve Jobs was "a tiny part at the end.")

---

## Onboarding — make them effective fast
- **Ben:** early on it's magical (a tiny apartment, "here's your computer, this is our problem"). Always reconnect people to the **long-term vision** so they don't think the world is the small problem in front of them. As you scale, *formalize* it: a day-0 → 30-day checklist (do they know their manager, team, the company's arc and top priorities?), measured by asking the new hire *and* their peers/manager "is this person up to speed?" If not, **stop hiring and retool.** And get to know people *as people* (aspirations, working style, how they like recognition).
- **John:** two things at any stage — **(1) get them doing real work fast** (engineers commit day one; business folks in real meetings day one — push off the cliff, don't ease in); **(2) give feedback quickly** (adapting to a strong culture is hard — Stripe's heavily *written*, headphones-on, IM-everything style jars people from "normal places"). Telling people how they're doing is unnatural, but you owe it to them.

---

## Scaling 2 → 1,000
- **Ben:** make teams **autonomous and nimble — "a startup of many startups,"** each owning its resources and one clear metric, so management decomposes into tractable atomic units. Pinterest bundles a strong designer + lead engineer + writer + community lead per project. And **referrals become the lifeblood** — a great early move was hiring a **professional recruiter as employee ~#14**, who taught everyone to screen for *culture*, not just talent.
- **Patrick:** once you don't fail fast, **all your problems become management-growth problems.** **Time horizons stretch** — in month 1 you plan a month out; by month 11 you should plan a year out; by year 4, four years. So early you must hire people productive *immediately*; after 2–3 years you can (and should) invest in promising people who take a year to ramp. Growing 2–3 heads/year is unnatural — be systematic about the **least-bad way** to manage it (e.g. three meals a day at long communal tables for random human mixing).

### Transparency at scale (Stripe)
A startup is an organization **not yet stuck with principal-agent problems** — everyone rows the same way, so information can be open (unlike a big company where locally-optimal ≠ globally-optimal). Stripe bcc'd everyone on email → mailing lists → a Gmail-filter-generating program (Gmail literally broke from the volume). Scaling it took **new tools** (weekly all-hands now that you can't read every email) *and* **social norms** (what's confidential; when it's okay to jump into a 170-person thread — "drive-by criticism" causes stage fright and silences people).

---

## Sharp Q&A nuggets
- **Do early hires become leaders?** Stripe: yes — developing management is an unnatural skill the company must build. Ben: some yes, some no — give people a shot, but make it **not one-way** (returning to IC mustn't feel like failure, or fear kills risk-taking).
- **Most startups aren't the iPhone — why would anyone sacrifice to join?** Patrick: it resonates *because* it's not guaranteed; the sacrifice is overstated ("the startup version of fishing" — realistically ~2 extra hours/day, not forgoing all joy for five years). Ben: don't pretend you have a crystal ball — be honest about what's exciting *and* hard and why their role is instrumental. **Red flag:** a "passionate" candidate also interviewing at 7 unrelated companies at the same stage is signing up for an *experience*, not a *goal* — they won't stick when it's hard. And a startup offers real **personal development**: lightly staffed and unforgiving, so you can actually measure your impact.
- **User base & hiring?** You don't only hire religious daily users (fine for an API). Screen for people who share the vision and care about the mission. But **hiring passionate users is a great early edge** — Stripe hired four users it couldn't have gotten otherwise.

---

## My action items
- [ ] **First 10 = 100:** Am I treating each early hire as the seed of the next ten?
- [ ] **Value investor:** Am I seeking undervalued, early-career talent rather than fighting over discovered stars?
- [ ] **Three traits:** Genuine, cares a great deal, finishes things — am I screening for all three?
- [ ] **References:** Am I forcing scarcity ("top 1/5/10%?") instead of accepting "they're great"?
- [ ] **Onboarding:** Real work on day one, fast feedback, and a 30-day "are they up to speed?" check.
