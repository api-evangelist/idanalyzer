# ID Analyzer

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

ID Analyzer is a cloud-based identity verification platform providing REST APIs for extracting and validating data from passports, driver licenses, and ID cards across 190+ countries. Core capabilities include document OCR with anti-forgery detection, biometric face matching and liveness verification, AML/PEP sanctions screening, and a hosted DocuPass KYC onboarding flow. The platform is ISO 27001 certified and compliant with GDPR, HIPAA, and NIST IAL2 standards.

**Website:** [https://www.idanalyzer.com](https://www.idanalyzer.com/en)
**API Documentation:** [https://developer.idanalyzer.com](https://developer.idanalyzer.com/docs/about-id-analyzer)
**Pricing:** [https://www.idanalyzer.com/en/pricing](https://www.idanalyzer.com/en/pricing)
**Status:** [https://status.idanalyzer.com](https://status.idanalyzer.com)
**Blog:** [https://www.idanalyzer.com/en/blog](https://www.idanalyzer.com/en/blog)
**GitHub:** [https://github.com/idanalyzer](https://github.com/idanalyzer)
**X:** [@idanalyzer](https://x.com/idanalyzer)

## APIs

- **Scanner API** — Document OCR and fraud analysis for 3,000+ document formats
- **Biometric API** — Face matching, liveness detection, and deepfake detection
- **AML Screening API** — Sanctions, watchlist, and PEP database search
- **DocuPass API** — Hosted KYC verification flow with QR code and webhook support
- **Transaction Vault API** — Identity record storage with audit trail and export

## Base URLs

- US: `https://api2.idanalyzer.com`
- EU: `https://api2-eu.idanalyzer.com`

## Authentication

API key authentication. Pass your key per SDK client instance or via the `IDANALYZER_KEY` environment variable.

## SDKs

Official SDKs (v2): Python, Node.js, PHP, .NET, Go, Java
Mobile SDKs: iOS (DocuPass), Android (DocuPass), Flutter, React Native

---

*This profile is maintained by [Kin Lane](mailto:kin@apievangelist.com) as part of the [APIs.json](https://apisjson.org) catalog.*
