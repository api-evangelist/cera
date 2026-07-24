# Cera

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
