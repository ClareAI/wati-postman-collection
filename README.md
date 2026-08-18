# WATI Postman collections

This repository contains Postman collections for WATI APIs. See the [API documentation](https://docs.wati.io) for endpoint details.

## V1

Download `WATI APIs.postman_collection.json` and `WATI API Environment.postman_environment.json`, then import both files into Postman.

## V3

Download and import `WATI APIs V3.postman_collection.json`. It contains the public V3 endpoints and their request and response examples.

Before sending a request, set these collection variables:

- `baseUrl`: your WATI API host. The default is `https://live-mt-server.wati.io`.
- `token`: your WATI API token. Do not commit a real token to this repository.

The V3 collection is generated from the V3 OpenAPI specification. Regenerate it whenever the public V3 API contract changes.
