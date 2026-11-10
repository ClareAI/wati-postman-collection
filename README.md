# WATI Postman collections

This repository contains Postman collections for WATI APIs. See the [API documentation](https://docs.wati.io) for endpoint details.

## V1

Download `WATI APIs.postman_collection.json` and `WATI API Environment.postman_environment.json`, then import both files into Postman.

## V3

Download and import `WATI APIs V3.postman_collection.json`. It contains the public V3 endpoints and their request and response examples.

Before sending a request, copy both values from **WATI API Docs** and set these collection variables:

- `baseUrl`: select **API V3** in WATI API Docs, then paste its **API Endpoint** value: the regional host only, without a tenant ID or trailing slash.
- `token`: paste the complete **Access Token** value, including the `Bearer ` prefix. Do not commit a real token to this repository.

The V3 collection is generated from the V3 OpenAPI specification. Regenerate it whenever the public V3 API contract changes.

### Conversation discovery and scans

The collection includes conversation list/query and scan status/results/cancel requests from ReadMe 2.6. The query example sets `page.size` for a synchronous page. For an asynchronous query, follow the reference's query rules, then copy the returned `scan_id` into the empty `scanId` collection variable. An accepted scan is not a completed result.

List/query are included in Growth, Pro and Business. Scan status/results/cancel have Pro/Business packaging; account-specific runtime enforcement and other permissions can differ. Existing Groups examples remain in the collection with availability notes: their presence does not establish release or entitlement under the current public reference.
