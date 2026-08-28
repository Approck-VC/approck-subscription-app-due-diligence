# Subscription App Transfer Checklist

Use this checklist after the transaction scope is clear and before either party treats the app as transferable. Platform rules change, so confirm the current requirements in the official documentation at the time of the transaction.

## Define what is being transferred

- The app alone, selected assets, the operating company, or a developer account
- iOS and Android listings and application identifiers
- Source code, build systems, designs, content, and documentation
- Domains, websites, email, social accounts, and support channels
- Backend infrastructure, databases, storage, and backups
- Analytics, attribution, subscription, and notification services
- Trademarks, licenses, contracts, and other intellectual property
- Customer obligations, refunds, support, and post-closing assistance

Do not assume that a service account, advertising account, payment profile, license, or contract can be assigned. Record the actual transfer or migration method for each asset.

## Confirm store eligibility

### Apple App Store

- Both parties' developer accounts are active and have accepted the required agreements
- The app meets Apple's current transfer criteria and is not in a blocking status
- In-app purchases, subscriptions, TestFlight, Xcode Cloud, and hosted assets are prepared as required
- App-specific shared-secret handling is planned for auto-renewable subscriptions
- The buyer understands which identifiers, analytics, and store records transfer
- Capabilities needing follow-up are inventoried, including push notifications, Sign in with Apple, keychain sharing, Apple Pay, Game Center, iCloud, and associated domains
- New certificates, keys, provisioning profiles, service configuration, or application updates are assigned to named owners

Primary sources:

- [Apple: App transfer criteria](https://developer.apple.com/help/app-store-connect/transfer-an-app/app-transfer-criteria)
- [Apple: Overview of app transfer](https://developer.apple.com/help/app-store-connect/transfer-an-app/overview-of-app-transfer)

### Google Play

- The seller and recipient Play Console accounts are active and verified
- The official app-transfer process is used for an app move
- The package name, registration transaction IDs, and required account details are available
- App signing, API projects, linked services, subscriptions, and financial implications are reviewed
- Data safety, privacy, store contact, and developer-profile information will remain accurate after transfer
- Services that do not transfer automatically have a migration owner and deadline

Primary source:

- [Google Play: Transfer apps to a different developer account](https://support.google.com/googleplay/android-developer/answer/6230247)

## Build the asset register

For every asset, record:

- Current owner and administrator
- Included or excluded status
- Transfer, invite, export, or migration method
- Buyer acceptance test
- Responsible person and target date
- Recurring cost and next renewal date
- Data-protection or contractual restriction

Include code repositories, cloud resources, databases, domains, DNS, certificates, email, support tools, design files, analytics, subscription platforms, push services, payment systems, legal documents, and brand assets.

## Prepare for closing

- Resolve critical diligence findings or document the accepted exception
- Produce current backups and test the required restoration path
- Export reports the seller will lose access to after transfer
- Freeze non-essential releases and infrastructure changes
- Agree on a closing sequence, rollback condition, and communications channel
- Prepare least-privilege buyer access without prematurely surrendering seller control
- List every credential that must be rotated, without placing credential values in the list
- Define escrow, payment, and legal completion conditions with qualified advisors
- Confirm who handles users, refunds, support, privacy requests, and incidents during transition

## Transfer-day sequence

- Confirm authorized representatives and payment or escrow status
- Capture the current production and store state
- Initiate and accept platform transfers through official channels
- Transfer or invite access to the agreed infrastructure and services
- Rotate high-risk credentials in the planned dependency order
- Update billing, recovery contacts, security notifications, and administrator roles
- Run the buyer's acceptance checks
- Record exceptions, failed checks, and temporary seller dependencies
- Obtain written acknowledgment of the assets accepted at closing

Avoid bulk credential rotation before the buyer has working access and a rollback path. Avoid leaving shared seller credentials active after the buyer has confirmed replacement access.

## Buyer acceptance checks

- Store ownership and required roles are visible
- A clean build succeeds for each supported platform
- The buyer can submit or prepare a release with the transferred configuration
- Production services, databases, storage, and backups are accessible
- Subscription validation and server notifications operate correctly
- Authentication, push, deep links, analytics, and crash reporting work
- Domains, DNS, email, privacy pages, and support channels resolve correctly
- Monitoring and security alerts reach the buyer
- Financial and subscription reports are available where the platform permits
- No undocumented seller account is required for normal operation

## Post-transfer

- Complete certificates, keys, profiles, integrations, and app updates that could not be changed earlier
- Remove seller and contractor access after the agreed support window
- Revoke obsolete tokens and recovery methods
- Verify backups and perform a restore exercise where proportionate
- Monitor revenue, renewals, notifications, crashes, and support for regressions
- Update store metadata, privacy disclosures, legal pages, and contact details
- Close or migrate excluded shared services
- Archive signed acceptance records and the final asset register

## Security rule

The checklist may identify credentials but must never contain their values. Use a secure transfer channel, limit access, keep an audit trail, and rotate credentials after the receiving party has confirmed control.

This document is operational guidance, not legal or tax advice. Transaction documents and platform requirements control when they differ from this checklist.
