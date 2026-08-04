# Diamond Search (diamond-search)

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

IDEX Online is the leading polished diamonds trading platform for professionals, providing unbiased, market-driven diamond pricing tools, news and research. The IDEX Onsite and Data Report APIs deliver natural diamond, lab grown diamond, and market data feeds to subscribers of the IDEX trading platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/diamond-search/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/diamond-search/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Diamonds
- Lab Grown
- Pricing
- Trading

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-05-19

## APIs

### IDEX Onsite Full Feed API

In this natural diamond feed API you will send an HTTP request with the requested identifiers in JSON, and you will get the full details of matching pre-filtered diamonds back in the requested format. This service is available as an add-on to all subscribers of the IDEX trading platform, however, results may vary based on your subscription type and permissions. Filters and markups can be set on IDEX.

- **Human URL:** [https://api.idexonline.com/Onsite/FullFeed](https://api.idexonline.com/Onsite/FullFeed)
- **Base URL:** `https://api.idexonline.com/onsite/api`

#### Tags

- Diamonds
- Feed

#### Properties

- [Documentation](https://api.idexonline.com/Onsite/FullFeed)
- [OpenAPI](openapi/idex-onsite-full-feed-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/idex-onsite-full-feed-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/idex-onsite-full-feed-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IDEX Lab Grown File API

In this lab grown diamond feed API you will send an HTTP request with the requested identifiers in JSON, and you will get the full details of all filtered available diamonds back in a zipped CSV file. This service is available as an add-on to all subscribers of the IDEX trading platform, however, results may vary based on your subscription type and permissions. This feed will return all lab grown diamond listings available for onsite feeds from IDEX.

- **Human URL:** [https://api.idexonline.com/Onsite/LabGrownFullFile](https://api.idexonline.com/Onsite/LabGrownFullFile)
- **Base URL:** `https://api.idexonline.com/Onsite`

#### Tags

- Diamonds
- Lab Grown

#### Properties

- [Documentation](https://api.idexonline.com/Onsite/LabGrownFullFile)
- [OpenAPI](openapi/idex-lab-grown-file-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/idex-lab-grown-file-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/idex-lab-grown-file-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IDEX Data Report API

In this API you will send an HTTP request with a date for which you want the report. You will get back a zipped CSV file. The file creation process may take a few minutes.

- **Human URL:** [https://api.idexonline.com/IdexDataApi/Report3](https://api.idexonline.com/IdexDataApi/Report3)
- **Base URL:** `https://api.idexonline.com/IdexDataApi`

#### Tags

- Diamonds
- Reports

#### Properties

- [Documentation](https://api.idexonline.com/IdexDataApi/Report3)
- [OpenAPI](openapi/idex-data-report-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/idex-data-report-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/idex-data-report-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Newsroom](http://www.idexonline.com/rssfeeds)
- [Login](https://www.idexonline.com/ns24/auth/login.aspx)
- [Sign- Up](https://www.idexonline.com/register.aspx)
- [Privacy Policy](http://www.idexonline.com/Privacy)
- [Terms of Service](http://www.idexonline.com/Conditions)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
