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
