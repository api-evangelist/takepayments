# takepayments (takepayments)

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

takepayments (a trading name of Payzone UK Limited) is a United Kingdom payment gateway and merchant-services provider that lets businesses accept card payments online, in person, and over the phone. It exposes a real public developer surface across two products — an online payment gateway and an integrated Terminal API — but does not publish a downloadable OpenAPI/Swagger definition; its API reference is documentation-only.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/takepayments/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/takepayments/refs/heads/main/apis.yml)

## Tags

- Payments
- United Kingdom
- Payment Gateway
- Payment Processing
- Card Payments
- Card Machines
- In-Person Payments
- Ecommerce
- PSP
- Acquiring

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs


#### Tags

- Payment Gateway
- Card Payments
- Ecommerce
- Hosted Payment Page
- Direct Integration

#### Properties

- [Documentation](https://www.takepayments.com/developer-support/)
- [Resources](https://www.takepayments.com/developer-support/resources/)
- [Integration Guide (PDF)](https://mapi.takepayments.com/media/mtapfhfn/takepayments-gateway-integration-guide_v3-02_07-22.pdf)
- [Direct Code Pack](https://mapi.takepayments.com/media/auilrieh/direct.zip)
- [Hosted Code Pack](https://mapi.takepayments.com/media/oetnwi1n/hosted.zip)
- [Shopping Cart Plugins](https://www.takepayments.com/developer-support/shopping-carts/)

### takepayments Terminal API

A REST/JSON API hosted on Azure API Management for pairing and driving takepayments card machines (Move5000, PAX A920 Pro) from an integrated app or POS. Documented operations include Authentication, Start a Transaction, Pairing a Terminal, Split Bill & Gratuity, and Pay at Table. Authentication is OAuth 2.0 client-credentials issued by Microsoft Azure AD, with the JWT passed as an `Authorization: Bearer` header. Sandbox and production base URLs are published on the developer portal; no downloadable OpenAPI/Swagger is provided.

- **Human URL:** [https://developer.takepayments.com/apis](https://developer.takepayments.com/apis)
- **Base URL:** `https://takepayments-integrated-prod-apim.azure-api.net/`

#### Tags

- Terminal API
- In-Person Payments
- Card Machines
- Pay at Table
- REST

#### Properties

- [Documentation](https://developer.takepayments.com/)
- [API Reference](https://developer.takepayments.com/apis)
- [Authentication](https://developer.takepayments.com/documentation/authentication)
- [Start a Transaction](https://developer.takepayments.com/documentation/Start-Transaction)
- [Online SDKs](https://developer.takepayments.com/online-sdk)

## Common Properties

- [Website](https://www.takepayments.com/)
- [Developer Portal](https://developer.takepayments.com/)
- [Documentation](https://www.takepayments.com/developer-support/)
- [API Reference](https://developer.takepayments.com/apis)
- [SDK](https://developer.takepayments.com/online-sdk)
- [Shopping Cart Plugins](https://www.takepayments.com/developer-support/shopping-carts/)
- [GitHub Organization](https://github.com/takepayments)
- [LinkedIn](https://www.linkedin.com/company/takepayments-limited/)
- [Blog](https://www.takepayments.com/blog/)
- [Support](https://www.takepayments.com/partner-support/)
- [Contact Us](https://www.takepayments.com/contact-us/)
- [Terms of Service](https://www.takepayments.com/terms-and-conditions/)
- [Privacy Policy](https://www.takepayments.com/privacy-policy/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
