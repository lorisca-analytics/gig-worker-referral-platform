# Evidence: Gig Worker Referral Platform

The research and planning behind the pilot recommendation. Client is Client Bank (anonymized for publishing). Interviewees are described by role only.

[Back to README](README.md)

---

## 1. Survey highlights (n=39)

Our own survey of gig and independent workers, April 2026.

| Finding | Result |
|---|---|
| Have the ID needed to open a U.S. bank account | 100% |
| Have more than one income source | 72% |
| Applied for a credit product before | 76% |
| Most recent application done online | 69% |
| Most recent application rejected | 25% |
| Credit was for everyday expenses or emergencies | 75% |
| Already know the client bank's brand | 68% |

What it told us: these are bank-eligible people with more than one income. Most of them already try to borrow, and they apply online.

## 2. Interviews (8) and legal review

Because this touches lending, compliance came first. We tested the idea with people who would have to sign off on it, not only the people it would serve.

**Industry and banking (4)**
- A senior data analyst inside the client bank, who confirmed the bank's existing data tools can already link outside data to customer records, and that a dedicated product is allowed to ask segment-specific questions
- A former debt investment analyst at a large investment fund, who pressure-tested the unit economics and the tax angle
- An industry advisor with a background as a chief information officer and consultant at large financial firms, who pushed us on scope and on who actually pays in each segment
- A technology executive at a creator-marketing agency, who showed us which partner types can actually vouch for earnings

**Gig workers (4)**
- A nurse with caregiving side work, a housekeeper, a small creator and a rideshare driver

**Legal review**
- A reviewer with a legal background flagged that letting one individual refer another could be read as targeting vulnerable people. We changed the design so only business partners refer. That one change made the model something a compliance team could approve.

Three themes came up in almost every conversation:
- **Invisible income.** The income is documented (1099s, platform statements, deposits). Standard income checks only read payroll, so it never gets counted.
- **Tax complexity.** Many payers, quarterly estimates and cross-platform reconciliation. Any tax feature has to be framed as prep and tracking, never as "formalizing" income, or people walk away.
- **Irregular pay.** One big month, then nothing. Monthly-consistency rules punish this even when the 12-month average is strong, so people default to fintech apps.

Other things we heard:
- Referrals from someone they trust work better than advertising.
- Some workers distrust banks, and "paperwork" is the real barrier, more than rates.
- The technology is not the blocker. Underwriting rules and an internal owner are.
- A worry that reporting more income would hurt Social Security benefits turned out to be wrong. More reported income helps.

## 3. Acquisition cost benchmark

- Pilot target: **$100 per activated customer**, paid to the referring partner only when the customer activates.
- Industry estimates used in the pitch: **$350 to $600** per new customer.
- Supporting source: Curinos (Jul 2024) puts new-to-bank cost per acquisition at **$663**, and **$868 for regional banks**. ([Curinos, "CPAs Continue To Soar"](https://www.curinos.com/insights/according-to-the-data-cpas-continue-to-soar))

## 4. Competitor gap

What gig workers use instead of a bank, and what each lacks:

| Alternative | Gives them | Missing |
|---|---|---|
| Cash and peer-to-peer apps | Fast, trusted transfers | No credit, no credit history |
| Neobanks | Mobile-first, early direct deposit | No credit, no branches, no relationship |
| Fintech lenders | Quick decisions based on cash flow | Rates far above bank rates, no deposits, no cross-sell |
| Platform payout cards | Instant payouts | Locked to one platform |

The gap: nobody combines bank-rate credit, regulated deposits, branches and a relationship that grows with the customer into a small business. A regional bank already has all four. It just can't read this customer's income.

## 5. Risk register

| Risk | Status | How we handle it | Warning sign |
|---|---|---|---|
| No internal owner at the bank | Open | Name an executive sponsor as the first ask | Pitch gets no follow-up meeting |
| Referral partner not signed (and first contact was the wrong partner type) | Open | Treat as a pilot dependency, with a second partner type as fallback | No response after three attempts in two weeks |
| Platform won't share earnings data | Open, workaround in place | Use deposit history the bank already has | Platform declines data request |
| Defaults from irregular income | Open | Conservative loan limits, 12-month income average, W-2 income as a buffer | 90-day delinquency above 2.5% |
| Tax feature scares people off | Watching | Frame as prep and tracking only | Interviewees distrust the tax feature |
| Loans drift to everyday spending | Watching | Gate loan purpose at application (equipment, inventory, invoices) | Applications skew to rent and bills |
| Regulators reject alternative income data | Mitigated | Dedicated product, single-state pilot | New federal guidance restricts it |
| Person-to-person referral targets vulnerable people | Eliminated | Switched to business partners as referrers | n/a |
| Social Security benefit worry | Eliminated | Interview confirmed more reported income helps | n/a |

## 6. KPI tree

| Stage | Question | Metrics and targets |
|---|---|---|
| Activity (months 1 to 3) | Did the machine run? | At least 1 partner signed · 500+ referrals · 60%+ consent rate · referral to decision in 5 days or less |
| Output (months 3 to 6) | Did the model work? | 65%+ approval rate · acquisition cost $150 or less per borrower · 80%+ income recognized · 70%+ consent to account open |
| Risk (months 3 to 12) | Is credit discipline holding? | 90-day delinquency 2.5% or less · manual review 20% or less · default rate within 1.5 points of a control group |
| Outcome (months 6 to 24) | Is the real prize showing up? | 15%+ take a second product · $2,500+ average deposits · 10%+ move to a business account |

## 7. 30-60-90 pilot outline

| Phase | Governance | Partners | Tech | Go-live |
|---|---|---|---|---|
| Days 1 to 30 | Name an executive owner and sponsors | Sign one referral partner in the pilot state | Scope the data-tool link and switch on the "other income" field in the existing loan application | |
| Days 31 to 60 | Risk committee approves, legal signs off on the dedicated product | Open talks with large platforms | Run the first 500 referrals through the verification flow | First cohort in market |
| Days 61 to 90 | First 90-day performance review | Add a second partner if activation is above 40% | Feed activation data back into underwriting | Check readiness for the small business track |

Checkpoints after launch: month 3, at least 40% of referrals activate or the pilot pauses and recalibrates. Month 12, scale decision based on activation, delinquency and cross-product use.
