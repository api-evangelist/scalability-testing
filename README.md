# Scalability Testing (scalability-testing)

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

A collection of tools, frameworks, APIs, and datasets for performing scalability and load testing of web services, APIs, and distributed systems. Scalability testing evaluates how a system performs as load increases, identifying bottlenecks, capacity limits, and performance degradation points. Key tools include Apache JMeter, k6, Gatling, Locust, and cloud-based platforms like AWS Load Testing, Azure Load Testing, and BlazeMeter.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/scalability-testing/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scalability-testing/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Testing
- Load Testing
- Performance Testing
- Scalability
- Stress Testing

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-02

## APIs

### Grafana k6 Cloud API

The Grafana k6 Cloud REST API provides programmatic access to run, manage, and retrieve results for load tests executed on the k6 cloud platform. k6 is an open-source load testing tool using JavaScript/TypeScript test scripts. The cloud platform adds distributed execution, real-time results, and team collaboration features.

- **Human URL:** [https://grafana.com/docs/grafana-cloud/testing/k6/](https://grafana.com/docs/grafana-cloud/testing/k6/)
- **Base URL:** `https://api.k6.io/v3`

#### Tags

- k6
- Load Testing
- Performance Testing

#### Properties

- [Documentation](https://grafana.com/docs/grafana-cloud/testing/k6/reference/rest-api/)
- [Postman Collection](collections/scalability-testing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalability-testing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BlazeMeter API

The BlazeMeter REST API provides access to the BlazeMeter cloud load testing platform. BlazeMeter supports JMeter, Gatling, Locust, Selenium, and custom test plans. The API enables test execution, monitoring, result retrieval, and configuration management.

- **Human URL:** [https://guide.blazemeter.com/hc/en-us/categories/200698715-BlazeMeter-API](https://guide.blazemeter.com/hc/en-us/categories/200698715-BlazeMeter-API)
- **Base URL:** `https://a.blazemeter.com/api/v4`

#### Tags

- BlazeMeter
- JMeter
- Load Testing

#### Properties

- [Documentation](https://guide.blazemeter.com/hc/en-us/categories/200698715-BlazeMeter-API)
- [Postman Collection](collections/scalability-testing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalability-testing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Azure Load Testing API

Azure Load Testing is a fully managed cloud service that enables running high-scale load tests. Based on Apache JMeter, it provides a REST API for creating, running, and analyzing load tests integrated with Azure DevOps and GitHub Actions CI/CD pipelines.

- **Human URL:** [https://learn.microsoft.com/en-us/azure/load-testing/](https://learn.microsoft.com/en-us/azure/load-testing/)
- **Base URL:** `https://management.azure.com/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.LoadTestService`

#### Tags

- Azure
- Cloud Load Testing
- JMeter
- Microsoft

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/azure/load-testing/)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/loadtestservice/resource-manager/Microsoft.LoadTestService/stable/2022-12-01/loadtestservice.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalability-testing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalability-testing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Apache JMeter

Apache JMeter is the most widely-used open-source load testing tool. It supports HTTP, HTTPS, FTP, JDBC, LDAP, SOAP, REST, and more protocols. JMeter provides a REST API in its distributed mode and integrates with BlazeMeter, Azure Load Testing, and other cloud platforms for scaled execution.

- **Human URL:** [https://jmeter.apache.org/](https://jmeter.apache.org/)

#### Tags

- Apache
- JMeter
- Load Testing
- Open Source

#### Properties

- [Documentation](https://jmeter.apache.org/usermanual/index.html)
- [Git Hub](https://github.com/apache/jmeter)
- [Postman Collection](collections/scalability-testing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalability-testing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Locust Load Testing

Locust is a scalable, distributed open-source load testing framework written in Python. Test scenarios are defined in pure Python code. Locust exposes a REST API and web UI for controlling test execution, viewing real-time metrics, and integrating with CI/CD pipelines.

- **Human URL:** [https://locust.io/](https://locust.io/)
- **Base URL:** `http://localhost:8089`

#### Tags

- Load Testing
- Locust
- Open Source
- Python

#### Properties

- [Documentation](https://docs.locust.io/en/stable/)
- [Git Hub](https://github.com/locustio/locust)
- [Postman Collection](collections/scalability-testing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalability-testing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Gatling Load Testing

Gatling is an open-source load testing framework built on Akka and Netty, providing high performance with a Scala/Java/Kotlin DSL for defining test scenarios. The Gatling Enterprise cloud platform provides distributed execution and advanced analytics APIs.

- **Human URL:** [https://gatling.io/](https://gatling.io/)

#### Tags

- Gatling
- Java
- Load Testing
- Open Source
- Scala

#### Properties

- [Documentation](https://docs.gatling.io/)
- [Git Hub](https://github.com/gatling/gatling)
- [Postman Collection](collections/scalability-testing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalability-testing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://k6.io/)
- [Git Hub](https://github.com/grafana/k6)
- [Git Hub](https://github.com/apache/jmeter)
- [Git Hub](https://github.com/locustio/locust)
- [Git Hub](https://github.com/gatling/gatling)
- [Documentation](https://grafana.com/docs/grafana-cloud/testing/k6/)
- [Vocabulary](vocabulary/scalability-testing-vocabulary.yml)
- [JSON-LD](json-ld/scalability-testing-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
