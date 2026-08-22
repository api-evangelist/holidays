# Holiday API (holidays)

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
