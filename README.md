# Wheels Up

Wheels Up Experience Inc. (NYSE: UP) is a leading on-demand private aviation provider in the U.S., offering charter and membership programs, commercial travel benefits through a strategic partnership with Delta Air Lines, and cargo services.

This repository profiles Wheels Up as part of the API Evangelist network. Wheels Up does **not** publish a public developer API — all booking, fleet management, and member services are exposed exclusively through its members-only mobile app and members.wheelsup.com web portal.

## Delta Air Lines Rescue (September 2023)

On September 20, 2023, Wheels Up was rescued from potential bankruptcy by a Delta Air Lines-led consortium that closed a $500M financing package:

- **Investors**: Delta Air Lines, Certares Management LLC, Knighthead Capital Management LLC, Cox Enterprises
- **Structure**: $350M term loan funded at closing + $100M revolving credit facility from Delta, with additional financing
- **Outcome**: Delta and partners took an approximately 95% controlling equity stake
- **Background**: Founder/CEO Kenny Dichter resigned May 9, 2023; in early August 2023 the company disclosed "substantial doubts" about its ability to continue as a going concern
- **Source**: [Aviation Week](https://aviationweek.com/business-aviation/aircraft-propulsion/wheels-finalizes-500-million-investment-rescue-package) · [AIN](https://www.ainonline.com/aviation-news/business-aviation/2023-09-20/delta-air-lines-consortium-completes-wheels-deal)

Wheels Up is now operated as a Delta-affiliated private aviation arm, with deep integration into the Delta loyalty and commercial product (including industry-first self-booking of Delta commercial flights inside the Wheels Up members app, announced 2025).

## Post-Rescue Transformation

- **October 2023** — Aircraft management division sold to Airshare (90 aircraft, 300 employees transferred)
- **2024** — Pivoted from membership-only economics toward programmatic charter and corporate programs (Up for Business, Custom Enterprise Solutions)
- **November 13, 2024** — Acquired the Embraer Phenom 300/300E fleet of GrandView Aviation (17 aircraft, $105M) and secured a $332M revolving equipment notes facility with Bank of America
- **Fleet modernization** — Transitioning four jet types to two: Embraer Phenom 300 series and Bombardier Challenger 300/350. Sold all 13 owned Citation X aircraft. King Air operations continue in existing service areas.
- **September 2025** — Launched Signature Membership portfolio with $200K prepaid deposit, $500 monthly fee, Dynamic and Fixed nationwide-rate plans across Phenom 300 and Challenger 300 series

## Membership Surface

- **Connect** — entry-tier membership (lowest deposit)
- **Core / Signature** — flagship membership with dynamic or fixed nationwide pricing
- **Up for Business** — corporate program for small/medium enterprises ($250K or $300K+ deposit)
- **Custom Enterprise Solutions** — larger corporate accounts ($500K or $1M+ deposit)
- **Charter Marketplace** — in-app real-time inventory of safety-vetted partner aircraft (non-members pay a $495 transaction fee per flight)

## Why No Public API

Wheels Up's booking surface is a members-only mobile app (iOS/Android) and the members.wheelsup.com web portal. There is no developer portal, no published OpenAPI, no public SDK, no rate card API, and no third-party app program. B2B operator connectivity was routed historically through the **Avianis** platform that Wheels Up acquired in September 2019, but Avianis is not a public-developer surface for Wheels Up's customer-facing booking.

Charter brokers and operators may discover Wheels Up empty-legs through marketplace platforms (Avinode and similar), but no Wheels Up-branded API is published.

## GitHub Presence

- [github.com/wheelsup](https://github.com/wheelsup) — original organization (created 2017), 5 public repositories, all forks of unrelated tooling (Adyen iOS, GraphQL Faker, Pravega CloudEvents, Sabre Postman collections, internal app-business-intelligence). No original SDKs, CLIs, or API artifacts.
- [github.com/Wheels-Up](https://github.com/Wheels-Up) — newer organization (created May 2025), 0 public repositories.

## Artifacts in this Repository

| Folder | Contents |
|---|---|
| `apis.yml` | APIs.json 0.19 index of Wheels Up's web presence, membership tiers, Delta rescue details, and GrandView acquisition |
| `README.md` | This file |

Because Wheels Up publishes no public OpenAPI, AsyncAPI, JSON Schema, or SDK, this repository does **not** include `openapi/`, `asyncapi/`, `json-schema/`, `json-structure/`, `json-ld/`, `examples/`, `rules/`, `capabilities/`, `vocabulary/`, `plans/`, `rate-limits/`, or `finops/` folders. Per the API Evangelist pipeline rules, empty/placeholder specs are not generated.

## Tier Reason

Tracked in the network registry as `x-tier: 3` with `x-tier-reason: no-apis` — Wheels Up is a notable Delta-controlled private aviation operator but exposes no developer-accessible API surface.

## Sources

- [Wheels Up Experience — Investor Relations](https://investors.wheelsup.com/)
- [Wheels Up — Wikipedia](https://en.wikipedia.org/wiki/Wheels_Up)
- [Delta-Backed Wheels Up Avoids Bankruptcy With $500M Investment — Simple Flying](https://simpleflying.com/delta-backed-private-jet-wheels-up-avoids-bankruptcy/)
- [Wheels Up Finalizes $500M Investment Rescue Package — Aviation Week](https://aviationweek.com/business-aviation/aircraft-propulsion/wheels-finalizes-500-million-investment-rescue-package)
- [Delta Consortium Acquires Majority Stake in Wheels Up — AIN](https://www.ainonline.com/aviation-news/business-aviation/2023-09-20/delta-air-lines-consortium-completes-wheels-deal)
- [Wheels Up Announces Fleet Modernization Strategy — PR Newswire (Oct 2024)](https://www.prnewswire.com/news-releases/wheels-up-announces-fleet-modernization-strategy-and-associated-transactions-302283330.html)
- [Wheels Up Launches New Membership Portfolio — Investor Relations (Sep 2025)](https://investors.wheelsup.com/news/news-details/2025/Wheels-Up-Launches-New-Membership-Portfolio/default.aspx)
- [Wheels Up to Launch Self-Booking of Delta Commercial Flights for Members — Investor Relations (2025)](https://investors.wheelsup.com/news/news-details/2025/Wheels-Up-to-Launch-Industry-First-Self-Booking-of-Delta-Commercial-Flights-for-Members/default.aspx)

---

*Profiled by [API Evangelist](https://apievangelist.com) — last updated 2026-05-23.*
