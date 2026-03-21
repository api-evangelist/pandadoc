# PandaDoc (pandadoc)
PandaDoc is a document automation platform that enables businesses to create, send, track, and e-sign documents programmatically. Their developer platform provides REST APIs and embedded tools for integrating document generation, e-signature collection, and workflow automation directly into third-party applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/pandadoc/refs/heads/main/apis.yml)

## Scope
- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Document Automation, E-Signature, Document Management, Document Generation, Webhooks

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-03-21

## APIs

### PandaDoc REST API
The PandaDoc REST API provides programmatic access to PandaDoc's document automation platform, enabling developers to create, send, track, and manage documents within their own applications. The API supports the full document lifecycle including generating documents from templates with dynamic data, collecting e-signatures, managing recipients, and tracking document status through webhooks. Authentication is handled via API keys, and a free sandbox environment is available for testing integrations before moving to production. An active Enterprise plan is required to access the production API.

**Human URL:** [https://developers.pandadoc.com/reference/about](https://developers.pandadoc.com/reference/about)

#### Tags:

 - Document Automation, E-Signature, Document Management, REST

#### Properties

- [Documentation](https://developers.pandadoc.com/reference/about)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml)

### PandaDoc Document Generation API
The PandaDoc Document Generation API allows developers to programmatically create documents from templates by injecting dynamic data pulled from CRM systems, databases, or other external sources. It supports branded document creation with content placeholders, conditional sections, pricing tables, and custom fields that are populated at runtime. Documents can be generated from existing PandaDoc templates or uploaded PDFs, enabling consistent and automated document production at scale. The API is commonly used in sales, legal, and HR workflows to eliminate manual document preparation.

**Human URL:** [https://developers.pandadoc.com/docs/getting-started](https://developers.pandadoc.com/docs/getting-started)

#### Tags:

 - Document Generation, Templates, Document Automation, CRM Integration

#### Properties

- [Documentation](https://developers.pandadoc.com/docs/getting-started)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml)

### PandaDoc E-Signature API
The PandaDoc E-Signature API enables developers to embed legally binding e-signature workflows directly within their applications using a white-label signing experience. It supports sending signature requests via email or SMS, configuring multiple recipients with defined roles and signing order, and collecting signatures without signers needing a PandaDoc account. The API provides real-time status tracking and generates audit trails and signed PDF copies upon completion. It is designed for use cases in contract management, sales, finance, and any workflow requiring legally compliant electronic signatures.

**Human URL:** [https://www.pandadoc.com/api/](https://www.pandadoc.com/api/)

#### Tags:

 - E-Signature, Electronic Signatures, Document Signing, Compliance

#### Properties

- [Documentation](https://www.pandadoc.com/api/)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml)

### PandaDoc Embedded Editing API
The PandaDoc Embedded Editing API allows developers to embed PandaDoc's document editor directly within their own platform, enabling end users to prepare, customize, and finalize documents without leaving the host application. Users can upload PDFs or select templates, place signature and form fields, adjust content, and assign recipients through a drag-and-drop interface embedded via token-based sessions. Once editing is complete, documents can be sent for e-signature collection and the resulting signed PDFs and audit trails can be retrieved via API. This enables a seamless, branded document experience without requiring users to have separate PandaDoc accounts.

**Human URL:** [https://www.pandadoc.com/api/embedded-editing/](https://www.pandadoc.com/api/embedded-editing/)

#### Tags:

 - Embedded Editing, Document Editor, White Label, Embedded

#### Properties

- [Documentation](https://www.pandadoc.com/api/embedded-editing/)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml)

### PandaDoc Webhooks API
The PandaDoc Webhooks API enables developers to subscribe to real-time event notifications for document lifecycle events such as document sent, viewed, signed, approved, declined, and completed. Webhooks can be configured to trigger events both within PandaDoc and in connected external systems, enabling automated workflows across a technology stack. Each event payload includes document metadata and status information for processing downstream actions like CRM updates, storage routing, or approval notifications. Webhooks are configured through the PandaDoc dashboard and are available to accounts with API access.

**Human URL:** [https://developers.pandadoc.com/docs/webhooks-concepts](https://developers.pandadoc.com/docs/webhooks-concepts)

#### Tags:

 - Webhooks, Events, Notifications, Integration

#### Properties

- [Documentation](https://developers.pandadoc.com/docs/webhooks-concepts)
- [OpenAPI](openapi/pandadoc-rest-api-openapi.yml)
- [AsyncAPI](asyncapi/pandadoc-webhooks-asyncapi.yml)

## Common Properties

- [Portal](https://developers.pandadoc.com/)
- [Documentation](https://developers.pandadoc.com/docs/getting-started)
- [Website](https://www.pandadoc.com/)
- [Blog](https://www.pandadoc.com/blog/)
- [Login](https://app.pandadoc.com/login/)
- [PrivacyPolicy](https://www.pandadoc.com/privacy-notice/)
- [TermsOfService](https://www.pandadoc.com/terms-of-use/)
- [Support](https://support.pandadoc.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
