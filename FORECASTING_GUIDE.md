# How to Read a Subscription App Forecast

A seller's forecast is one of the most influential documents in a subscription app deal, and one of the easiest to get wrong. This guide explains what a credible forecast claims, how to read the retention data behind it, and where seller projections most often break down. It is written for buyers and reviewers, not model builders: you do not need to rebuild the seller's model to tell whether it deserves your money.

For the broader valuation framework, see [How App Valuation Works](https://approck.com/knowledge/how-valuation-works). This guide goes one level deeper on the forecasting half of that process.

## What a forecast actually claims

A subscription app forecast estimates future net revenue from the subscribers an app already has, plus any assumptions about new subscribers. It is a claim about behavior: how many current subscribers will still be paying in 6, 12, or 24 months. It is not a multiple applied to last month's revenue, and treating it that way hides most of the risk.

Three components drive every forecast:

- **The existing subscriber base** and how it decays over time
- **New subscriber additions**, if the app is still acquiring users
- **Net revenue per subscriber** after platform commission, refunds, and taxes

The first component is the most predictable and carries most of the value in an established app. The second is the least predictable, and forecasts that lean on it deserve the most scrutiny.

## Cohorts: why averages lie

Asking "what is the app's churn rate?" is like asking "what is the average temperature?" across seasons and cities. The useful question is: churn for whom, and starting when?

Subscribers who arrive through different doors behave differently:

- **Weekly subscribers** renew often, so the data shows quickly whether they stay or leave
- **Monthly subscribers** usually make up the backbone of revenue and churn steadily
- **Annual subscribers** can make retention look excellent for months, then fall off a cliff at renewal
- **Trial converts** typically retain differently from direct paid subscribers
- **Paid-traffic subscribers** often churn faster than organic ones once acquisition stops

A blended average across all of these hides the differences that matter. If an app added a large annual-plan cohort recently, a healthy-looking average retention rate may simply be annual subscribers who have not yet hit their first renewal.

What to ask the seller for:

- Retention curves by subscription start month (cohort retention), not just a blended average
- The split between weekly, monthly, and annual plans over time
- A breakdown of subscribers acquired through paid channels versus organic, if the app ran marketing

## Reading a retention curve

Plot subscriber counts or revenue by acquisition cohort, and one of a few shapes will appear:

| Shape | What it usually means | Typical impact |
| --- | --- | --- |
| Steady gradual decline | Normal subscription wear-off; predictable | Supports a conventional valuation |
| Slow decline that flattens | A loyal core of long-term subscribers | Positive signal |
| Sharp early drop, then stable | High churn among mismatches, a solid core remains | Depends on core size |
| Continuous acceleration in decline | Something changed: app quality, competition, or policy issues | Materially lower value |
| Cliff at a specific date | A price change, policy event, or a reporting gap | Investigate before pricing |

Two details deserve particular attention:

- **Missing periods are not zeros.** If cohort data is absent for some months, the forecast must not silently treat those subscribers as churned — or as retained. Ask what the data gap means.
- **Young cohorts are unproven.** A cohort started three months ago says little about two-year retention. Forecasts that read full-lifetime behavior from young cohorts are overconfident.

## The delisted app case

Apps removed from the App Store or Google Play, or apps with acquisitions turned off, behave differently from live apps: the subscriber base is fixed, and the only question is how fast it runs off. This is a distinct valuation case, not a pessimistic version of the standard one.

For a delisted or no-new-subs app, check:

- Whether the seller's forecast explicitly models a runoff, rather than applying a live-app multiple
- Whether new installs are truly zero, or whether the app still gets occasional demand that cannot convert
- Whether the store relationship allows reactivation or transfer at all — a delisted app that cannot be transferred has a different kind of value
- Whether billing still processes correctly for all plan types, since annual subscribers may be paying far into the future

Runoff value can still be real value, but it should be priced as what it is: a known base decaying on a measurable curve.

## Red flags in a seller's forecast

- Retention presented only as a blended average, with no cohort breakdown
- Historical gaps silently filled with zeros or optimistic assumptions
- Paid-acquisition subscribers projected with the same retention as organic ones
- Retention assumed flat forever, with no decay
- Annual-plan revenue annualized without accounting for renewal cliffs
- A forecast that changes methodology right before the sale period
- No reconciliation between the forecast's starting numbers and the store's financial reports

Any one of these is a question, not automatically a dealbreaker. Several of them together mean the forecast is decoration, and the price should be built from evidence you assemble yourself.

## Questions to put to the seller

1. Which subscription events (renewals, cancellations, refunds, billing retries) feed the forecast, and from which system?
2. Show retention by cohort start month for the last 12–24 months.
3. What share of current subscribers came from paid campaigns, and when did those campaigns end?
4. Have there been price changes, plan changes, or app store issues that break the trend?
5. If the app is delisted or no longer acquiring, what runoff curve is assumed, and what data supports it?

## Limitations

Every forecast is an estimate, and even a well-built model cannot account for a future platform policy change, an OS update that breaks the app, or a competitor's launch. The purpose of reviewing a forecast is not to certify its accuracy; it is to understand which assumptions carry the price, and to test them against evidence. Where evidence and forecast disagree, trust the evidence — and price the disagreement.

