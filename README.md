# Finmid

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

finmid is a Berlin-based embedded lending and B2B payments infrastructure provider that lets software platforms and marketplaces offer financing — cash advances, term loans, and business loans — to their customers across 30+ European markets without becoming a lender or handling the regulatory complexity themselves. finmid exposes two REST APIs: the B2B Payments API (buyer/seller onboarding, payment requests, payouts, and repayment) and the Capital API (pre-approved offer generation, an embeddable acceptance widget, business onboarding/KYB, fundings, and payments). Both APIs are JSON over HTTPS, authenticated with an environment-scoped X-API-Key header, with a separate sandbox environment, HMAC-signed webhooks for asynchronous events, and HTTP Message Signatures (RFC 9421, Ed25519) for platform-provided capital payout execution.

**Areas:** Company · Embedded Finance · Embedded Lending · B2B Payments · Fintech · Lending · Capital · Financing · Payments · Marketplace

## Finmid on APIs.io

Everything profiled for Finmid is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/finmid/](https://apis.io/providers/finmid/)** — or go straight to one of the APIs or properties below.

### APIs (20)

- [finmid B2B Payments API](https://apis.io/apis/finmid/finmid-b2b-payments-api-2/) — Embed B2B payment and financing into a platform: onboard buyers and sellers, create payment requests financed by a finmid loan, create payouts, upload…
- [finmid Capital API](https://apis.io/apis/finmid/finmid-capital-api-2/) — Offer pre-approved, customizable financing to businesses on a platform: real-time offer generation, an embeddable acceptance widget (iframe), business…
- [Finmid Beta Endpoints API](https://apis.io/apis/finmid/finmid-beta-endpoints-api/) — The Beta Endpoints API from Finmid — 1 operation(s) for beta endpoints.
- [Finmid Business API](https://apis.io/apis/finmid/finmid-business-api/) — The Business API from Finmid — 6 operation(s) for business.
- [Finmid Buyer API](https://apis.io/apis/finmid/finmid-buyer-api/) — The Buyer API from Finmid — 4 operation(s) for buyer.
- [Finmid Capital Max API](https://apis.io/apis/finmid/finmid-capital-max-api/) — Endpoints for managing Capital Max applications.
- [Finmid CSP Financial Document API](https://apis.io/apis/finmid/finmid-csp-financial-document-api/) — The CSP Financial Document API from Finmid — 4 operation(s) for csp financial document.
- [Finmid Document API](https://apis.io/apis/finmid/finmid-document-api/) — The Document API from Finmid — 2 operation(s) for document.
- [Finmid Funding API](https://apis.io/apis/finmid/finmid-funding-api/) — The Funding API from Finmid — 2 operation(s) for funding.
- [Finmid Funding Application API](https://apis.io/apis/finmid/finmid-funding-application-api/) — Endpoints for managing Funding Applications.
- [Finmid Incoming Webhook API](https://apis.io/apis/finmid/finmid-incoming-webhook-api/) — The Incoming Webhook API from Finmid — 2 operation(s) for incoming webhook.
- [Finmid Offer API](https://apis.io/apis/finmid/finmid-offer-api/) — The Offer API from Finmid — 4 operation(s) for offer.
- [Finmid Offer Group API](https://apis.io/apis/finmid/finmid-offer-group-api/) — The Offer Group API from Finmid — 3 operation(s) for offer group.
- [Finmid Onboarding API](https://apis.io/apis/finmid/finmid-onboarding-api/) — The Onboarding API from Finmid — 1 operation(s) for onboarding.
- [Finmid Payment API](https://apis.io/apis/finmid/finmid-payment-api/) — The Payment API from Finmid — 4 operation(s) for payment.
- [Finmid Payment Request API](https://apis.io/apis/finmid/finmid-payment-request-api/) — The Payment Request API from Finmid — 6 operation(s) for payment request.
- [Finmid Sales statements API](https://apis.io/apis/finmid/finmid-sales-statements-api/) — The Sales statements API from Finmid — 1 operation(s) for sales statements.
- [Finmid Seller API](https://apis.io/apis/finmid/finmid-seller-api/) — The Seller API from Finmid — 4 operation(s) for seller.
- [Finmid Simulation API](https://apis.io/apis/finmid/finmid-simulation-api/) — The Simulation API from Finmid — 17 operation(s) for simulation.
- [Finmid Tasks API](https://apis.io/apis/finmid/finmid-tasks-api/) — The Tasks API from Finmid — 2 operation(s) for tasks.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Finmid Webhooks](https://apis.io/asyncapis/finmid/finmid-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [finmid](https://apis.io/servers/finmid/finmid/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Finmid Agentic Access](https://apis.io/agentic-access/finmid/finmid-agentic-access/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Finmid API Rules](https://apis.io/rules/finmid/finmid-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Finmid Authentication](https://apis.io/security/finmid/finmid-authentication/)
- [Finmid Domain Security](https://apis.io/security/finmid/finmid-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.finmid.com)
- [Documentation](https://docs.finmid.com)
- [Getting started](https://docs.finmid.com/docs/finmid-products)
- [API reference](https://docs.finmid.com/reference/api-introduction)
- [Sign up](https://platform.finmid.com)
- [Blog](https://finmid.com/blog/)
- [Terms of service](https://finmid.com/legal/)
- [Privacy policy](https://finmid.com/privacy/)
- [GitHub](https://github.com/finmid)
- [Status](https://finmid.statuspage.io)

## API Evangelist rating

**Kin Score 44.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 57.3 |
| Contract governance | 22.0 |
| Operational transparency | 22.4 |
| Developer ergonomics | 48.8 |
| Access clarity | 21.1 |

**Agent readiness 37.7** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | yes |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 25.9** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/finmid/](https://apis.io/providers/finmid/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Finmid: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/finmid/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
