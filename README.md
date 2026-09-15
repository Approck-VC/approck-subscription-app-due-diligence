# Subscription App Due Diligence

An open checklist for evaluating a subscription-based mobile app before an acquisition or sale. It covers revenue evidence, subscription health, traffic quality, technical ownership, platform compliance, and transfer readiness.

Maintained by [Approck](https://approck.com/), a marketplace for verified subscription mobile apps.

## Who this is for

- Founders preparing a mobile app for sale
- Buyers screening a subscription app before making an offer
- Operators organizing a data room or handover plan
- Advisors who need a consistent first-pass review

This repository is a starting point, not a replacement for legal, tax, financial, security, or platform-specific advice.

## Checklists

| Area | What it helps verify |
| --- | --- |
| [Valuation inputs](VALUATION_INPUTS.md) | Revenue quality, subscription performance, acquisition economics, costs, and risk |
| [Forecast guide](FORECASTING_GUIDE.md) | How to read and stress-test a seller's revenue projections |
| [Technical review](TECHNICAL_REVIEW.md) | Build reproducibility, ownership, infrastructure, security, and maintainability |
| [Transfer checklist](TRANSFER_CHECKLIST.md) | Store eligibility, asset inventory, credential handover, closing, and post-transfer checks |

## Knowledge library

Guides from the [Approck knowledge base](https://approck.com/knowledge) are also available in this repository as plain markdown, including a canonical link back to the live page in each file. Start with the [library index](knowledge/README.md).

## Quick start

1. Ask the seller to provide evidence for each claimed metric, not only screenshots or summaries.
2. Reconcile store proceeds, subscription analytics, and bank or accounting records for the same periods.
3. Produce a working release build from the source code and documented environment.
4. Confirm transfer eligibility with Apple or Google before treating the transaction as executable.
5. Put every transferred asset, dependency, credential, and post-closing obligation into the written deal scope.

## Evidence standard

A useful finding records four things:

- **Claim:** what the seller or buyer believes to be true
- **Evidence:** the source and reporting period used to verify it
- **Finding:** what the evidence supports or contradicts
- **Impact:** how the finding affects price, risk, timing, or transfer scope

Prefer direct, read-only access to primary systems during diligence. Redact personal data and never place passwords, private keys, recovery codes, or production exports in a shared checklist.

## Approck resources

- [Estimate an app's value](https://approck.com/valuation)
- [Browse verified subscription apps](https://approck.com/products)
- [Prepare an app for sale](https://approck.com/developers)

## Contributing

Read [AGENTS.md](AGENTS.md) for content, evidence, and verification rules. [CLAUDE.md](CLAUDE.md) links to the same instructions.

Corrections and practical additions are welcome. When a checklist item depends on an app-store rule, include a link to the current official Apple or Google documentation.

## License

The documentation is available under the [Creative Commons Attribution 4.0 International License](LICENSE.md).
