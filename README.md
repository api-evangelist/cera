# Cera

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

Cera is a United Kingdom-based digital-first home healthcare company, founded in 2016 and headquartered in London, that describes itself as Europe's largest provider of in-home care. It delivers home care, live-in care, nurse-led and complex care, extra-care housing, supported living, and specialist learning-disability and autism support, wrapped around a proprietary digital platform that applies data analytics and machine learning so carers can collect, monitor, and react to vital-sign changes in real time.

## API Posture

As of this review (2026-07-24), Cera exposes **no public developer portal, no self-serve REST API, and no HL7 FHIR endpoint or CapabilityStatement**. The `developer.`, `docs.`, `api.`, and `fhir.` subdomains do not resolve, and the primary site (`ceracare.co.uk`) is a Next.js single-page app that returns the same app shell for `/developers`, `/api`, `/openapi.json`, and `/.well-known/smart-configuration` (soft 404s, no real specs). Cera's GitHub organization ([github.com/ceracare](https://github.com/ceracare)) contains only infrastructure-as-code and interview repositories — no API, SDK, OpenAPI, or FHIR projects.

Cera's platform is an internal, operator-facing product delivered through consumer and carer mobile apps rather than a documented partner API. This profile is an honest identity-only stub recording the absence of a public API surface.

## Links

- Website: https://ceracare.co.uk/
- About: https://ceracare.co.uk/about-cera
- Services: https://ceracare.co.uk/our-services
- GitHub: https://github.com/ceracare
- LinkedIn: https://uk.linkedin.com/company/ceracare

Home market: United Kingdom.
