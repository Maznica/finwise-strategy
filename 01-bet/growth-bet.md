# The Bet · FinWise

> Module 1 · Ignite a PLG Motion. The growth hypothesis and where you're betting, plus the growth-loop visualization.

## Growth hypothesis

FinWise’s biggest growth problem is that the product creates value for exactly one person, so nothing built during the reverse trial becomes something anyone would pay to keep or lose by leaving., because over 13 months deep feature adoption rose 5.4× (Modeling 10.78% → 58.26%) while trial→paid stayed locked in a 0.21-point band and churn outran new customers in all 13 months. Usage went up; neither conversion nor retention responded. The missing ingredient isn’t engagement — it’s dependency..

_Working notes: I think FinWise biggest problem is that only 2 % of customers who begin a trial convert to paying customers. 
As the majority of the marketing budget is going to paid acquissition to drive trial sign-ups and only 2 % of them becoming paid customers. It is really problematic.
So, I think that they are not able to show the value in the trial period and therefore, only 2 % convert to paid users.
In addition to that also the retention is not that good as only 40 % stay with finwise after one year. That means for me that even one year some of the customers are not able to recognize the value.
So the problem is that the vlaue is hard to realize for the customers. Therefore the reverse trial also not work because it seams that the downgrade doesn't hurt. Evidence: - Most of the marketing budget goes to paid acquisition to drive trial sign-ups
- But only 2 % of trial customers become paid customers: This means that majority of the users never recognize the value and therefore never got far enough in to feel the loss by reverse trial.
- That means, adding more money to acquisition is no longer driving meaningful growth. The acquisition isn't the constraint.

Moreover, 60 % churn means that the failure continues after payment. 

Against the data: The data at one hand confirmed and at another challenged my hypotheses:
Confirmed:

I claimed users never reach real value. Import Data at 39.37% backs that — the majority of trials never load their own numbers.
I claimed the churn problem is worse than the headline. It is: churn exceeds new customers in all 13 months, 317 vs 128, net −189. The scenario said “60% churn”; the data says the customer base is shrinking every single month.
I ranked acquisition last. The data is harsher than I was — not diminishing returns, no returns (r = 0.09).

Challenged — and this is the real hit:

My whole hypothesis rested on “get more users to value and conversion follows.” The data refuses that. Modeling adoption went 10.78% → 58.26%, a 5.4× rise in deep feature usage, and trial→paid went 2.05% → 2.06%.

Users got substantially more engaged and it bought FinWise nothing. My predicted mechanism — activation improves, conversion follows — already ran as a natural experiment over 13 months, and it failed._

_____

## The bet

The highest-leverage experiment I’d run first is making “invite your bookkeeper or accountant” the central action of the reverse trial, not a buried settings option.  
Changed hypothesis: 
IF we make inviting a second person the primary call-to-action of the reverse trial — surfaced at first login and again the moment a user completes their first report — with the invitee getting permanent free view-and-comment access,  
THEN the share of trial accounts reaching 2+ active users within 14 days WILL rise to 25%+, and trial→paid among multi-user accounts WILL run at least 2× single-user accounts (≈4% vs ≈2%), BECAUSE a single-user account has nothing to lose downgrade, while a shared account has a second person depending on it — and a second seat creates a payment trigger that doesn’t require the owner to decide in the abstract,  
WHICH WE’LL MEASURE WITH an A/B test over 4 weeks.  Primary: % of trial accounts with 2+ active users by day 14 Secondary: trial→paid split by account size;  Guardrails: day-1 drop-off, single conversation rate must not dropp off

**Not doing:** I’m not touching acquisition, and I’m not running a retention programme or a pricing test first. Three specific trade-offs:

Walking past the largest loss in the funnel. 88,134 visits leave without trialing — 14× more people than the next step loses. I’m accepting that becuse it will defocus me from the main problem

Not attacking retention head-on, even though it’s the bigger dollar problem — 317 lost vs 128 gained. I’m betting collaboration fixes retention as a byproduct of dependency. If it doesn’t, I’ve spent a quarter on acquisition-side mechanics while the paid base kept draining at the same rate.

Choosing the loop over the funnel fix. A better paywall or a sharper downgrade screen is faster to build, faster to read, and the most defensible alternative on the table. I’m passing on the quick win for a structural one that compounds — which also means that if I’m wrong, I’m wrong slowly and expensively.

The assumption this all rests on: that FinWise’s users have someone to invite. If most small-business owners genuinely do their own books alone, the collaboration loop has no fuel and the entire bet collapses. That’s the one thing I’d validate in week one — before building anything, pull the distribution of active users per account on the existing paid base.

_____

## Growth loop

