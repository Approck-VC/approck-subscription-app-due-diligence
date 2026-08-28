# Subscription App Technical Review

The objective is to determine whether the buyer can build, release, operate, secure, and maintain the product without hidden dependence on the seller.

## Ownership and scope

- Identify every source-code repository and its legal owner
- Confirm the seller can transfer the code, designs, content, data, and documentation
- List third-party, open-source, commercial, and custom-licensed components
- Match the reviewed code to the live iOS and Android applications
- Record any shared code or infrastructure that is excluded from the transaction
- Identify contractors or agencies whose work lacks clear assignment terms

## Reproducible build

- Clone the repositories into a clean environment
- Follow the written setup instructions without undocumented seller intervention
- Install pinned or otherwise documented dependency versions
- Build release candidates for each supported platform
- Run the available automated tests and record the results
- Confirm signing and release steps without copying live private keys into the review environment
- Compare application identifiers, versions, and enabled capabilities with the live store records

A successful local build is not proof that production deployment, signing, backend access, or store submission will work. Verify those as separate steps.

## Architecture and maintainability

- Supported platforms, minimum OS versions, languages, and frameworks
- Application modules and major data flows
- Backend services, databases, queues, storage, and scheduled jobs
- Environments and deployment process
- API ownership, versioning, rate limits, and failure modes
- Monitoring, logging, alerting, crash reporting, and backups
- Known incidents, unresolved defects, and deferred migrations
- Bus factor and areas understood by only one person

Record unsupported dependencies, end-of-life runtimes, fragile manual steps, and components that cannot be transferred.

## Security and privacy

- Authentication, authorization, and privileged roles
- Secret storage and rotation process
- Encryption in transit and at rest
- Administrative interfaces and production access paths
- Dependency and source-code vulnerability findings
- Data collected, purpose, retention, deletion, and export behavior
- Consent flows, tracking disclosures, and privacy-policy consistency
- Incident history and unresolved security reports
- Backup restoration and recovery access

Use read-only access where possible. Do not request passwords in documents or chat. Transfer secrets through an agreed secure channel and rotate them at the correct closing stage.

## Services and dependencies

For every external service, capture:

| Field | Example evidence |
| --- | --- |
| Purpose | What breaks if the service is unavailable |
| Owner | Legal entity or person controlling the account |
| Transfer path | Ownership change, invited access, migration, or replacement |
| Cost | Current plan and usage-based charges |
| Data | Stored personal, operational, or financial data |
| Credentials | Credential type and rotation owner, never the secret itself |
| Contract | Renewal date, minimum term, and assignment restriction |

Common dependencies include cloud hosting, domains, email, analytics, attribution, push notifications, subscription platforms, payment processors, support tools, AI providers, content feeds, and advertising accounts.

## Store and release history

- Current production and staged versions
- Rejected releases, warnings, suspensions, or removals
- Privacy labels, Data safety declarations, age ratings, and regulated features
- In-app purchase and subscription configuration
- TestFlight or internal-testing setup
- Signing keys, certificates, provisioning profiles, and app-signing ownership
- Push, universal links, deep links, associated domains, and server notifications

Verify transfer-specific rules against the current platform documentation rather than relying on an old checklist.

## Operational handover

- Release and rollback runbooks
- Infrastructure diagram and service inventory
- On-call, alert, and incident-response process
- Customer-support workflow and response backlog
- Moderation, content, localization, and recurring maintenance tasks
- Product roadmap and known commitments
- Named owners for each handover action
- Time-boxed seller support after closing

## Findings report

Classify each material finding consistently:

| Severity | Meaning |
| --- | --- |
| Critical | Prevents safe ownership, transfer, build, release, or operation |
| High | Could cause material outage, security exposure, store action, or unexpected cost |
| Medium | Requires planned remediation but does not block transfer |
| Low | Documentation, maintainability, or process improvement |

Each finding should include evidence, business impact, recommended action, owner, and whether it must be resolved before closing.
