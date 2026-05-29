# Holiday API (holidays)

Holiday API is a commercial reference-data service that delivers verified public holidays, observances, country and language metadata, and workday calculations for 250 countries and 3,680+ state/province subdivisions in 100+ languages. Operated by Gravity Boulevard, LLC, it exposes five JSON endpoints under https://holidayapi.com/v1/ with official client libraries for Go, Node.js, PHP, Python, Ruby, and Raku.

**URL:** [Visit APIs.yml URL](https://raw.githubusercontent.com/api-evangelist/holidays/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Calendar, Holidays, Public Holidays, Observances, Reference Data, Countries, Languages, Workdays, Business Days, Localization

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Holiday API — Holidays

Retrieves public holidays and observances for countries, states, and provinces. Supports filtering by year, month, day, language, previous/upcoming queries, and free-text search.

**Human URL:** https://holidayapi.com/docs
**Base URL:** https://holidayapi.com/v1

**Tags:** Holidays, Calendar, Public Holidays

**Properties:**
- [Documentation](https://holidayapi.com/docs)
- [OpenAPI](openapi/holidays-api-openapi.yml)
- [JSON Schema](json-schema/holidays-holiday-schema.json)
- [JSON Structure](json-structure/holidays-holiday-structure.json)
- [Example](examples/holidays-list-holidays-example.json)
- [Naftiko Capability](capabilities/holidays-holidays.yaml)
- [JSON-LD](json-ld/holidays-context.jsonld)

### Holiday API — Countries

Lists supported countries with ISO codes (alpha-2, alpha-3, numeric), spoken languages, currencies, flag image URLs, weekend days, and state/province subdivisions.

**Human URL:** https://holidayapi.com/countries
**Base URL:** https://holidayapi.com/v1

**Tags:** Countries, Reference Data, Subdivisions

**Properties:**
- [Documentation](https://holidayapi.com/docs)
- [OpenAPI](openapi/holidays-api-openapi.yml)
- [JSON Schema](json-schema/holidays-country-schema.json)
- [JSON Structure](json-structure/holidays-country-structure.json)
- [Example](examples/holidays-list-countries-example.json)
- [Naftiko Capability](capabilities/holidays-countries.yaml)
- [JSON-LD](json-ld/holidays-context.jsonld)

### Holiday API — Languages

Lists supported languages (ISO 639-1 codes with documented exceptions) used to retrieve localized holiday names. Holiday API supports 100+ languages.

**Human URL:** https://holidayapi.com/languages
**Base URL:** https://holidayapi.com/v1

**Tags:** Languages, Localization, Reference Data

**Properties:**
- [Documentation](https://holidayapi.com/docs)
- [OpenAPI](openapi/holidays-api-openapi.yml)
- [JSON Schema](json-schema/holidays-language-schema.json)
- [JSON Structure](json-structure/holidays-language-structure.json)
- [Example](examples/holidays-list-languages-example.json)
- [Naftiko Capability](capabilities/holidays-languages.yaml)
- [JSON-LD](json-ld/holidays-context.jsonld)

### Holiday API — Workdays

Two operations for working-day arithmetic that honor a country's workweek and public holidays: get the workday that occurs a given number of days after a start date, and count the number of workdays between two dates.

**Human URL:** https://holidayapi.com/docs
**Base URL:** https://holidayapi.com/v1

**Tags:** Workdays, Business Days, Calendar

**Properties:**
- [Documentation](https://holidayapi.com/docs)
- [OpenAPI](openapi/holidays-api-openapi.yml)
- [JSON Schema](json-schema/holidays-workday-schema.json)
- [JSON Structure](json-structure/holidays-workday-structure.json)
- [Example (Workday)](examples/holidays-get-workday-example.json)
- [Example (Workdays)](examples/holidays-get-workdays-example.json)
- [Naftiko Capability](capabilities/holidays-workdays.yaml)
- [JSON-LD](json-ld/holidays-context.jsonld)

## Common Properties

- [Website](https://holidayapi.com/)
- [Portal](https://holidayapi.com/)
- [Documentation](https://holidayapi.com/docs)
- [Pricing](https://holidayapi.com/pricing)
- [Sign Up](https://holidayapi.com/signup)
- [Login](https://holidayapi.com/login)
- [Terms of Service](https://holidayapi.com/terms)
- [Contact](https://holidayapi.com/contact)
- [GitHub Organization](https://github.com/holidayapi)
- [OpenAPI](openapi/holidays-api-openapi.yml)
- [JSON Schema (Response)](json-schema/holidays-response-schema.json)
- [JSON Structure (Response)](json-structure/holidays-response-structure.json)
- [JSON-LD Context](json-ld/holidays-context.jsonld)
- [Spectral Rules](rules/holidays-rules.yml)
- [Vocabulary](vocabulary/holidays-vocabulary.yml)
- [Plans / Pricing](plans/holidays-plans-pricing.yml)
- [Rate Limits](rate-limits/holidays-rate-limits.yml)
- [FinOps](finops/holidays-finops.yml)
- [Example (Error envelope)](examples/holidays-error-example.json)
- [Public APIs Listing](https://github.com/public-apis/public-apis)

## Official SDKs

| Language | Repo |
|---|---|
| Go | https://github.com/holidayapi/holidayapi-go |
| Node.js / TypeScript | https://github.com/holidayapi/holidayapi-node |
| PHP | https://github.com/holidayapi/holidayapi-php |
| Python | https://github.com/holidayapi/holidayapi-python |
| Ruby | https://github.com/holidayapi/holidayapi-ruby |
| Raku | https://github.com/holidayapi/holidayapi-raku |

## Features

- Verified Holiday Data — proprietary holiday generation system continuously verifies holidays for 250 countries.
- Subdivision Coverage — 3,680 state/province subdivisions on the States & Provinces plan via ISO 3166-2.
- 100+ Languages — localized holiday names via ISO 639-1 codes.
- Workday Calculator — workdays and workday-range arithmetic honoring country-specific workweeks and holidays.
- Historic and Future Dates — coverage from year 1 through year 2050+ on paid plans.
- Multiple Response Formats — JSON, XML, YAML, CSV, TSV, PHP.
- Offline Storage — unlimited offline caching during active paid subscription; 24-hour window on free tier.
- No Velocity Throttling — all plans share a 1M requests/month quota with no per-second or per-minute limits.
- Five-Nines Uptime — enterprise-grade infrastructure designed for 99.999% availability.

## Pricing Summary

| Plan | Price | Use | Years | Subdivisions |
|---|---|---|---|---|
| Free | $0 | Non-commercial | Historic only | No |
| Countries | $249/year | Commercial | 1-2050+ | No |
| States & Provinces | $399/year | Commercial | 1-2050+ | Yes (3,680) |

All plans include 1,000,000 requests/month with no velocity throttling.

## Notes

This entry was originally bulk-registered as part of a public-apis catalog sweep on 2026-05-28 and was profiled in full on 2026-05-29. The provider publishes an official OpenAPI definition at `https://holidayapi.com/holidayapi-v1-openapi.yaml` (vendored at `openapi/holidays-api-openapi.yml`) and maintains six official SDKs under the `holidayapi` GitHub org. No MCP server or Claude Skill was discovered for this provider.

## Maintainers

- **Kin Lane** — kin@apievangelist.com — https://apievangelist.com
