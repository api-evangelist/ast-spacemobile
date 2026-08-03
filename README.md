# AST SpaceMobile (ast-spacemobile)

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

AST SpaceMobile (NASDAQ: ASTS) is a United States satellite operator building the SpaceMobile Network, a space-based cellular broadband constellation of BlueBird satellites carrying the largest commercial phased-array antennas in low Earth orbit, designed to deliver 4G and 5G directly to standard, unmodified smartphones. It sits upstream of the retail telecom market as a wholesale coverage layer — signals from a handset are relayed by satellite to a small number of in-country ground gateways, which compensate for Doppler and delay and then hand the traffic into a mobile network operator's core, where the operator completes the call and bills the subscriber. Distribution runs entirely through partner carriers, with agreements covering nearly 60 mobile network operators serving over 3 billion subscribers, including AT&T, Verizon, Vodafone, Rakuten, Bell, TELUS and stc, plus strategic investment from Google and American Tower.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ast-spacemobile/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ast-spacemobile/refs/heads/main/apis.yml)

## Tags

- Telecommunications
- United States
- Satellite
- Direct-to-Device
- Non-Terrestrial Network
- Mobile Network Operator
- Broadband
- 5G
- Roaming
- Space

## Timestamps

- **Created:** 2026-07-25
- **Modified:** 2026-07-25

## APIs

None. As of the July 25, 2026 review, AST SpaceMobile publishes no public API.

This is the honest finding, and for a non-terrestrial-network operator at this stage it is the expected one. Every first-party developer host and path probed either failed to resolve or returned 404: `developer.ast-science.com`, `developers.ast-science.com`, `docs.ast-science.com`, `api.ast-science.com` and `opengateway.ast-science.com` have no DNS records, and `/developer`, `/developers`, `/api`, `/opengateway`, `/openapi.json`, `/swagger.json` and `/api-docs` all return 404. There is no API documentation, no OpenAPI or Swagger, no SDK, no GitHub organization, no Postman workspace, no GraphQL endpoint, no webhook catalog and no `.well-known` metadata. The `openapi/` directory is deliberately absent because nothing real was found to put in it.

### CAMARA and GSMA Open Gateway posture

**No CAMARA reference found — not a member, not named, nothing callable.** A full-text scan of the home, partners, network, how-it-works, how-you-connect, mission, company and FAQ pages plus the press-release index returned zero occurrences of "CAMARA", "Open Gateway", "API", "SDK", "developer" or "TM Forum". Not one CAMARA API — Number Verification, SIM Swap, Device Location, Device Status, Quality on Demand, Carrier Billing, KYC Match, Scam Signal, Device Swap, Population Density — is claimed, documented or exposed. There is not even a press release to discount here; AST has made no CAMARA claim at all.

AST is not a GSMA Open Gateway participant. Open Gateway is an operator commitment layer signed by carriers that own subscribers; AST is a wholesale coverage supplier to those carriers and holds no retail subscriber base of its own. Its partners — AT&T, Verizon, Vodafone, Rakuten, Bell, TELUS, stc — are the Open Gateway signatories, which is a partner fact, not an AST fact. No Aduna channel relationship is claimed either.

No TM Forum Open API conformance certification is claimed. No 3GPP NEF or SCEF surface, network slicing API or edge/MEC API is described — AST's architecture is documented purely in radio and transport terms, and any Network Exposure Function in this value chain belongs to the terminating carrier.

### How developers actually reach SpaceMobile

Indirectly, through someone else. Developers cannot buy, provision or call anything from AST SpaceMobile. SpaceMobile coverage reaches end users as a Day Pass, a monthly add-on, or a standalone plan sold by a partner mobile network operator, and any programmable interface a developer touches — messaging, location, verification, connectivity — belongs to that operator.

## Links

- [Website](https://ast-science.com/)
- [Company](https://ast-science.com/company/)
- [Partners](https://ast-science.com/partners/)
- [SpaceMobile Network](https://ast-science.com/spacemobile-network/)
- [How It Works](https://ast-science.com/how-it-works/)
- [FAQs](https://ast-science.com/faqs/)
- [Blog](https://ast-science.com/blog/)
- [Press Releases](https://ast-science.com/press-releases/)
- [Investor Relations](https://investors.ast-science.com/)
- [LinkedIn](https://www.linkedin.com/company/ast-science/)

## Review

See [review.yml](review.yml) for the full reviewer findings, including every probe URL with its HTTP status.
