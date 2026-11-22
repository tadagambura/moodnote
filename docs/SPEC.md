# MoodNote: Spec

**A 30-second check-in that shows your patterns** · #8 of 31 · Wave 1: Daily keepers · Used: Daily · Medium · Revenue potential: Medium · Habits, Health & Learning · Source: Perplexity

## One-liner

Log mood, energy, sleep and stress in one tap a day, add optional tags (work, exercise, period, medication), and see what lines up with your good and bad days. Export your history for a GP or therapist.

## Problem / audience

- **Who it's for:** People managing stress, burnout, ADHD, cycle symptoms or anxiety, or simply wanting more self-awareness.
- **The problem it solves:** It's hard to spot what affects your mood and energy, or to explain it to a professional.
- **Example:** A user notices that poor sleep and skipped lunches come before most of their low-energy days.

## MVP features (ship with only these)

1. One-tap daily check-in: mood, energy, sleep, stress
2. Optional tags and a short note
3. Weekly patterns
4. Exportable history
5. Gentle reminders, with no streak pressure

## Not in MVP

- Correlations ('low energy follows short sleep')
- Cycle-aware view
- Private journal lock

## Monetisation

| Model | Detail |
|---|---|
| Free | Check-ins and 30 days of history, with ads |
| Premium | £3.99/month: unlimited history, correlations, exports, lock |
| Ads | Contextual only, never targeted using health data |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Gentle daily check-in reminder |
| Tiny win | 30-second check-in |
| Progress | Patterns and insights (deliberately not streaks) |
| Share | None by default (private) |
| Next step | Weekly insight |
| Cadence | Daily |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Calm.** Gentle, kind humour and smooth motion: a stickman yawning after a shift, a fly escaping an empty pocket. No drama, nothing that adds stress.

- Check-in: the meditating stickman floats up and a bird lands on his head
- Good day: his aura glows warm and he gives a sleepy smile
- Rough day: a little cloud appears and he offers it an umbrella and a cup of tea
- Weekly insight ready: he unrolls a tiny scroll
- Sleep logged: he yawns and curls up under a blanket

**Line we don't cross:** No celebrations or reactions to mood scores, ever.

## AI

**Light (opt-in).** Optional weekly reflection written from your check-ins. Opt-in only, premium, no identifying data sent. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app.
- **Data:** On the device only; health-related data needs extra care.
- **Backend:** AI proxy for the optional weekly reflection (premium). Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Energy and sleep; Burnout awareness; Self-awareness tips
- **Shareable output:** None by default (private)

## Risks

Sensitive health data: no ad tracking on it, strong privacy, no medical claims, and signposting to real support. Deliberately no guilt streaks.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
