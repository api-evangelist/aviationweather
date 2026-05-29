# Aviation Weather Center (aviationweather)

The NOAA/NWS Aviation Weather Center (AWC) public data API provides machine-to-machine access to operational aviation weather products including METARs, TAFs, pilot reports (PIREPs/AIREPs), SIGMETs (domestic and international), G-AIRMETs and AIRMETs, Center Weather Advisories (CWAs), TFM convective forecasts (TCFs), area forecasts, area forecast discussions, meteorological information statements (MIS), and reference data for stations, airports, NAVAIDs, fixes, features, and obstacles. Responses are available in raw text, JSON, GeoJSON, XML, and (for METAR/TAF) IWXXM formats.

**URL:** [Visit APIs.json URL](https://aviationweather.gov/data/api/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Type

- **x-type:** government
- **x-tier:** 3 (bulk-registered from public-apis, enriched 2026-05-29)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Weather

## Tags

- Aviation, Weather, Government, NOAA, NWS, METAR, TAF, PIREP, SIGMET, AIRMET, Open Data, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Aviation Weather Data API

Public REST API exposing operational aviation weather products produced by the NOAA/NWS Aviation Weather Center. Endpoints cover decoded weather observations (METAR), terminal forecasts (TAF), pilot reports (PIREP/AIREP), domestic and international SIGMETs, G-AIRMETs and AIRMETs, CWAs, TFM convective forecasts, area forecasts, forecast discussions, meteorological information statements, plus reference data for stations, airports, NAVAIDs, fixes, features, and obstacles. All endpoints are public and do not require an API key.

**Human URL:** [https://aviationweather.gov/data/api/](https://aviationweather.gov/data/api/)

**Base URL:** `https://aviationweather.gov/api/data`

#### Tags

- Weather, Aviation, Government, Open Data

#### Endpoints (20 operations across 2 tags)

**Weather Data**
- `GET /api/data/metar` — Get METAR Observations
- `GET /api/data/taf` — Get TAFs
- `GET /api/data/pirep` — Get Pilot Reports
- `GET /api/data/airsigmet` — Get Domestic SIGMETs
- `GET /api/data/isigmet` — Get International SIGMETs
- `GET /api/data/gairmet` — Get US Graphical AIRMETs
- `GET /api/data/airmet` — Get AIRMETs
- `GET /api/data/tcf` — Get TFM Convective Forecast
- `GET /api/data/cwa` — Get CWSU Center Advisories
- `GET /api/data/windtemp` — Get Wind and Temperature Point Data
- `GET /api/data/areafcst` — Get US Area Forecasts
- `GET /api/data/fcstdisc` — Get US Forecast Discussions
- `GET /api/data/mis` — Get Meteorological Information Statement

**Navigational Data**
- `GET /api/data/stationinfo` — Get Station Info
- `GET /api/data/airport` — Get Airport Info
- `GET /api/data/navaid` — Get Navigational Aid Info
- `GET /api/data/fix` — Get Navigational Fix and Waypoint Info
- `GET /api/data/feature` — Get Feature Info
- `GET /api/data/obstacle` — Get Obstacle Info

**Legacy**
- `GET /api/data/dataserver` — Get Data Server (ADDS passthrough)

#### Properties

- [Documentation](https://aviationweather.gov/data/api/)
- [OpenAPI](openapi/aviationweather-openapi.yml)
- [OpenAPISource](https://aviationweather.gov/data/schema/openapi.yaml)
- [Examples](https://aviationweather.gov/data/example/)
- [TermsOfService](https://aviationweather.gov/data/api/)
- [RateLimits](rate-limits/aviationweather-rate-limits.yml)
- [Status](https://aviationweather.gov/)

## Common Properties

- [Website](https://aviationweather.gov/)
- [Agency: NOAA / NWS / Aviation Weather Center](https://www.weather.gov/aviation/awc)
- [Parent Organization: NOAA NWS NCEP](https://www.ncep.noaa.gov/)
- [Sister Service: api.weather.gov](https://www.weather.gov/documentation/services-web-api)
- [Help](https://aviationweather.gov/help/)
- [Related Service: WIFS API](https://aviationweather.gov/wifs/api?f=html)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Privacy Policy](https://www.weather.gov/privacy)
- [License: U.S. Government Work](https://www.weather.gov/disclaimer)

## Integrations

| Name | Description |
|------|-------------|
| [api.weather.gov](https://api.weather.gov/) | NWS general weather API (separate from AWC aviation surface). |
| [NOAA WIFS](https://aviationweather.gov/wifs/) | Weather Information For System — bulk GRIB/IWXXM distribution. |
| [FAA SWIM](https://www.faa.gov/air_traffic/technology/swim) | FAA System Wide Information Management — operational distribution channel that also carries AWC products. |

## Solutions

| Name | Description |
|------|-------------|
| Flight planning | Pre-flight briefings combining METAR, TAF, PIREP, SIGMET, and AIRMET data. |
| Dispatch and operations | Airline/charter dispatch consuming SIGMET/AIRMET for route avoidance. |
| General aviation apps | EFB (electronic flight bag) apps surfacing aviation weather on mobile. |
| Research and analytics | Academic and research use of historical aviation weather observations and advisories. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AviationWeather.gov API v4.0](openapi/aviationweather-openapi.yml) — Imported from the upstream `aviationweather.gov/data/schema/openapi.yaml`, with `servers`, license, contact, and Title Case operation summaries added.

### JSON Schema

- [METAR](json-schema/aviationweather-metar-schema.json)
- [TAF](json-schema/aviationweather-taf-schema.json)
- [PIREP](json-schema/aviationweather-pirep-schema.json)
- [Domestic SIGMET](json-schema/aviationweather-airsigmet-schema.json)
- [International SIGMET](json-schema/aviationweather-isigmet-schema.json)
- [G-AIRMET](json-schema/aviationweather-gairmet-schema.json)
- [AIRMET](json-schema/aviationweather-airmet-schema.json)
- [CWA](json-schema/aviationweather-cwa-schema.json)
- [Station Info](json-schema/aviationweather-station-schema.json)
- [Airport Info](json-schema/aviationweather-airport-schema.json)

### JSON Structure

- [METAR](json-structure/aviationweather-metar-structure.json)
- [TAF](json-structure/aviationweather-taf-structure.json)
- [PIREP](json-structure/aviationweather-pirep-structure.json)
- [Domestic SIGMET](json-structure/aviationweather-airsigmet-structure.json)
- [International SIGMET](json-structure/aviationweather-isigmet-structure.json)
- [G-AIRMET](json-structure/aviationweather-gairmet-structure.json)
- [AIRMET](json-structure/aviationweather-airmet-structure.json)
- [CWA](json-structure/aviationweather-cwa-structure.json)
- [Station Info](json-structure/aviationweather-station-structure.json)
- [Airport Info](json-structure/aviationweather-airport-structure.json)

### JSON-LD

- [aviationweather-context.jsonld](json-ld/aviationweather-context.jsonld) — JSON-LD context mapping AWC fields to schema.org, SOSA/SSN observation vocabulary, and an `awc:` namespace.

### Examples

Per-operation request/response example payloads (20):

- [METAR](examples/aviationweather-metar-example.json), [TAF](examples/aviationweather-taf-example.json), [PIREP](examples/aviationweather-pirep-example.json)
- [Domestic SIGMET](examples/aviationweather-airsigmet-example.json), [International SIGMET](examples/aviationweather-isigmet-example.json)
- [G-AIRMET](examples/aviationweather-gairmet-example.json), [AIRMET](examples/aviationweather-airmet-example.json)
- [TFM Convective Forecast](examples/aviationweather-tcf-example.json), [CWA](examples/aviationweather-cwa-example.json)
- [Wind/Temp](examples/aviationweather-windtemp-example.json), [Area Forecast](examples/aviationweather-areafcst-example.json)
- [Forecast Discussion](examples/aviationweather-fcstdisc-example.json), [MIS](examples/aviationweather-mis-example.json)
- [Station Info](examples/aviationweather-stationinfo-example.json), [Airport](examples/aviationweather-airport-example.json)
- [NAVAID](examples/aviationweather-navaid-example.json), [Fix](examples/aviationweather-fix-example.json)
- [Feature](examples/aviationweather-feature-example.json), [Obstacle](examples/aviationweather-obstacle-example.json)
- [Data Server (legacy)](examples/aviationweather-dataserver-example.json)

## Capabilities

Self-contained Naftiko capability files. Each file inlines its own consumes block plus REST and MCP adapters, with no shared/ directory and no cross-file references.

### Aviation Weather Data API

| Capability | Tag | Operations | Tools | Personas |
|------------|-----|------------|-------|----------|
| [Weather Data](capabilities/aviationweather-weather-data.yaml) | Weather Data | 13 | 13 MCP / 13 REST | Pilot, Dispatcher, AirTrafficControl, WeatherAnalyst |
| [Navigational Data](capabilities/aviationweather-navigational-data.yaml) | Navigational Data | 6 | 6 MCP / 6 REST | Pilot, Dispatcher, EFBDeveloper, Researcher |

## Vocabulary

- [aviationweather-vocabulary.yml](vocabulary/aviationweather-vocabulary.yml) — Unified taxonomy mapping 20 resources, 1 action verb (get), 2 workflows, and 6 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [aviationweather-rules.yml](rules/aviationweather-rules.yml) — 48 Spectral rules across 13 categories enforcing AWC API conventions (kebab-style lowercase paths under `/api/data/`, camelCase JSON properties, `format` enum constraint, no auth required, query-only GET-only surface).

## Rate Limits

- [aviationweather-rate-limits.yml](rate-limits/aviationweather-rate-limits.yml) — 100 requests/minute per consumer IP; 1 request/minute per endpoint per thread; max 400 entries per response; 15 days historical depth; no paid tier.

## Notes

This repo was initially bulk-registered as part of a public-apis catalog sweep on 2026-05-28, then fully enriched via the government API profiling pipeline on 2026-05-29 against the upstream OpenAPI 3.1 spec published by the Aviation Weather Center.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
