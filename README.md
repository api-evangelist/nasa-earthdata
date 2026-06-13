# NASA Earthdata

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
