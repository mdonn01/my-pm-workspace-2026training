# Streakly Comeback Experience — PRD Skeleton

*Draft starting point from team Slack thread (Marcus, Raj, Lena), 2026-09-28. Not a finished document — for alignment ahead of Thursday's meeting.*

## Problem Statement

Day-7 retention has dropped from 48% to 39% since the streak redesign shipped. The drop is sharpest among users who break their streak in week 1 — once a user misses two days in a row, churn is almost double.

Today, breaking a streak resets the counter to zero with no acknowledgment: the app shows the same home screen as if nothing happened, and the "you lost your streak" push notification has a harsh tone that drops users back at day zero with nothing offered. Users experience this as punishment, and go passive because there's no graceful way back in.

Working hypothesis: users disengage after a streak break because it feels like failure, and the app offers no comeback path — pulling them back requires something specific to their own progress, not a generic "keep going" message.

## Goals

- Recover Day-7 retention lost since the streak redesign (39% → back toward the prior 48% baseline).
- Give users who break a streak a graceful path back in, rather than a cold reset.
- Reduce the churn spike specifically among week-1 streak-breakers.

## Non-Goals

*(Not discussed in thread — to be defined before/at Thursday's meeting.)*

## Success Metrics

*(Not discussed in thread — to be defined. Note: Day-7 retention is the metric already in play, currently 39% vs. a 48% baseline before the redesign.)*

## Open Questions / Notes for Thursday

- Confirm whether the problem is the streak reset itself, the notification tone, or both (raised by Marcus, not resolved in thread).
- Solution direction floated by Lena (not yet scoped/approved): a "Comeback screen" shown on streak break, with best-streak stat, a 60-second comeback lesson, and a one-tap streak-freeze.
- Raj: technically feasible with existing data sources; would need logic for who sees it and streak-freeze rules.
- Goal for Thursday per Marcus: align on the problem before designing solutions.
