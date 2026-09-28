---
name: weekly-status
description: Turn raw bullet-point notes into a formatted weekly leadership status update with Shipped, In Progress, Blockers, and Next Week sections. Use this whenever the user asks for a weekly update, status update, leadership update, or wants to turn scratch notes/bullets into a shareable status report, even if they don't explicitly ask for a "skill."
---

# Weekly Status Update

Turn raw bullet-point notes into a leadership-ready status update.

## Output format

ALWAYS use this exact structure:

# Weekly Status Update
## Shipped
- (up to 3 bullets)
## In Progress
- (up to 3 bullets)
## Blockers
- (up to 3 bullets, or "None this week")
## Next Week
- (up to 3 bullets)

## How to sort notes into sections

Read the raw bullets and route each one by its status language:
- Done, launched, shipped, completed → **Shipped**
- Working on, underway, in flight → **In Progress**
- Blocked, waiting on, stuck → **Blockers**
- Planned, will do, starting → **Next Week**

## How to rewrite each bullet

- One plain, declarative sentence per bullet. State what happened or what's happening — not how it feels or why it matters.
- No jargon, acronyms, or internal buzzwords. If the raw note uses one, translate it into plain language a non-technical exec would understand.
- Cap every section at 3 bullets. If more than 3 notes land in a section, keep the 3 with the biggest impact or most senior visibility and drop the rest — don't cram extras in or split bullets to fit.
- If a section has no relevant notes, write "None this week" rather than leaving it blank.

## Example

**Input:**
- finished migrating auth to new SSO provider
- still working on the onboarding redesign, about 60% done
- blocked on legal review for the new ToS copy
- next week starting the perf audit on the checkout flow
- also shipped the dark mode toggle
- in progress: cleaning up tech debt in the billing service

**Output:**

# Weekly Status Update
## Shipped
- Migrated authentication to the new single sign-on provider
- Released a dark mode toggle

## In Progress
- Onboarding redesign, about 60% complete
- Cleanup work on the billing service

## Blockers
- Waiting on legal review of the new terms-of-service copy

## Next Week
- Starting a performance audit of the checkout flow
