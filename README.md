# PandaDoc (pandadoc)

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

PandaDoc is a document automation platform that enables businesses to create, send, track, and e-sign documents programmatically. Their developer platform provides REST APIs and embedded tools for integrating document generation, e-signature collection, and workflow automation directly into third-party applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/apis.yml)

## Scope

- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Document Automation
- E-Signature
- Document Management
- Document Generation
- Webhooks

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### PandaDoc REST API

The PandaDoc REST API provides programmatic access to PandaDoc's document automation platform, enabling developers to create, send, track, and manage documents within their own applications. The API supports the full document lifecycle including generating documents from templates with dynamic data, collecting e-signatures, managing recipients, and tracking document status through webhooks. Authentication is handled via API keys, and a free sandbox environment is available for testing integrations before moving to production. An active Enterprise plan is required to access the production API.

- **Human URL:** [https://developers.pandadoc.com/reference/about](https://developers.pandadoc.com/reference/about)
- **Base URL:** `https://api.pandadoc.com/public/v1`

#### Tags

- Document Automation
- E-Signature
- Document Management
- REST

#### Properties

- [Documentation](https://developers.pandadoc.com/reference/about)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pandadoc-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pandadoc-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PandaDoc Document Generation API

The PandaDoc Document Generation API allows developers to programmatically create documents from templates by injecting dynamic data pulled from CRM systems, databases, or other external sources. It supports branded document creation with content placeholders, conditional sections, pricing tables, and custom fields that are populated at runtime. Documents can be generated from existing PandaDoc templates or uploaded PDFs, enabling consistent and automated document production at scale. The API is commonly used in sales, legal, and HR workflows to eliminate manual document preparation.

- **Human URL:** [https://developers.pandadoc.com/docs/getting-started](https://developers.pandadoc.com/docs/getting-started)
- **Base URL:** `https://api.pandadoc.com/public/v1`

#### Tags

- Document Generation
- Templates
- Document Automation
- CRM Integration

#### Properties

- [Documentation](https://developers.pandadoc.com/docs/getting-started)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pandadoc-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pandadoc-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PandaDoc E-Signature API

The PandaDoc E-Signature API enables developers to embed legally binding e-signature workflows directly within their applications using a white-label signing experience. It supports sending signature requests via email or SMS, configuring multiple recipients with defined roles and signing order, and collecting signatures without signers needing a PandaDoc account. The API provides real-time status tracking and generates audit trails and signed PDF copies upon completion. It is designed for use cases in contract management, sales, finance, and any workflow requiring legally compliant electronic signatures.

- **Human URL:** [https://www.pandadoc.com/api/](https://www.pandadoc.com/api/)
- **Base URL:** `https://api.pandadoc.com/public/v1`

#### Tags

- E-Signature
- Electronic Signatures
- Document Signing
- Compliance

#### Properties

- [Documentation](https://www.pandadoc.com/api/)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pandadoc-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pandadoc-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PandaDoc Embedded Editing API

The PandaDoc Embedded Editing API allows developers to embed PandaDoc's document editor directly within their own platform, enabling end users to prepare, customize, and finalize documents without leaving the host application. Users can upload PDFs or select templates, place signature and form fields, adjust content, and assign recipients through a drag-and-drop interface embedded via token-based sessions. Once editing is complete, documents can be sent for e-signature collection and the resulting signed PDFs and audit trails can be retrieved via API. This enables a seamless, branded document experience without requiring users to have separate PandaDoc accounts.

- **Human URL:** [https://www.pandadoc.com/api/embedded-editing/](https://www.pandadoc.com/api/embedded-editing/)
- **Base URL:** `https://api.pandadoc.com/public/v1`

#### Tags

- Embedded Editing
- Document Editor
- White Label
- Embedded

#### Properties

- [Documentation](https://www.pandadoc.com/api/embedded-editing/)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pandadoc-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pandadoc-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### PandaDoc Webhooks API

The PandaDoc Webhooks API enables developers to subscribe to real-time event notifications for document lifecycle events such as document sent, viewed, signed, approved, declined, and completed. Webhooks can be configured to trigger events both within PandaDoc and in connected external systems, enabling automated workflows across a technology stack. Each event payload includes document metadata and status information for processing downstream actions like CRM updates, storage routing, or approval notifications. Webhooks are configured through the PandaDoc dashboard and are available to accounts with API access.

- **Human URL:** [https://developers.pandadoc.com/docs/webhooks-concepts](https://developers.pandadoc.com/docs/webhooks-concepts)
- **Base URL:** `https://api.pandadoc.com/public/v1`

#### Tags

- Webhooks
- Events
- Notifications
- Integration

#### Properties

- [Documentation](https://developers.pandadoc.com/docs/webhooks-concepts)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/pandadoc-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/pandadoc-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/pandadoc-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

## Common Properties

- [GitHub Organization](https://github.com/PandaDoc)
- [LinkedIn](https://www.linkedin.com/company/pandadoc)
- [Portal](https://developers.pandadoc.com/)
- [Documentation](https://developers.pandadoc.com/docs/getting-started)
- [Website](https://www.pandadoc.com/)
- [Blog](https://www.pandadoc.com/blog/)
- [Login](https://app.pandadoc.com/login/)
- [Privacy Policy](https://www.pandadoc.com/privacy-notice/)
- [Terms of Service](https://www.pandadoc.com/terms-of-use/)
- [Support](https://support.pandadoc.com/)
- [JSON-LD](json-ld/pandadoc-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/pandadoc-document-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pandadoc-webhook-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
- [Integrations](https://www.pandadoc.com/integrations/)
- [L L Ms Txt](https://developers.pandadoc.com/llms.txt)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
