# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

## Method

**Method:** A/B Test

**Why:** There are several reasons:
1. Precision is what this bet needs, and therefore an A/B test is the method which gives it. This is a structural bet — M1 explicitly chose the loop over the faster funnel fix, accepting "if I'm wrong, I'm wrong slowly and expensively."
2. The randomisation unit is available and not contaminated.
3. Holdout test would be also nice but more for retention ( churn) metric.

_____

## Hypothesis + primary metric

If we make inviting a second person the primary call-to-action of the reverse trial — surfaced at first login and again the moment a user generates their first cash-flow report, with the invitee receiving a permanent free view-and-comment seat — then the share of trial accounts reaching 2+ active users by day 14 will rise from baseline to ≥25%, and trial→paid among multi-user accounts will run at ≥2× single-user accounts (~4% vs ~2%), because a single-user account has almost nothing to lose at the day-15 downgrade while a shared account contains a working relationship the downgrade can remove

**Primary metric:** % of trial accounts with 2+ active users by day 14. "Active" = the invitee has signed in and either viewed a report or left a comment (per M2, commented is the stronger signal; viewed is the minimum bar). Measured intent-to-treat on all accounts randomised at signup., target: Primary ≥ 25% of trial accounts multi-user by day 14, at p < 0.05. Anything below that is a Modest Win → iterate, don't ship.

_Experiment: Multi-User Trial Activation Test (Collaboration CTA), Establish whether making "invite your accountant" the primary action of the reverse trial moves trial accounts from single-user to multi-user inside the 14-day trial — the dependency condition M1 identified as the missing ingredient behind both the 2% trial→paid ceiling and the 60% annual churn._

_Testing One change: the invite becomes the primary CTA of the trial, at two moments. (a) At first login, as the headline action rather than a settings option. (b) Immediately after the first cash-flow report renders, anchored to a specific finding in the user's own data. on All new trial accounts created during the 14-day enrolment window randomised 50/50 at signup. Current experience: A trial user signs up, works through onboarding, and — if they get there — connects their bank data and sees a list of transactions and a chart of their own numbers. Only 39.37% of trials ever reach that point. Collaboration exists but is invisible: "invite a user" sits in a settings submenu, framed as account administration, with no prompt, no moment, and no reason attached to it. The account stays single-user through day 15, when the downgrade removes features from someone who has built nothing worth keeping.._

_Predicted outcome: Treatment reaches 25–30% of trial accounts multi-user by day 14, against a control baseline in the low single digits. Trial→paid among multi-user accounts runs at roughly 4% vs ~2%. If successful: 1. Ship to 100% behind a feature flag, rolled out incrementally.
2. Open the committed 5% long-term holdout to test the claim this bet actually rests on — that dependency fixes the 2.48:1 churn ratio. 
3. Iterate on the second half of the loop: invite acceptance and invitee activation
4. Feed the multi-user accounts into the M3 "Whose Turn" mechanic — it has no fuel without them.. If unsuccessful: Diagnose what was going on with additional metrics.
1. Low invite send rate - iterate on cta to invite
2. High send rate, low acceptance - accountant doesn't see a reason to come, iterate on invitation
3. High acceptance, no conversion lift - maybe our assumption about dependency was not correct, stop and try another test.._

_____

## Guardrail + read date

- **Guardrail:** 1. Product CSAT must not drop more than 5pp vs control. 2. Day-1 drop-off must not increase. 3. Bank-data connection rate must not fall below 39.37%
- **Read date:** Day 28 after launch. No earlier, for any reason.

_____
