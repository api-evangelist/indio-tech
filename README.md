# Indio Technologies (indio-tech)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Indio Technologies is a cloud-based insurance application and submissions platform for commercial insurance agencies and brokers, acquired by and now part of **Applied Systems**. Indio replaces manual PDF forms and spreadsheets with a library of 10,000+ digitally enhanced "smart" insurance forms and ACORD applications, a submission workspace that packages digital applications, schedule workbooks, document-upload requests and e-signature requests, plus secure document sharing and a "TurboTax-like" experience for insureds.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/indio-tech/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/indio-tech/refs/heads/main/apis.yml)

## Access Model — Important

**Indio does not publish a self-service public developer API.** There is no public REST reference, no OpenAPI definition, no API-key self-signup, and no developer portal specific to Indio. Where programmatic data exchange exists, it is **partner/carrier-gated** and brokered through Applied Systems:

- **Applied Epic integration + SDK** — bi-directional data exchange between Indio and the Applied Epic agency management system.
- **IVANS data exchange API** — used (via the Applied/IVANS division) to move submission and proposal data between agencies, brokers and carriers.
- **Applied DevCenter** — the gated Applied Systems partner developer program (subscribe-to-APIs model for Applied products).

Because of this, the API groupings in `apis.yml` are **logical, modeled surfaces** (`endpointsModeled: true`) derived from Indio's documented product concepts. No concrete endpoints, paths, or base URLs are fabricated, because none are publicly documented.

## Tags

- Insurance
- Insurtech
- Insurance Applications
- Submissions
- Digital Forms
- ACORD
- E-Signature
- Commercial Insurance
- Applied Systems
- Partner API

## Timestamps

- **Created:** 2026-07-10
- **Modified:** 2026-07-10

## APIs (Modeled)

Each grouping below is `endpointsModeled: true` — a logical map of Indio's product data model, not a documented public API.





## Common Properties

- [LinkedIn](https://www.linkedin.com/company/indio-technologies)
- [Website](https://www.useindio.com)
- [Documentation](https://help.useindio.com/en/)
- [Developer Program (Applied DevCenter)](https://devcenter.myappliedproducts.com/home)
- [Parent Company (Applied Systems)](https://www1.appliedsystems.com/en-us/solutions/for-agents/insurance-application-software/indio/)
- [Plans](plans/indio-tech-plans-pricing.yml)

## Pricing

Indio is sold as a per-seat SaaS product, not a metered API. Public directories list a starting price around **$50 per user per month**, with full agency pricing quoted by Indio / Applied Systems sales. There is no separately priced public API plan. See [plans/indio-tech-plans-pricing.yml](plans/indio-tech-plans-pricing.yml).

## Review

Does Indio expose a documented public WebSocket API? **No.** See [review.yml](review.yml). Indio publishes no public WebSocket, REST, or SSE API; programmatic access is partner-gated through Applied Systems.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
