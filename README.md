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

The University of Adelaide is a public research university in Adelaide, South Australia, founded in 1874 and a member of the Group of Eight. Since January 2026 it has been superseded by **Adelaide University**, the merged institution formed with the University of South Australia — ROR records [University of Adelaide](https://ror.org/00892tw58) as *inactive* with successor [Adelaide University](https://ror.org/028g18b61), and adelaide.edu.au now serves the merged institution. This repository catalogs the institution's public, developer-facing footprint as an [APIs.json](http://apisjson.org/) profile.

This profile is deliberately thin, because the footprint is thin. A full crawl of the 10,326-URL adelaide.edu.au sitemap on 2026-08-30 returned no developer portal, no API reference, no open-data portal, and no OpenAPI under any path. `llms.txt` and `.well-known/security.txt` both 404.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-adelaide/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-adelaide-api-evangelist&utm_content=repo

## Type

- university / Public Research University / Index / Consumer / Public

## Tags

University, Higher Education, Education, Australia, Group of Eight, Research Repository, Research Data, Library, OAI-PMH, DSpace, Identity Federation, Shibboleth, Metadata, Course Catalog

## Surfaces, by who actually operates them

A university is a federation of buyers, not a producer. Every surface below carries an operator.

**Institution-operated** — Adelaide's own host, Adelaide's own deployment:

- **Adelaide Research & Scholarship REST API** — DSpace 7.6.1 HAL/JSON, keyless read access. Base: https://digital.library.adelaide.edu.au/server/api · Contract: https://github.com/DSpace/RestContract
- **Adelaide Research & Scholarship OAI-PMH** — OAI-PMH 2.0, Handle prefix 2440, earliest datestamp 2002. Base: https://digital.library.adelaide.edu.au/server/oai/request
- **Shibboleth Identity Provider (SAML 2.0)** — entityID `urn:mace:federation.org.au:testfed:au-idp.adelaide.edu.au`, scope `adelaide.edu.au`, registered in the Australian Access Federation. Metadata: https://au-idp.adelaide.edu.au/idp/shibboleth

**Tenant** — Adelaide's data on someone else's contract. The vendor's specification is deliberately *not* stored in this repository:

- **Adelaide Figshare** — research data on Figshare. https://adelaide.figshare.com/ (answers 202 to this network: a bot challenge, not a dead host)
- **MyUni** — Instructure Canvas LMS. Public LTI 1.3 JWKS and OIDC discovery; REST API returns 401. https://myuni.adelaide.edu.au/

## Domain standards (Kin Score `education` regime)

Probed, not claimed. See [conformance/university-of-adelaide-education-standards.yml](conformance/university-of-adelaide-education-standards.yml).

| Standard | Operator | Evidence |
|---|---|---|
| `oai-pmh` 2.0 | institution | Identify → 200 |
| `saml` 2.0 | institution | IdP metadata → 200 |
| `shibboleth` | institution | `shibmd:Scope adelaide.edu.au` |
| `datacite` | institution | DataCite provider `adelaide`, one repository client |
| `lti` 1.3 | tenant | MyUni LTI JWKS → 200, AGS line items → 401 |

`scim`, `oneroster`, `caliper`, `qti` and `ed-fi` were probed and not found. `orcid` and `crossref` are registered as DSpace external sources but the live ORCID query failed, so neither is claimed.

## Artifacts

- Conformance: [conformance/university-of-adelaide-education-standards.yml](conformance/university-of-adelaide-education-standards.yml)
- Authentication: [authentication/university-of-adelaide-authentication.yml](authentication/university-of-adelaide-authentication.yml)
- Vocabulary: [vocabulary/university-of-adelaide-vocabulary.yml](vocabulary/university-of-adelaide-vocabulary.yml)
- Examples (real probed responses): [examples/university-of-adelaide-examples.yml](examples/university-of-adelaide-examples.yml)
- Plans: [plans/university-of-adelaide-plans-pricing.yml](plans/university-of-adelaide-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-adelaide-rate-limits.yml](rate-limits/university-of-adelaide-rate-limits.yml)
- FinOps: [finops/university-of-adelaide-finops.yml](finops/university-of-adelaide-finops.yml)
- Domain Security: [security/university-of-adelaide-domain-security.yml](security/university-of-adelaide-domain-security.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-08-30

## Common Properties

- Website: https://adelaide.edu.au/
- GitHub Organization: https://github.com/universityofadelaide
- LinkedIn: https://au.linkedin.com/school/uniofadelaide/
- Research Repository: https://digital.library.adelaide.edu.au/
- Library: https://adelaide.edu.au/library/
- Course Catalog: https://adelaide.edu.au/study/
- Identity Federation: https://au-idp.adelaide.edu.au/idp/shibboleth
- AI Policy: https://adelaide.edu.au/about/policies/academic-integrity-policy/
- AI Tooling (ChatMate): https://app.chatmate.adelaide.edu.au/
- Authentication (CAS SSO): https://login.adelaide.edu.au/cas/login
- Privacy Policy: https://adelaide.edu.au/about/policies/privacy-policy/
- Review: [review.yml](review.yml)

## Correction notice — 2026-08-30

The June 2026 profile of this institution credited it with ten OpenAPI definitions, eleven `apis[]` entries (altmetric, articles, authors, collections, institutions, oauth, other, profiles, projects, symplectic), twenty Postman/OpenCollection files, two JSON Schemas, two JSON Structures, two examples, two Spectral rulesets, a vocabulary, a JSON-LD context, an authentication profile, an OAuth scope list, an agentic-access profile covering 157 operations, and a capability map.

Every one of those artifacts derived from a **single Figshare contract** — `info.title: Figshare API`, contact "Figshare Support", `servers[0]: https://api.figshare.com/v2` — that eleven other institutions in this catalog shipped verbatim as their own. It is Figshare's engineering, not Adelaide's. **47 files were removed.** The Figshare *deployment* is kept, correctly labelled as a tenant relationship, because a tenancy is a real institutional fact.

The corrected profile scores lower than the one it replaces. That is the correction working.

## Notes

Every interface listed was probed directly on 2026-08-30 and the status codes are recorded in `x-coverage.evidence` in [apis.yml](apis.yml). Three things exist but are not credited as surfaces, and are named rather than assumed: the Research GitLab at `git.adelaide.edu.au` is registered in the Australian Access Federation and resolves to a campus address but does not answer on 443 from this network; the research-computing and HPC pages now redirect into a ServiceNow employee portal that returns a 1,447-byte JavaScript shell; and `adelaide.figshare.com` returns a bot challenge. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
