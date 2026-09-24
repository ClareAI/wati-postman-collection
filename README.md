# WATI Postman collections

This repository contains Postman collections for WATI APIs. See the [API documentation](https://docs.wati.io) for endpoint details.

## V1

Download `WATI APIs.postman_collection.json` and `WATI API Environment.postman_environment.json`, then import both files into Postman.

## V3

Download and import `WATI APIs V3.postman_collection.json`. It contains the public V3 endpoints and their request and response examples.

Before sending a request, copy both values from **WATI API Docs** and set these collection variables:

- `baseUrl`: paste the **API Endpoint** value. Do not add a trailing slash.
- `token`: paste the complete **Access Token** value, including the `Bearer ` prefix. Do not commit a real token to this repository.

The V3 collection is generated from the V3 OpenAPI specification. Regenerate it whenever the public V3 API contract changes.
