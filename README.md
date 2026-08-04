# JupyterHub (jupyterhub)

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

JupyterHub is a multi-user server for Jupyter notebooks. It manages authentication, spawns and proxies multiple instances of the single-user Jupyter notebook server, and exposes a REST API for managing users, groups, services, tokens, and the proxy.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/jupyterhub/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Authentication
- Data Science
- Education
- Hub
- Multi-User
- Notebooks
- OAuth2
- Python

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### JupyterHub REST API

REST API for managing users, groups, single-user servers, services, tokens, the proxy, and OAuth2 authorization in a JupyterHub deployment. Authenticated via API tokens or OAuth2.

- **Human URL:** [https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html](https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html)
- **Base URL:** `http://localhost:8000/hub/api`

#### Tags

- Authentication
- Groups
- OAuth2
- REST API
- Servers
- Tokens
- Users

#### Properties

- [Documentation](https://jupyterhub.readthedocs.io/en/stable/reference/rest-api.html)
- [Repository](https://github.com/jupyterhub/jupyterhub)
- [Authentication](https://jupyterhub.readthedocs.io/en/stable/rbac/index.html)
- [OpenAPI](openapi/jupyterhub-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/jupyterhub-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/jupyterhub-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/jupyterhub-user.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jupyterhub-server.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/jupyterhub-group.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/jupyterhub-context.jsonld)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/project-jupyter)
- [Website](https://jupyter.org/hub)
- [Documentation](https://jupyterhub.readthedocs.io/)
- [Getting Started](https://jupyterhub.readthedocs.io/en/stable/tutorial/quickstart.html)
- [Installation](https://jupyterhub.readthedocs.io/en/stable/installation-guide.html)
- [GitHub Organization](https://github.com/jupyterhub)
- [Repository](https://github.com/jupyterhub/jupyterhub)
- [Community](https://discourse.jupyter.org/c/jupyterhub)
- [License](https://github.com/jupyterhub/jupyterhub/blob/main/COPYING.md)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
