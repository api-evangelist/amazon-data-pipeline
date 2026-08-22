# Amazon Data Pipeline (amazon-data-pipeline)

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

AWS Data Pipeline is a web service that helps you reliably process and move data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals. With AWS Data Pipeline, you can regularly access your data where it is stored, transform and process it at scale, and efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS, Amazon DynamoDB, and Amazon EMR. It supports data-driven workflows with retry, failure handling, and scheduling capabilities.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/amazon-data-pipeline/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-data-pipeline/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AWS
- Data Processing
- ETL
- Workflows
- Data Pipeline
- Automation

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### AWS Data Pipeline API

The AWS Data Pipeline API provides a web service for processing and moving data between different AWS compute and storage services as well as on-premises data sources at specified intervals. The API allows you to create pipeline definitions, schedule data transformations, configure retry and failure handling logic, and monitor pipeline execution across Amazon S3, Amazon RDS, Amazon DynamoDB, and Amazon EMR.

- **Human URL:** [https://aws.amazon.com/datapipeline/](https://aws.amazon.com/datapipeline/)
- **Base URL:** `https://datapipeline.amazonaws.com`

#### Tags

- AWS
- Data Processing
- ETL
- Workflows

#### Properties

- [Documentation](https://docs.aws.amazon.com/datapipeline/)
- [OpenAPI](openapi/amazon-data-pipeline-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/amazon-data-pipeline.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/amazon-data-pipeline.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Pricing](https://aws.amazon.com/datapipeline/pricing/)
- [Getting Started](https://aws.amazon.com/datapipeline/getting-started/)
- [F A Q](https://aws.amazon.com/datapipeline/faqs/)
- [API Reference](https://docs.aws.amazon.com/datapipeline/latest/APIReference/)
- [JSON Schema](json-schema/pipeline-object-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/pipeline-description-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/amazon-data-pipeline-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://aws.amazon.com/datapipeline/)
- [Developer Portal](https://aws.amazon.com/datapipeline/)
- [Documentation](https://docs.aws.amazon.com/datapipeline/)
- [Terms of Service](https://aws.amazon.com/service-terms/)
- [Privacy Policy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [GitHub Organization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/datapipeline/)
- [Sign Up](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [Status Page](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [Spectral Rules](rules/amazon-data-pipeline-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-data-pipeline-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://aws.amazon.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
