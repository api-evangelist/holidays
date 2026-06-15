# Holiday API (holidays)

Holiday API is a commercial reference-data service that delivers verified public holidays, observances, country and language metadata, and workday calculations for 250 countries and 3,680+ state/province subdivisions in 100+ languages. Operated by Gravity Boulevard, LLC, it exposes five JSON endpoints under https://holidayapi.com/v1/ with official client libraries for Go, Node.js, PHP, Python, Ruby, and Raku.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/holidays/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/holidays/main/apis.yml)

## Tags

- Calendar
- Holidays
- Public Holidays
- Observances
- Reference Data
- Countries
- Languages
- Workdays
- Business Days
- Localization

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Holiday API — Holidays

Retrieves public holidays and observances for countries, states, and provinces. Supports filtering by year, month, day, language, previous/upcoming queries, and free-text search.

- **Human URL:** [https://holidayapi.com/docs](https://holidayapi.com/docs)
- **Base URL:** `https://holidayapi.com/v1`

#### Tags

- Holidays
- Calendar
- Public Holidays

#### Properties

- [Documentation](https://holidayapi.com/docs)
- [OpenAPI](openapi/holidays-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/holidays-holiday-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/holidays-holiday-structure.json)
- [Example](examples/holidays-list-holidays-example.json)
- [JSON-LD](json-ld/holidays-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Holiday API — Countries

Lists supported countries with ISO codes (alpha-2, alpha-3, numeric), spoken languages, currencies, flag image URLs, weekend days, and state/province subdivisions.

- **Human URL:** [https://holidayapi.com/countries](https://holidayapi.com/countries)
- **Base URL:** `https://holidayapi.com/v1`

#### Tags

- Countries
- Reference Data
- Subdivisions

#### Properties

- [Documentation](https://holidayapi.com/docs)
- [OpenAPI](openapi/holidays-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/holidays-country-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/holidays-country-structure.json)
- [Example](examples/holidays-list-countries-example.json)
- [JSON-LD](json-ld/holidays-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Holiday API — Languages

Lists supported languages (ISO 639-1 codes with documented exceptions) used to retrieve localized holiday names. Holiday API supports 100+ languages.

- **Human URL:** [https://holidayapi.com/languages](https://holidayapi.com/languages)
- **Base URL:** `https://holidayapi.com/v1`

#### Tags

- Languages
- Localization
- Reference Data

#### Properties

- [Documentation](https://holidayapi.com/docs)
- [OpenAPI](openapi/holidays-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/holidays-language-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/holidays-language-structure.json)
- [Example](examples/holidays-list-languages-example.json)
- [JSON-LD](json-ld/holidays-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Holiday API — Workdays

Two operations for working-day arithmetic that honor a country's workweek and public holidays: get the workday that occurs a given number of days after a start date, and count the number of workdays between two dates.

- **Human URL:** [https://holidayapi.com/docs](https://holidayapi.com/docs)
- **Base URL:** `https://holidayapi.com/v1`

#### Tags

- Workdays
- Business Days
- Calendar

#### Properties

- [Documentation](https://holidayapi.com/docs)
- [OpenAPI](openapi/holidays-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/holidays-workday-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/holidays-workday-structure.json)
- [Example](examples/holidays-get-workday-example.json)
- [Example](examples/holidays-get-workdays-example.json)
- [JSON-LD](json-ld/holidays-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Website](https://holidayapi.com/)
- [Portal](https://holidayapi.com/)
- [Documentation](https://holidayapi.com/docs)
- [OpenAPI](openapi/holidays-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/holidays-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/holidays-response-structure.json)
- [JSON-LD](json-ld/holidays-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/holidays-rules.yml)
- [Vocabulary](vocabulary/holidays-vocabulary.yml)
- [Plans](plans/holidays-plans-pricing.yml)
- [Rate Limits](rate-limits/holidays-rate-limits.yml)
- [Pricing](https://holidayapi.com/pricing)
- [Sign Up](https://holidayapi.com/signup)
- [Login](https://holidayapi.com/login)
- [Terms of Service](https://holidayapi.com/terms)
- [Contact](https://holidayapi.com/contact)
- [GitHub Organization](https://github.com/holidayapi)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Example](examples/holidays-error-example.json)
- [SDK](https://github.com/holidayapi/holidayapi-go)
- [SDK](https://github.com/holidayapi/holidayapi-node)
- [SDK](https://github.com/holidayapi/holidayapi-php)
- [SDK](https://github.com/holidayapi/holidayapi-python)
- [SDK](https://github.com/holidayapi/holidayapi-ruby)
- [SDK](https://github.com/holidayapi/holidayapi-raku)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
