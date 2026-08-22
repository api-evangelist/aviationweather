# Aviation Weather Center (aviationweather)

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

The NOAA/NWS Aviation Weather Center (AWC) public data API provides machine-to-machine access to operational aviation weather products including METARs, TAFs, pilot reports (PIREPs/AIREPs), SIGMETs (domestic and international), G-AIRMETs and AIRMETs, Center Weather Advisories (CWAs), TFM convective forecasts (TCFs), area forecasts, area forecast discussions, meteorological information statements (MIS), and reference data for stations, airports, NAVAIDs, fixes, features, and obstacles. Responses are available in raw text, JSON, GeoJSON, XML, and (for METAR/TAF) IWXXM formats.

**APIs.json:** [https://aviationweather.gov/data/api/](https://aviationweather.gov/data/api/)

## Tags

- Aviation
- Weather
- Government
- NOAA
- NWS
- METAR
- TAF
- PIREP
- SIGMET
- AIRMET
- Open Data
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Aviation Weather Data API

Public REST API exposing operational aviation weather products produced by the NOAA/NWS Aviation Weather Center. Endpoints cover decoded weather observations (METAR), terminal forecasts (TAF), pilot reports (PIREP/AIREP), domestic and international SIGMETs, G-AIRMETs and AIRMETs, CWAs, TFM convective forecasts, area forecasts, forecast discussions, meteorological information statements, plus reference data for stations, airports, NAVAIDs, fixes, features, and obstacles. All endpoints are public and do not require an API key.

- **Human URL:** [https://aviationweather.gov/data/api/](https://aviationweather.gov/data/api/)
- **Base URL:** `https://aviationweather.gov/api/data`

#### Tags

- Weather
- Aviation
- Government
- Open Data

#### Properties

- [Documentation](https://aviationweather.gov/data/api/)
- [OpenAPI](openapi/aviationweather-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aviationweather.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aviationweather.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Open A P I Source](https://aviationweather.gov/data/schema/openapi.yaml)
- [Examples](https://aviationweather.gov/data/example/)
- [Terms of Service](https://aviationweather.gov/data/api/)
- [Rate Limits](rate-limits/aviationweather-rate-limits.yml)
- [Government A P I](https://aviationweather.gov/data/api/)
- [Data A P I](https://aviationweather.gov/api/data)
- [Open Data A P I](https://aviationweather.gov/api/data)
- [Status](https://aviationweather.gov/)
- [JSON Schema](json-schema/aviationweather-metar-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aviationweather-taf-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aviationweather-pirep-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aviationweather-airsigmet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aviationweather-isigmet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aviationweather-gairmet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aviationweather-airmet-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aviationweather-cwa-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aviationweather-station-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/aviationweather-airport-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/aviationweather-metar-structure.json)
- [JSON Structure](json-structure/aviationweather-taf-structure.json)
- [JSON Structure](json-structure/aviationweather-airport-structure.json)
- [Example Payload](examples/aviationweather-metar-example.json)
- [Example Payload](examples/aviationweather-taf-example.json)
- [Example Payload](examples/aviationweather-pirep-example.json)
- [Example Payload](examples/aviationweather-airsigmet-example.json)
- [Example Payload](examples/aviationweather-isigmet-example.json)
- [Example Payload](examples/aviationweather-gairmet-example.json)
- [Example Payload](examples/aviationweather-airmet-example.json)
- [Example Payload](examples/aviationweather-tcf-example.json)
- [Example Payload](examples/aviationweather-cwa-example.json)
- [Example Payload](examples/aviationweather-windtemp-example.json)
- [Example Payload](examples/aviationweather-areafcst-example.json)
- [Example Payload](examples/aviationweather-fcstdisc-example.json)
- [Example Payload](examples/aviationweather-mis-example.json)
- [Example Payload](examples/aviationweather-stationinfo-example.json)
- [Example Payload](examples/aviationweather-airport-example.json)
- [Example Payload](examples/aviationweather-navaid-example.json)
- [Example Payload](examples/aviationweather-fix-example.json)
- [Example Payload](examples/aviationweather-feature-example.json)
- [Example Payload](examples/aviationweather-obstacle-example.json)
- [Example Payload](examples/aviationweather-dataserver-example.json)

## Common Properties

- [Website](https://aviationweather.gov/)
- [Agency](https://www.weather.gov/aviation/awc)
- [Parent Organization](https://www.ncep.noaa.gov/)
- [Sister Service](https://www.weather.gov/documentation/services-web-api)
- [Documentation](https://aviationweather.gov/data/api/)
- [Examples](https://aviationweather.gov/data/example/)
- [Help](https://aviationweather.gov/help/)
- [Recent Changes](https://aviationweather.gov/data/api/)
- [OpenAPI](openapi/aviationweather-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Vocabulary](vocabulary/aviationweather-vocabulary.yml)
- [JSON-LD](json-ld/aviationweather-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/aviationweather-rules.yml)
- [Related Service](https://aviationweather.gov/wifs/api?f=html)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Privacy Policy](https://www.weather.gov/privacy)
- [License](https://www.weather.gov/disclaimer)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
