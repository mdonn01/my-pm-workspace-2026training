# Strategy — Streakly Comeback

## Hypothesis: recovering the 9-point Day-7 retention drop (48% → 39%)

The streak mechanic's loss-aversion design — the thing that drives engagement — is the same mechanic that punishes users when a streak breaks: a cold reset to zero, a harsh "you lost your streak" push notification, and no acknowledgment or path back in. This is driving week-1 streak-breakers to churn at roughly 2x the normal rate, which is the sharpest contributor to the overall Day-7 drop.

## Candidate direction (unvalidated)

A "Comeback screen" shown when a streak breaks, instead of a cold reset:
- Best-streak stat (shows their real progress, not just the reset counter)
- One 60-second "comeback lesson" to rebuild momentum
- One-tap streak-freeze to protect the streak they rebuild

Raj: technically feasible with existing data sources; would need logic for who sees it and streak-freeze rules — no new data sources required.

## Status

Root cause (reset mechanic vs. notification tone vs. both) and the Comeback screen direction are both **unconfirmed**. Pending additional inputs (user research, support tickets, survey/data) to be supplied later.
