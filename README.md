# NASA Earthdata

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

NASA Earthdata is the Earth Observing System Data and Information System (EOSDIS) portal providing access to NASA's Earth observation data holdings. It offers REST APIs for searching, discovering, and downloading satellite imagery, climate data, and Earth science datasets from NASA missions.

## APIs

### CMR Search API
High-performance metadata search across NASA's Earth science data collections and granules. Supports keyword, spatial, temporal, and faceted queries.
- Base URL: `https://cmr.earthdata.nasa.gov`
- Docs: https://cmr.earthdata.nasa.gov/search/site/docs/search/api.html

### CMR STAC API
STAC-compliant interface over the Common Metadata Repository for discovering and accessing Earth science data using the SpatioTemporal Asset Catalog specification.
- Base URL: `https://cmr.earthdata.nasa.gov/stac`
- Docs: https://github.com/nasa/cmr-stac/blob/master/docs/usage/usage.md

### Earthdata Login API
OAuth2-based authentication and user management for NASA EOSDIS services. Required for accessing protected datasets.
- Base URL: `https://urs.earthdata.nasa.gov`
- Docs: https://www.earthdata.nasa.gov/engage/open-data-services-software/earthdata-developer-portal/earthdata-login-api

### AppEEARS API
RESTful API for submitting point and area data extraction tasks from NASA Earth science datasets with multiple output format options.
- Base URL: `https://appeears.earthdatacloud.nasa.gov/api`
- Docs: https://appeears.earthdatacloud.nasa.gov/api/

### Harmony API
OGC-compliant data transformation service supporting subsetting, reprojection, and format conversion with cloud-native AWS S3 data staging.
- Base URL: `https://harmony.earthdata.nasa.gov`
- Docs: https://harmony.earthdata.nasa.gov/docs

### Global Imagery Browse Services (GIBS) API
Public tile service delivering over 1,000 satellite imagery products via WMTS, WMS, and TMS protocols. No authentication required.
- Base URL: `https://gibs.earthdata.nasa.gov`
- Docs: https://nasa-gibs.github.io/gibs-api-docs/access-basics/

## Access

All NASA Earthdata APIs are free to use. A free [Earthdata Login](https://urs.earthdata.nasa.gov/users/new) account is required for accessing protected datasets and authenticated endpoints.

## Developer Portal

https://www.earthdata.nasa.gov/engage/open-data-services-software/earthdata-developer-portal

## Support

- Forum: https://forum.earthdata.nasa.gov/
- Status: https://status.earthdata.nasa.gov/
- Email: support@earthdata.nasa.gov
