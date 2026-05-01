# Diamond Search (diamond-search)

IDEX Online is the leading polished diamonds trading platform for professionals, providing unbiased, market-driven diamond pricing tools, news and research. This repository captures the IDEX Onsite and Data Report APIs that deliver natural diamond, lab grown diamond, and market data feeds to IDEX trading platform subscribers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/diamond-search/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

- Diamonds, Lab Grown, Pricing, Trading

## Timestamps

- **Created:** 2024-11-13
- **Modified:** 2026-04-28

## APIs

### IDEX Onsite Full Feed API

In this natural diamond feed API you will send an HTTP request with the requested identifiers in JSON, and you will get the full details of matching pre-filtered diamonds back in the requested format. This service is available as an add-on to all subscribers of the IDEX trading platform, however, results may vary based on your subscription type and permissions. Filters and markups can be set on IDEX.

**Human URL:** [https://api.idexonline.com/Onsite/FullFeed](https://api.idexonline.com/Onsite/FullFeed)

**Base URL:** https://api.idexonline.com/onsite/api

#### Tags:

- Diamonds, Feed

#### Properties

- [Documentation](https://api.idexonline.com/Onsite/FullFeed)
- [OpenAPI](openapi/idex-onsite-full-feed-api-openapi.yml)

### IDEX Lab Grown File API

In this lab grown diamond feed API you will send an HTTP request with the requested identifiers in JSON, and you will get the full details of all filtered available diamonds back in a zipped CSV file. This service is available as an add-on to all subscribers of the IDEX trading platform, however, results may vary based on your subscription type and permissions. This feed will return all lab grown diamond listings available for onsite feeds from IDEX.

**Human URL:** [https://api.idexonline.com/Onsite/LabGrownFullFile](https://api.idexonline.com/Onsite/LabGrownFullFile)

#### Tags:

- Diamonds, Lab Grown

#### Properties

- [Documentation](https://api.idexonline.com/Onsite/LabGrownFullFile)
- [OpenAPI](openapi/idex-lab-grown-file-api-openapi.yml)

### IDEX Data Report API

In this API you will send an HTTP request with a date for which you want the report. You will get back a zipped CSV file. The file creation process may take a few minutes.

**Human URL:** [https://api.idexonline.com/IdexDataApi/Report3](https://api.idexonline.com/IdexDataApi/Report3)

#### Tags:

- Diamonds, Reports

#### Properties

- [Documentation](https://api.idexonline.com/IdexDataApi/Report3)
- [OpenAPI](openapi/idex-data-report-api-openapi.yml)

## Common Properties

- [Newsroom](http://www.idexonline.com/rssfeeds)
- [Login](https://www.idexonline.com/ns24/auth/login.aspx)
- [Sign-Up](https://www.idexonline.com/register.aspx)
- [PrivacyPolicy](http://www.idexonline.com/Privacy)
- [TermsOfService](http://www.idexonline.com/Conditions)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
