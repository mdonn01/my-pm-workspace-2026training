# Decision Brief: Streakly Comeback Problem

*For: Marcus, Head of Product — 2026-09-28*

## Situation

Streakly's Day-7 retention has dropped 9 points (48% → 39%) since the streak v2 redesign, driven mostly by users who break a streak in week 1 and never return. User interviews and NPS feedback both converge on the same root cause: the all-or-nothing streak reset, not the underlying lesson content, is what's pushing people away.

## Key Findings

- The all-or-nothing streak reset is the single largest complaint theme in NPS feedback (7 of 10 respondents), and interview subjects describe it as the direct cause of quitting — even users with real investment (a 12-day streak, five weeks in) walked away the moment it broke.
- Streak anxiety starts before any break occurs — a user just 4 days in was already anxious about losing everything, suggesting the mechanic may suppress week-1 engagement independent of an actual break.
- Users explicitly want the product to act like "a coach, not a scorekeeper" — asking for something that helps them recover, not just a reset.
- Notification strategy is a real but secondary issue (3 of 10 NPS mentions): some users are over-notified and disable reminders entirely, while others feel forgotten — a one-size-fits-all fix would help one group and hurt the other.
- Competitively, streak-freeze/repair mechanics are now table stakes (Duolingo, Elevate, Busuu all have them), but every competitor uses them only to *prevent* a break — none offer a graceful comeback experience for a user who has already broken a streak, leaving that moment unclaimed.

## Options Considered

1. **Build the Comeback screen** (best-streak stat + short comeback lesson + one-tap streak-freeze) — directly targets the top-cited pain point and claims the unowned "after the break" moment.
2. **Ship streak-freeze/repair only** — matches competitor parity, likely faster to build, but only prevents future breaks; doesn't help the users who've already broken one, which interviews and NPS both flag as the bigger issue.
3. **Retune notification strategy alone** — addresses a real complaint, but it's a secondary theme (3 of 10) and unlikely to move Day-7 retention meaningfully on its own.

## Recommended Action

Build the Comeback screen as the primary bet, since it directly addresses the most-cited driver of churn and claims a gap no competitor currently owns.

## Why Now

The retention drop is measurable and compounding, and research shows it isn't just early-days churn that will self-correct — it's hitting users who'd already built real investment. Competitors are actively moving toward more forgiving streak mechanics (Elevate just added freezes in 2026), so the window to be first to own the comeback moment, rather than just match freeze parity, is closing.
