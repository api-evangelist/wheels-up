# Wheels Up

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
