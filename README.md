# Tableau Desktop (tableau-desktop)

APIs and integration points for Tableau Desktop, a data visualization and business intelligence platform from Salesforce. Tableau provides REST APIs, embedding APIs, extension APIs, and SDK tools for building custom visualizations, automating server operations, and extending analytics capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tableau-desktop/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tableau-desktop/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Analytics
- Business Intelligence
- Data Visualization
- Desktop Application

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Tableau REST API

Manage and interact with Tableau Server and Tableau Cloud resources programmatically including workbooks, data sources, users, and permissions.

- **Human URL:** [https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm)
- **Base URL:** `https://tableau-server/api/3.22`

#### Tags

- Cloud
- Publishing
- REST
- Server
- Workbooks

#### Properties

- [Documentation](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm)
- [API Reference](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref.htm)
- [Authentication](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_concepts_auth.htm)
- [OpenAPI](openapi/tableau-desktop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tableau-desktop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-desktop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Extensions API

Build dashboard extensions that enable users to interact with data from other applications directly in Tableau dashboards.

- **Human URL:** [https://tableau.github.io/extensions-api/](https://tableau.github.io/extensions-api/)
- **Base URL:** `https://tableau.github.io/extensions-api/`

#### Tags

- Dashboard
- Extensions
- JavaScript
- Web Components

#### Properties

- [Documentation](https://tableau.github.io/extensions-api/docs/trex_overview.html)
- [API Reference](https://tableau.github.io/extensions-api/docs/index.html)
- [GitHub Repository](https://github.com/tableau/extensions-api)
- [Getting Started](https://tableau.github.io/extensions-api/docs/trex_getstarted.html)
- [Postman Collection](collections/tableau-desktop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-desktop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Hyper API

Create, read, update, and delete data in .hyper files for use in Tableau Desktop and Server with high-performance data extract capabilities.

- **Human URL:** [https://tableau.github.io/hyper-db/docs/](https://tableau.github.io/hyper-db/docs/)
- **Base URL:** `https://tableau.github.io/hyper-db/`

#### Tags

- Data Extract
- Database
- ETL
- Hyper
- SQL

#### Properties

- [Documentation](https://tableau.github.io/hyper-db/docs/)
- [API Reference](https://tableau.github.io/hyper-db/lang_docs/py/tableauhyperapi.html)
- [GitHub Repository](https://github.com/tableau/hyper-api-samples)
- [Release Notes](https://tableau.github.io/hyper-db/docs/releases/)
- [Postman Collection](collections/tableau-desktop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-desktop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Embedding API

Embed Tableau visualizations into web applications using modern web components with v3 of the Embedding API.

- **Human URL:** [https://help.tableau.com/current/api/embedding_api/en-us/index.html](https://help.tableau.com/current/api/embedding_api/en-us/index.html)
- **Base URL:** `https://help.tableau.com/current/api/embedding_api/`

#### Tags

- Embedding
- Integration
- JavaScript
- Web Components

#### Properties

- [Documentation](https://help.tableau.com/current/api/embedding_api/en-us/index.html)
- [GitHub Repository](https://github.com/tableau/embedding-api-v3-samples)
- [Authentication](https://help.tableau.com/current/api/embedding_api/en-us/docs/embedding_api_auth.html)
- [Postman Collection](collections/tableau-desktop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-desktop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Metadata API

Discover and query metadata about Tableau content using GraphQL, including workbooks, data sources, flows, and lineage information.

- **Human URL:** [https://help.tableau.com/current/api/metadata_api/en-us/index.html](https://help.tableau.com/current/api/metadata_api/en-us/index.html)
- **Base URL:** `https://help.tableau.com/current/api/metadata_api/`

#### Tags

- Data Governance
- GraphQL
- Lineage
- Metadata

#### Properties

- [Documentation](https://help.tableau.com/current/api/metadata_api/en-us/index.html)
- [Getting Started](https://help.tableau.com/current/api/metadata_api/en-us/docs/meta_api_start.html)
- [Postman Collection](collections/tableau-desktop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-desktop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Server Client (Python)

Python library that provides a convenient wrapper for the Tableau Server REST API for automation and integration workflows.

- **Human URL:** [https://tableau.github.io/server-client-python/](https://tableau.github.io/server-client-python/)
- **Base URL:** `https://tableau.github.io/server-client-python/`

#### Tags

- Automation
- Python
- REST API
- Server

#### Properties

- [Documentation](https://tableau.github.io/server-client-python/docs/)
- [API Reference](https://tableau.github.io/server-client-python/docs/api-ref)
- [GitHub Repository](https://github.com/tableau/server-client-python)
- [Postman Collection](collections/tableau-desktop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-desktop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://www.tableau.com/developer)
- [Documentation](https://www.tableau.com/developer/tools)
- [Getting Started](https://www.tableau.com/developer/getting-started)
- [Blog](https://www.tableau.com/about/blog/developers)
- [Support](https://www.tableau.com/support)
- [Terms of Service](https://www.tableau.com/tos)
- [Privacy Policy](https://www.tableau.com/privacy)
- [Training](https://trailhead.salesforce.com/content/learn/modules/tableau-developer-platform/get-started-with-the-tableau-developer-platform)
- [GitHub Organization](https://github.com/tableau)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
