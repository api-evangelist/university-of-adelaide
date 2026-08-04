# University of Adelaide (university-of-adelaide)

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

The University of Adelaide is a public research university in Adelaide, South Australia, founded in 1874 and ranked #72 in the QS World University Rankings 2025. This repository catalogs the institution's public, developer-facing API footprint as an [APIs.json](http://apisjson.org/) profile. The university's machine-readable surface is concentrated in open scholarly infrastructure — a DSpace institutional repository and an Adelaide Figshare research-data instance — rather than a consolidated developer portal.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-adelaide/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-adelaide-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, Research, Institutional Repository, Open Data, Australia

## APIs

- **Adelaide Research & Scholarship REST API** — DSpace 7.6.1 HAL/JSON REST API for the institutional repository. Docs: https://wiki.lyrasis.org/display/DSDOC7x/REST+API · Base: https://digital.library.adelaide.edu.au/server/api
- **Adelaide Research & Scholarship OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint. Docs: https://www.openarchives.org/OAI/openarchivesprotocol.html · Base: https://digital.library.adelaide.edu.au/server/oai/request
- **Adelaide Figshare Research Data API** — Research data via the shared Figshare public REST API and OAI-PMH. Docs: https://docs.figshare.com/ · Base: https://api.figshare.com/v2

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-adelaide-plans-pricing.yml](plans/university-of-adelaide-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-adelaide-rate-limits.yml](rate-limits/university-of-adelaide-rate-limits.yml)
- FinOps: [finops/university-of-adelaide-finops.yml](finops/university-of-adelaide-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.adelaide.edu.au/
- GitHub: https://github.com/universityofadelaide
- LinkedIn: https://au.linkedin.com/school/uniofadelaide/
- Authentication (CAS SSO): https://login.adelaide.edu.au/
- Review: [review.yml](review.yml)

## Notes

All cataloged interfaces were probed directly. The DSpace REST API, DSpace OAI-PMH, and the Figshare public API/OAI-PMH endpoints returned live responses. No unified self-service public API developer portal was found for the university; course-outlines and timetable systems are web applications with no documented public API, and no public status page resolved. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
