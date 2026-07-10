# Indio Technologies (indio-tech)

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

### Indio Submissions API

The core submission object — the workspace that packages digital applications, schedule workbooks, document-upload requests and e-signature requests for a single insured; created, populated, sent to insureds, renewed, and submitted to carriers.

- **Human URL:** [https://help.useindio.com/en/collections/2173888-submission-features](https://help.useindio.com/en/collections/2173888-submission-features)

### Indio Forms and Applications API

The library of 10,000+ digitally enhanced "smart" insurance forms and ACORD applications that can be added to a submission, auto-mapped, pre-filled, and completed and signed electronically.

- **Human URL:** [https://help.useindio.com/en/articles/2143244-how-to-add-and-select-forms](https://help.useindio.com/en/articles/2143244-how-to-add-and-select-forms)

### Indio Clients API

The client/insured records a submission is created against, synchronized bi-directionally with Applied Epic and Policy Works via Applied Systems integrations. The nearest documented programmatic surface is the Applied Epic SDK.

- **Human URL:** [https://help.useindio.com/en/](https://help.useindio.com/en/)

### Indio Documents and E-Signature API

Document-upload requests, secure document sharing, and the full e-signature solution that ride inside a submission — product features exposed in the Indio portal.

- **Human URL:** [https://help.useindio.com/en/](https://help.useindio.com/en/)

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
