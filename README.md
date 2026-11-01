# University of Adelaide

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

The University of Adelaide is a public research university in Adelaide, South Australia, founded in 1874 and a member of the Group of Eight. Since January 2026 it has been superseded by Adelaide University, the merged institution formed with the University of South Australia: ROR records the University of Adelaide (https://ror.org/00892tw58) as inactive with successor Adelaide University (https://ror.org/028g18b61), adelaide.edu.au now serves the merged institution, and its DataCite and Australian Access Federation records both read "Adelaide University". It operates no public developer program. A full crawl of the 10,326-URL adelaide.edu.au sitemap on 2026-08-30 returned no developer portal, no API reference, no open-data portal, and no OpenAPI under any path. Its genuinely institution-operated machine-readable surfaces are three: the DSpace 7.6.1 "Adelaide Research & Scholarship" repository at digital.library.adelaide.edu.au, which serves a keyless HAL/JSON REST API and a live OAI-PMH 2.0 endpoint under the institution's own Handle prefix 2440; and the institution's Shibboleth SAML 2.0 Identity Provider at au-idp.adelaide.edu.au, registered in the Australian Access Federation and scoped to adelaide.edu.au. Everything else that looks like an Adelaide API is a vendor contract running under an Adelaide name: adelaide.figshare.com is a Figshare tenancy, myuni.adelaide.edu.au is an Instructure Canvas tenancy exposing LTI 1.3 and OIDC discovery, and access.adelaide.edu.au is a PeopleSoft student system behind Okta SSO. This profile is deliberately thin because the footprint is thin.

**Areas:** University · Higher Education · Education · Australia · Group of Eight · Research Repository · Research Data · Library · OAI-PMH · DSpace · Identity Federation · Shibboleth

## University of Adelaide on APIs.io

Everything profiled for University of Adelaide is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/university-of-adelaide/](https://apis.io/providers/university-of-adelaide/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Adelaide Research & Scholarship REST API](https://apis.io/apis/university-of-adelaide/dspace-rest/) — DSpace 7.6.1 HAL/JSON REST API for the University of Adelaide institutional repository "Adelaide Research & Scholarship", exposing communities, collections,…
- [Adelaide Research & Scholarship OAI-PMH](https://apis.io/apis/university-of-adelaide/dspace-oai-pmh/) — OAI-PMH 2.0 metadata harvesting endpoint for the "Adelaide Research & Scholarship" repository, on the same institution-operated host. Confirmed live…
- [Adelaide University Shibboleth Identity Provider (SAML 2.0)](https://apis.io/apis/university-of-adelaide/saml-idp/) — The institution's own Shibboleth SAML 2.0 Identity Provider, serving machine-readable EntityDescriptor metadata from its own host. Confirmed live…
- [Adelaide Figshare Research Data Repository — Adelaide tenancy](https://apis.io/apis/university-of-adelaide/figshare-tenancy/) — The University's research-data repository runs on Figshare at the institution-specific host adelaide.figshare.com. The DATA, the DOIs and the curation are…
- [MyUni Learning Management System (Instructure Canvas) — Adelaide tenancy](https://apis.io/apis/university-of-adelaide/myuni-canvas/) — The University's LMS runs on Instructure Canvas at myuni.adelaide.edu.au. The tenancy, roster and course content are Adelaide's; the API contract is…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Vocabulary (1)

The provider's domain terms, defined.

- [University of Adelaide Research Data Vocabulary](https://apis.io/vocabularies/university-of-adelaide/university-of-adelaide-vocabulary/)

#### Examples (1)

Example requests and responses.

- [University Of Adelaide Dspace Rest Root Response](https://apis.io/examples/university-of-adelaide/university-of-adelaide-dspace-rest-root-response/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [University Of Adelaide Authentication](https://apis.io/security/university-of-adelaide/university-of-adelaide-authentication/)
- [University Of Adelaide Domain Security](https://apis.io/security/university-of-adelaide/university-of-adelaide-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [University Of Adelaide Plans Pricing](https://apis.io/plans/university-of-adelaide/university-of-adelaide-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [University Of Adelaide Rate Limits](https://apis.io/rate-limits/university-of-adelaide/university-of-adelaide-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [University Of Adelaide Finops](https://apis.io/finops/university-of-adelaide/university-of-adelaide-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://adelaide.edu.au/)
- [Blog](https://adelaide.edu.au/about/news/)
- [Terms of service](https://adelaide.edu.au/about/disclaimer/)
- [Privacy policy](https://adelaide.edu.au/about/policies/privacy-policy/)
- [GitHub](https://github.com/universityofadelaide)

## API Evangelist rating

**Kin Score 22.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 10.5 |
| Contract governance | 3.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 23.8 |
| Access clarity | 26.3 |

**Agent readiness 4.4** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/university-of-adelaide/](https://apis.io/providers/university-of-adelaide/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for University of Adelaide: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/university-of-adelaide/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
