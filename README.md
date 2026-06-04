# University of Adelaide (university-of-adelaide)

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
