# Prudential plc (prudential-plc)

Prudential plc is a life and health insurance and asset management group incorporated in England and Wales and listed on the London, Hong Kong, Singapore and New York exchanges, with its principal operating office in Hong Kong and roots in London going back to 1848. Its home market for this profile is the United Kingdom, but its book is almost entirely Asian and African: life protection, health and medical, savings and retirement, takaful, pensions and Hong Kong Mandatory Provident Funds, plus asset management under the Eastspring brand, across Hong Kong, Singapore, Malaysia, Indonesia, the Philippines, Thailand, Vietnam, Taiwan, India, mainland China, Cambodia, Laos, Myanmar and a dozen African markets including Kenya, Uganda, Ghana, Nigeria and Zambia.

It is no longer a UK retail insurer at all — the UK and Europe business was demerged as M&G plc in 2019 and the US business as Jackson Financial in 2021 — so the familiar UK "Pru" brands at pru.co.uk belong to M&G, not to this company.

Its API posture is that there is no public API posture. Prudential plc publishes no developer portal, no API reference, no downloadable OpenAPI or Swagger document and no partner integration surface of any kind. The `developer`, `developers`, `docs`, `api`, `apis`, `partners`, `portal` and `sandbox` subdomains of prudentialplc.com all fail to resolve, and `/developers`, `/api`, `/developer`, `/partners` and `/integrations` on the corporate site all return HTTP 404. The group's stated technology strategy is inward-facing — AI, automation, cloud and a global AI Lab running over a hundred internal use cases — and its distribution is built on tied agency forces and exclusive bancassurance partnerships, which are commercial and contractual relationships rather than published API programmes.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/prudential-plc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/prudential-plc/refs/heads/main/apis.yml)

## Tags

- Insurance
- United Kingdom
- Life Insurance
- Health Insurance
- Carrier
- Asset Management
- Pensions
- Takaful
- Bancassurance
- Asia
- Africa

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

None. Prudential plc publishes no public, documented API. The `apis[]` array in `apis.yml` is intentionally empty — see [review.yml](review.yml) for the full probe record.

## API Posture

| Signal | Finding |
| --- | --- |
| Developer portal | None. Every developer/api/docs/partners subdomain of prudentialplc.com fails DNS (HTTP 000); every developer path on the corporate site returns HTTP 404 |
| Self-serve? | No — there is no portal to gate, self-serve or otherwise |
| OpenAPI harvested | 0 — no OpenAPI, Swagger, AsyncAPI, GraphQL SDL or .proto exists on any resolvable Prudential plc host |
| Auth model | None published — no API is documented, so no scheme could be attributed |
| Quote / Bind / Issue / FNOL | None exposed. All four happen through tied agents, myPrudential policyholder portals and bancassurance branch systems |
| Webhooks / AsyncAPI | None published |
| Postman | No first-party workspace; the third-party "PrudentialWatch" workspace is unaffiliated |
| GraphQL / gRPC | None. `/graphql` returns HTTP 404 |
| ACORD posture | No ACORD reference found — no ACORD, AL3, ACORD XML, NGDS or IVANS mention anywhere in the public estate |
| Real integration channel | Tied agency forces and exclusive bancassurance partnerships (Standard Chartered, CIMB Thai, MSB, SeABank, Yoma Bank, Bank Syariah Indonesia) — commercial contracts, not APIs |
| Home market | United Kingdom (incorporated England and Wales, LSE-listed); operating book is Asia and Africa |

## Disambiguation

Two name collisions matter for this record and are documented in full in [review.yml](review.yml):

1. **Prudential Financial, Inc.** (NYSE: PRU, Newark, New Jersey) is a **separate company** with no ownership relationship to Prudential plc. It *does* operate a developer portal at developers.prudential.com and a partner API portal at developer.apis.prudential.com. None of that belongs here — WHOIS on prudential.com returns "Registrant Organization: The Prudential Insurance Company of America". That company is profiled separately in this network as `prudential-financial`.
2. **The UK "Pru" consumer brands** (pru.co.uk, pruadviser.co.uk, Prudential Assurance Company Limited) went to **M&G plc** in the October 2019 demerger and are not Prudential plc properties.

A third, weaker collision: `developer-pacs.prudential.com.sg`, described in search results as a "Prudential APIM Team" developer portal for Prudential Assurance Company Singapore, is dead — a stale Imperva CNAME with no resolvable A record. Nothing has been recorded from it.

## Common Properties

- [Website](https://www.prudentialplc.com/en/)
- [About](https://www.prudentialplc.com/en/about-us/our-purpose-and-mission/)
- [Technology Strategy](https://www.prudentialplc.com/en/about-us/our-strategy/technology/)
- [Distribution Strategy](https://www.prudentialplc.com/en/about-us/our-strategy/distribution/)
- [Newsroom](https://www.prudentialplc.com/en/newsroom/)
- [Investor Relations](https://www.prudentialplc.com/en/investors/overview/)
- [Contact](https://www.prudentialplc.com/en/contact-us/)
- [Privacy Notice](https://www.prudentialplc.com/en/site-services/privacy-notice/)
- [Terms of Use](https://www.prudentialplc.com/en/site-services/terms-of-use/)
- [GitHub Organization](https://github.com/PrudentialCorporationAsia)
- [LinkedIn](https://www.linkedin.com/company/prudentialplc)

## Maintainers

- Kin Lane — kin@apievangelist.com
