---
title: "App Transfer & Acquisition Process"
url: https://approck.com/knowledge/transfer-process
description: "An app sale uses Apple's official app-transfer process. Changes to an organization's Account Holder follow separate eligibility rules."
---

# App Transfer & Acquisition Process

> Published at [approck.com/knowledge/transfer-process](https://approck.com/knowledge/transfer-process)

## App Transfer

Apple's [official app-transfer process](https://developer.apple.com/help/app-store-connect/transfer-an-app/overview-of-app-transfer) moves an eligible app from the seller's account to the buyer's account. The app keeps its reviews, ratings, and Bundle ID, and users can continue receiving updates.

**Before transfer:**

- Check Apple's current transfer criteria for both accounts and the app.
- Back up the app information and agree on the assets included in the sale.
- Plan subscription, signing, and service changes required by the app's capabilities.

## Account Holder Changes

For an organization, Apple allows the [Account Holder role](https://developer.apple.com/help/account/access/transfer-the-account-holder-role/) to move to an eligible employee who can legally bind that organization. Individual memberships have limited exceptions that require Apple Developer Support.

Changing login credentials, two-factor authentication, or banking details does not complete either process. Do not share the seller's Apple Account. Assignment of the Developer Program agreement requires Apple's prior written consent under [its terms](https://developer.apple.com/support/terms/apple-developer-program-license-agreement/).

## Essential Transfer Checklist

Regardless of which method is used, every acquisition should include:

1. **Complete source code** — the latest working build that matches the live App Store version
2. **Design files** — all UI/UX assets (Figma, Sketch, or equivalent)
3. **Payment analytics access** — transfer of RevenueCat, Adapty, or equivalent service accounts
4. **Privacy policies** — updated to reflect new ownership or transferred as-is for later update
5. **Server infrastructure** — if the app uses backend services, transfer or migrate hosting
6. **Banking details update** — ensure Apple pays revenue to the new owner's account

## Using an Escrow Service

For transactions between parties who don't have an established trust relationship, using an escrow mechanism is strongly recommended. A neutral third party holds both the funds and the app during the verification period. Once both sides confirm the transfer is complete and accurate, the funds are released to the seller and the app to the buyer.

This eliminates the most common risk in private app sales: one party fulfilling their obligation while the other doesn't.


## Frequently asked questions

### How should an app sale transfer ownership?

Use Apple's official app-transfer process after checking eligibility and preparing the required subscription and service changes.

### Can a buyer simply take over the seller's login?

No. Login and banking changes do not transfer ownership. Account Holder changes have separate eligibility rules, and assignment of the Developer Program agreement requires Apple's consent.

### When should escrow be used in app acquisitions?

Escrow is recommended when parties do not have an established trust relationship or transaction risk is high.
