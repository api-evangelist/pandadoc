# PandaDoc GraphQL Schema

## Overview

This GraphQL schema represents the PandaDoc document automation and e-signature platform. PandaDoc provides REST APIs at `https://api.pandadoc.com/public/v1` for creating, sending, tracking, and e-signing documents programmatically. This schema models the core domain types from that platform in GraphQL SDL form.

## Source

- **Provider**: PandaDoc
- **REST API Reference**: https://developers.pandadoc.com/reference
- **Developer Portal**: https://developers.pandadoc.com/
- **Base URL**: https://api.pandadoc.com/public/v1
- **Schema File**: pandadoc-schema.graphql

## Domain Coverage

The schema covers the following PandaDoc platform domains:

### Documents
Core document lifecycle types including `Document`, `DocumentDetails`, `DocumentStatus`, `DocumentTheme`, `DocumentSession`, and `DocumentToken`. Documents are the primary resource in PandaDoc and progress through statuses from draft through sent, viewed, signed, approved, and completed.

### Templates
`Template`, `TemplateDetails`, `TemplateFields`, and `TemplateContent` types model reusable document blueprints that can be instantiated with dynamic data to generate documents at scale.

### Content Library
`ContentLibraryItem` and `ContentLibraryDetails` cover reusable content blocks that can be pulled into documents and templates.

### Recipients and Signers
`Recipient`, `RecipientDetails`, `RecipientRole`, and `RecipientAccessCode` model the parties involved in document workflows. `Signer`, `SignerDetails`, and `SignatureRequest` cover e-signature collection specifics.

### Fields
`Field`, `FieldDetails`, `FieldType`, `FieldValue`, `TableField`, `TableRow`, and `TableCell` represent the fillable and signable fields placed within documents.

### Pricing
`Price`, `PriceDetails`, `PriceCatalog`, `PriceVariant`, and `PriceDiscount` model the pricing table capabilities used in sales proposals and quotes.

### Products
`Product` and `ProductDetails` cover the product catalog that feeds into pricing tables.

### Forms
`Form`, `FormDetails`, `FormField`, and `FormResponse` model PandaDoc's form collection capabilities for standalone data gathering.

### Folders
`Folder`, `FolderDetails`, and `FolderItem` model the organizational hierarchy for documents and templates.

### Members and Workspaces
`Member`, `MemberDetails`, `MemberRole`, `Workspace`, and `WorkspaceDetails` model user and team organization within PandaDoc accounts.

### Webhooks
`WebhookEvent`, `Webhook`, and `WebhookSubscription` cover the event-driven notification system for document lifecycle events.

### Authentication
`APIKey`, `OauthToken`, and `OauthApp` model authentication credential types supported by the PandaDoc platform.

### Metadata and Variables
`Metadata`, `Variable`, and `TokenPayload` cover document-level metadata, dynamic variable substitution, and session token structures used in embedded editing flows.

## Authentication

PandaDoc supports two authentication methods:

1. **API Key** (Bearer token) — passed as `Authorization: API-Key <key>` header
2. **OAuth 2.0** — passed as `Authorization: Bearer <token>` header

An active Enterprise plan is required for production API access. A free sandbox environment is available for testing.

## Rate Limits

Default rate limit is 100 requests per minute per workspace.

## Notes

PandaDoc does not currently offer a native GraphQL endpoint. This schema is a conceptual representation of the PandaDoc REST API domain model expressed in GraphQL SDL for integration reference, schema mapping, and tooling purposes.