**Loop type:** Collaboration, If I would go for a loop I would choose a collaboration loop, because:
Financial data is private — a small business never publishes its cash-flow report, so a content-driven loop has no shareable output to run on. And a referral loop would feed more strangers into a top-of-funnel the data already shows is unresponsive and a trial that converts at a fixed 2%. Collaboration is the only loop whose output lands inside the account: pulling in the bookkeeper, accountant or co-founder creates the multi-user dependency, and it produces a seat-based payment trigger.
The assumption here is that the user has someone to collaborate with.

![Growth loop diagram](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI2ODAiIGhlaWdodD0iNDAwIiB2aWV3Qm94PSIwIDAgNjgwIDQwMCIgcm9sZT0iaW1nIiBmb250LWZhbWlseT0iJ1NlZ29lIFVJJywgc3lzdGVtLXVpLCAtYXBwbGUtc3lzdGVtLCBIZWx2ZXRpY2EsIEFyaWFsLCBzYW5zLXNlcmlmIj4KICA8dGl0bGU+RmluV2lzZSBjb2xsYWJvcmF0aW9uIGdyb3d0aCBsb29wPC90aXRsZT4KICA8ZGVzYz5BIHNpeC1zdGFnZSBjeWNsZTogYSBzbWFsbC1idXNpbmVzcyBvd25lciBzdGFydHMgYSB0cmlhbCBhbmQgY29ubmVjdHMgYmFuayBkYXRhLCBpbnZpdGVzIHRoZWlyIGFjY291bnRhbnQgdG8gYSBmcmVlIHJldmlldyBzZWF0LCB0aGUgYWNjb3VudCBiZWNvbWVzIGEgc2hhcmVkIHdvcmtzcGFjZSwgaXQgY29udmVydHMgdG8gYSBwYWlkIHNlYXQtYmFzZWQgcGxhbiBhbmQgcmV0YWlucywgdGhlIGFjY291bnRhbnQgdGhlbiBhZG9wdHMgRmluV2lzZSBhY3Jvc3MgdGhlaXIgb3duIGNsaWVudCBib29rLCBhbmQgbmV3IHByZS1zb2xkIG93bmVycyBhcnJpdmUsIHJlc3RhcnRpbmcgdGhlIGxvb3AuPC9kZXNjPgoKICA8ZGVmcz4KICAgIDxtYXJrZXIgaWQ9ImFycm93IiB2aWV3Qm94PSIwIDAgMTAgMTAiIHJlZlg9IjgiIHJlZlk9IjUiIG1hcmtlcldpZHRoPSI2IiBtYXJrZXJIZWlnaHQ9IjYiIG9yaWVudD0iYXV0by1zdGFydC1yZXZlcnNlIj4KICAgICAgPHBhdGggZD0iTTIgMUw4IDVMMiA5IiBmaWxsPSJub25lIiBzdHJva2U9IiM1RjVFNUEiIHN0cm9rZS13aWR0aD0iMS41IiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiLz4KICAgIDwvbWFya2VyPgogIDwvZGVmcz4KCiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjY4MCIgaGVpZ2h0PSI0MDAiIGZpbGw9IiNGRkZGRkYiLz4KCiAgPHRleHQgeD0iNDAiIHk9IjM0IiBmb250LXNpemU9IjE1IiBmb250LXdlaWdodD0iNjAwIiBmaWxsPSIjMkMyQzJBIj5GaW5XaXNlIENvLiDigJQgY29sbGFib3JhdGlvbiBncm93dGggbG9vcDwvdGV4dD4KCiAgPHJlY3QgeD0iNDAiIHk9IjU2IiB3aWR0aD0iMTgwIiBoZWlnaHQ9Ijc2IiByeD0iNCIgZmlsbD0iI0YxRUZFOCIgc3Ryb2tlPSIjNUY1RTVBIiBzdHJva2Utd2lkdGg9IjAuNSIvPgogIDx0ZXh0IHg9IjEzMCIgeT0iODgiIGZvbnQtc2l6ZT0iMTQiIGZvbnQtd2VpZ2h0PSI2MDAiIGZpbGw9IiM0NDQ0NDEiIHRleHQtYW5jaG9yPSJtaWRkbGUiPk93bmVyIHN0YXJ0cyB0cmlhbDwvdGV4dD4KICA8dGV4dCB4PSIxMzAiIHk9IjEwOCIgZm9udC1zaXplPSIxMiIgZmlsbD0iIzVGNUU1QSIgdGV4dC1hbmNob3I9Im1pZGRsZSI+Q29ubmVjdHMgYmFuayBkYXRhPC90ZXh0PgoKICA8cmVjdCB4PSIyNTAiIHk9IjU2IiB3aWR0aD0iMTgwIiBoZWlnaHQ9Ijc2IiByeD0iNCIgZmlsbD0iI0UxRjVFRSIgc3Ryb2tlPSIjMEY2RTU2IiBzdHJva2Utd2lkdGg9IjAuNSIvPgogIDx0ZXh0IHg9IjM0MCIgeT0iODgiIGZvbnQtc2l6ZT0iMTQiIGZvbnQtd2VpZ2h0PSI2MDAiIGZpbGw9IiMwODUwNDEiIHRleHQtYW5jaG9yPSJtaWRkbGUiPkludml0ZXMgYWNjb3VudGFudDwvdGV4dD4KICA8dGV4dCB4PSIzNDAiIHk9IjEwOCIgZm9udC1zaXplPSIxMiIgZmlsbD0iIzBGNkU1NiIgdGV4dC1hbmNob3I9Im1pZGRsZSI+RnJlZSByZXZpZXcgc2VhdDwvdGV4dD4KCiAgPHJlY3QgeD0iNDYwIiB5PSI1NiIgd2lkdGg9IjE4MCIgaGVpZ2h0PSI3NiIgcng9IjQiIGZpbGw9IiNFMUY1RUUiIHN0cm9rZT0iIzBGNkU1NiIgc3Ryb2tlLXdpZHRoPSIwLjUiLz4KICA8dGV4dCB4PSI1NTAiIHk9Ijg4IiBmb250LXNpemU9IjE0IiBmb250LXdlaWdodD0iNjAwIiBmaWxsPSIjMDg1MDQxIiB0ZXh0LWFuY2hvcj0ibWlkZGxlIj5TaGFyZWQgd29ya3NwYWNlPC90ZXh0PgogIDx0ZXh0IHg9IjU1MCIgeT0iMTA4IiBmb250LXNpemU9IjEyIiBmaWxsPSIjMEY2RTU2IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIj5Cb3RoIHdvcmsgaW4gaXQ8L3RleHQ+CgogIDxyZWN0IHg9IjQ2MCIgeT0iMjE2IiB3aWR0aD0iMTgwIiBoZWlnaHQ9Ijc2IiByeD0iNCIgZmlsbD0iI0VFRURGRSIgc3Ryb2tlPSIjNTM0QUI3IiBzdHJva2Utd2lkdGg9IjAuNSIvPgogIDx0ZXh0IHg9IjU1MCIgeT0iMjQ4IiBmb250LXNpemU9IjE0IiBmb250LXdlaWdodD0iNjAwIiBmaWxsPSIjM0MzNDg5IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIj5TZWF0LWJhc2VkIHVwZ3JhZGU8L3RleHQ+CiAgPHRleHQgeD0iNTUwIiB5PSIyNjgiIGZvbnQtc2l6ZT0iMTIiIGZpbGw9IiM1MzRBQjciIHRleHQtYW5jaG9yPSJtaWRkbGUiPlBheXMsIGFuZCBzdGF5czwvdGV4dD4KCiAgPHJlY3QgeD0iMjUwIiB5PSIyMTYiIHdpZHRoPSIxODAiIGhlaWdodD0iNzYiIHJ4PSI0IiBmaWxsPSIjRTFGNUVFIiBzdHJva2U9IiMwRjZFNTYiIHN0cm9rZS13aWR0aD0iMC41Ii8+CiAgPHRleHQgeD0iMzQwIiB5PSIyNDgiIGZvbnQtc2l6ZT0iMTQiIGZvbnQtd2VpZ2h0PSI2MDAiIGZpbGw9IiMwODUwNDEiIHRleHQtYW5jaG9yPSJtaWRkbGUiPkFjY291bnRhbnQgYWRvcHRzPC90ZXh0PgogIDx0ZXh0IHg9IjM0MCIgeT0iMjY4IiBmb250LXNpemU9IjEyIiBmaWxsPSIjMEY2RTU2IiB0ZXh0LWFuY2hvcj0ibWlkZGxlIj5Vc2VzIGl0IHdpdGggY2xpZW50czwvdGV4dD4KCiAgPHJlY3QgeD0iNDAiIHk9IjIxNiIgd2lkdGg9IjE4MCIgaGVpZ2h0PSI3NiIgcng9IjQiIGZpbGw9IiNGMUVGRTgiIHN0cm9rZT0iIzVGNUU1QSIgc3Ryb2tlLXdpZHRoPSIwLjUiLz4KICA8dGV4dCB4PSIxMzAiIHk9IjI0OCIgZm9udC1zaXplPSIxNCIgZm9udC13ZWlnaHQ9IjYwMCIgZmlsbD0iIzQ0NDQ0MSIgdGV4dC1hbmNob3I9Im1pZGRsZSI+TmV3IG93bmVycyBhcnJpdmU8L3RleHQ+CiAgPHRleHQgeD0iMTMwIiB5PSIyNjgiIGZvbnQtc2l6ZT0iMTIiIGZpbGw9IiM1RjVFNUEiIHRleHQtYW5jaG9yPSJtaWRkbGUiPlJlZmVycmVkLCBwcmUtc29sZDwvdGV4dD4KCiAgPGcgc3Ryb2tlPSIjNUY1RTVBIiBzdHJva2Utd2lkdGg9IjEuNSIgZmlsbD0ibm9uZSIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIj4KICAgIDxsaW5lIHgxPSIyMjIiIHkxPSI5NCIgIHgyPSIyNDYiIHkyPSI5NCIgIG1hcmtlci1lbmQ9InVybCgjYXJyb3cpIi8+CiAgICA8bGluZSB4MT0iNDMyIiB5MT0iOTQiICB4Mj0iNDU2IiB5Mj0iOTQiICBtYXJrZXItZW5kPSJ1cmwoI2Fycm93KSIvPgogICAgPGxpbmUgeDE9IjU1MCIgeTE9IjEzNiIgeDI9IjU1MCIgeTI9IjIxMiIgbWFya2VyLWVuZD0idXJsKCNhcnJvdykiLz4KICAgIDxsaW5lIHgxPSI0NTgiIHkxPSIyNTQiIHgyPSI0MzQiIHkyPSIyNTQiIG1hcmtlci1lbmQ9InVybCgjYXJyb3cpIi8+CiAgICA8bGluZSB4MT0iMjQ4IiB5MT0iMjU0IiB4Mj0iMjI0IiB5Mj0iMjU0IiBtYXJrZXItZW5kPSJ1cmwoI2Fycm93KSIvPgogICAgPGxpbmUgeDE9IjEzMCIgeTE9IjIxMiIgeDI9IjEzMCIgeTI9IjEzNiIgbWFya2VyLWVuZD0idXJsKCNhcnJvdykiLz4KICA8L2c+CgogIDxyZWN0IHg9IjQwIiAgeT0iMzI0IiB3aWR0aD0iMTIiIGhlaWdodD0iMTIiIHJ4PSIyIiBmaWxsPSIjRjFFRkU4IiBzdHJva2U9IiM1RjVFNUEiIHN0cm9rZS13aWR0aD0iMC41Ii8+CiAgPHRleHQgeD0iNTgiICB5PSIzMzQiIGZvbnQtc2l6ZT0iMTIiIGZpbGw9IiM1RjVFNUEiPkVudHJ5IHBvaW50PC90ZXh0PgogIDxyZWN0IHg9IjE2MCIgeT0iMzI0IiB3aWR0aD0iMTIiIGhlaWdodD0iMTIiIHJ4PSIyIiBmaWxsPSIjRTFGNUVFIiBzdHJva2U9IiMwRjZFNTYiIHN0cm9rZS13aWR0aD0iMC41Ii8+CiAgPHRleHQgeD0iMTc4IiB5PSIzMzQiIGZvbnQtc2l6ZT0iMTIiIGZpbGw9IiM1RjVFNUEiPlVzZXIgYWN0aW9uPC90ZXh0PgogIDxyZWN0IHg9IjI5MCIgeT0iMzI0IiB3aWR0aD0iMTIiIGhlaWdodD0iMTIiIHJ4PSIyIiBmaWxsPSIjRUVFREZFIiBzdHJva2U9IiM1MzRBQjciIHN0cm9rZS13aWR0aD0iMC41Ii8+CiAgPHRleHQgeD0iMzA4IiB5PSIzMzQiIGZvbnQtc2l6ZT0iMTIiIGZpbGw9IiM1RjVFNUEiPlJldmVudWUgKyByZXRlbnRpb248L3RleHQ+CgogIDx0ZXh0IHg9IjQwIiB5PSIzNzAiIGZvbnQtc2l6ZT0iMTEiIGZpbGw9IiM4ODg3ODAiPlRyaWdnZXI6IG93bmVyIGNvbm5lY3RzIGJhbmsgZGF0YSBhbmQgZ2VuZXJhdGVzIGEgZmlyc3QgY2FzaC1mbG93IHJlcG9ydC4gT3V0cHV0IHRoYXQgcmVzdGFydHMgdGhlIGxvb3A6IHRoZSBhY2NvdW50YW50J3MgY2xpZW50IGJvb2suPC90ZXh0Pgo8L3N2Zz4K)

_____
