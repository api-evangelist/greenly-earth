# Greenly (greenly-earth)

Greenly is a Paris-headquartered (with offices in London and New York) carbon accounting platform focused on small and mid-sized businesses, helping companies measure, reduce, and report their greenhouse-gas emissions across Scope 1, 2, and 3. The platform automates carbon footprint calculations from accounting, expense, supplier, energy, and cloud data; produces regulator-aligned Bilan Carbone, GHG Protocol, CSRD, CBAM, EUDR, SBTi, CDP, TCFD/IFRS, EcoVadis, and California climate disclosure deliverables; supports product-level LCA; recommends supplier alternatives; and offers a marketplace for verified carbon-offset projects. Greenly also exposes a developer-facing Carbon Analytics REST API (v1.5, hosted at api.greenly.earth) historically built by Offspend, which banks and fintechs use to enrich bank-card transactions with per-purchase CO2 emissions, classify spend into purchase categories, surface lower-carbon alternatives, and book offset volumes against vetted projects — sandbox and production environments are available with API-key authentication on request to contact@greenly.earth.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/greenly-earth/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/greenly-earth/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Carbon Accounting
- Carbon Footprint
- Carbon Analytics
- Greenhouse Gas
- GHG Protocol
- Scope 1
- Scope 2
- Scope 3
- Sustainability
- ESG
- Climate
- CSRD
- CBAM
- EUDR
- SBTi
- TCFD
- EcoVadis
- Bilan Carbone
- Life Cycle Assessment
- Carbon Offsets
- SMB
- Fintech
- Transaction Enrichment

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Greenly Carbon Analytics API

The Greenly Carbon Analytics API (v1.5) is a RESTful service that enriches bank-card and expense transactions with carbon-footprint analytics. Given a transaction label (raw or cleaned), country, amount, and currency, the API classifies the spend into a purchase category, detects the merchant/provider, and returns estimated CO2-equivalent emissions plus optional lower-carbon alternatives. Companion endpoints expose the purchase-category taxonomy, the list of recommended lower-carbon provider alternatives, the catalog of verified carbon offset projects, an offset-booking endpoint, basic user management, and standard live/ready health probes. Two environments are published: a sandbox at https://apisandbox.greenly.earth/v1.5 and production at https://api.greenly.earth/v1.5. Access requires an API key obtained by emailing contact@greenly.earth; the key is passed in the api-key request header. JSON in and out; sample Postman requests are available.

- **Human URL:** [https://api.greenly.earth/v1.5](https://api.greenly.earth/v1.5)
- **Base URL:** `https://api.greenly.earth/v1.5`

#### Tags

- Carbon Analytics
- Carbon Footprint
- Transaction Enrichment
- Carbon Offsets
- Purchase Categories
- Fintech

#### Properties

- [OpenAPI](openapi/greenly-carbon-analytics-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/greenly-carbon-analytics-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/greenly-carbon-analytics-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Sandbox](https://apisandbox.greenly.earth/v1.5)
- [Production](https://api.greenly.earth/v1.5)
- [Documentation](https://bump.sh/greenly)
- [Authentication](https://api.greenly.earth/v1.5)
- [Support](mailto:contact@greenly.earth)

## Common Properties

- [Website](https://greenly.earth/)
- [Portal](https://greenly.earth/en-us)
- [Pricing](https://greenly.earth/info/pricing)
- [Plans](https://greenly.earth/info/pricing)
- [Documentation](https://help.greenly.earth/en/)
- [Support](https://help.greenly.earth/en/)
- [Help Center](https://help.greenly.earth/en/)
- [Contact Us](mailto:contact@greenly.earth)
- [Partners](https://greenly.earth/en-us/partners)
- [Become A Partner](https://greenly.earth/en-us/partners/become-a-partner)
- [Industries](https://greenly.earth/en-us/industries/finance)
- [Industries](https://greenly.earth/en-us/industries/tech)
- [Industries](https://greenly.earth/en-us/industries/retail)
- [Industries](https://greenly.earth/en-us/industries/industrial)
- [Product](https://greenly.earth/en-us/products/carbon-footprint)
- [Product](https://greenly.earth/en-us/products/lca)
- [Product](https://greenly.earth/en-us/products/action-plans)
- [Product](https://greenly.earth/en-us/products/csrd-reporting)
- [Product](https://greenly.earth/en-us/products/cbam)
- [Product](https://greenly.earth/en-us/products/eudr)
- [Product](https://greenly.earth/en-us/products/ecovadis)
- [Product](https://greenly.earth/en-us/products/esg-framework)
- [Product](https://greenly.earth/en-us/products/sustainable-procurement)
- [Product](https://greenly.earth/en-us/products/california-climate-disclosure-laws)
- [Product](https://greenly.earth/en-us/products/tcfd-ifrs-certifications)
- [Product](https://greenly.earth/en-us/products/retail-espr)
- [Methodology](https://greenly.earth/en-us/info/emission-factors)
- [Methodology](https://greenly.earth/en-us/info/artificial-intelligence)
- [Methodology](https://greenly.earth/en-us/info/scientific-board)
- [Methodology](https://greenly.earth/en-us/sbti)
- [Glossary](https://greenly.earth/en-us/glossary)
- [Blog](https://greenly.earth/en-us/blog)
- [Case Studies](https://greenly.earth/en-us/case-study)
- [Resources](https://greenly.earth/en-us/resources/ebooks)
- [Resources](https://greenly.earth/en-us/resources/webinar)
- [Events](https://greenly.earth/en-us/resources/events)
- [Newsletter](https://greenly.earth/en-us/newsletter)
- [Tools](https://greenly.earth/en-us/tools)
- [Press Kit](https://greenly.earth/en-us/info/press-kit)
- [E S G Report](https://greenly.earth/en-us/info/greenly-esg-report)
- [Comparison](https://greenly.earth/en-us/compare/greenly-vs-watershed)
- [Comparison](https://greenly.earth/en-us/compare/greenly-vs-persefoni)
- [Comparison](https://greenly.earth/en-us/compare/greenly-vs-normative)
- [Comparison](https://greenly.earth/en-us/compare/greenly-vs-sweep)
- [Comparison](https://greenly.earth/en-us/compare/greenly-vs-sami)
- [Privacy Policy](https://greenly.earth/en-us/cgv/privacy-policy-greenly-by-offspend)
- [Data Security](https://greenly.earth/en-us/cgv/data-security)
- [LinkedIn](https://www.linkedin.com/company/greenly)
- [Sign Up](https://greenly.earth/en-us/products/demo-steps)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
