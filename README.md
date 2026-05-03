# Scalability Testing

A collection of tools, frameworks, APIs, and datasets for performing scalability and load testing of web services, APIs, and distributed systems. Scalability testing evaluates how a system performs as load increases, identifying bottlenecks, capacity limits, and performance degradation points. Key tools include Apache JMeter, k6, Gatling, Locust, and cloud platforms like Azure Load Testing and BlazeMeter.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/scalability-testing/refs/heads/main/apis.yml)

- **k6 Documentation:** https://grafana.com/docs/grafana-cloud/testing/k6/
- **JMeter Documentation:** https://jmeter.apache.org/usermanual/
- **Locust Documentation:** https://docs.locust.io/

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Scalability, Load Testing, Performance Testing, Stress Testing, API Testing, Monitoring, Analytics

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-02

## APIs and Tools

### Grafana k6 Cloud API

The Grafana k6 Cloud REST API provides programmatic access to run and manage load tests. k6 is an open-source load testing tool using JavaScript/TypeScript test scripts.

**Human URL:** https://grafana.com/docs/grafana-cloud/testing/k6/

**Tags:** k6, Load Testing, Performance Testing

**Properties**

- [Documentation](https://grafana.com/docs/grafana-cloud/testing/k6/reference/rest-api/)

### BlazeMeter API

The BlazeMeter REST API enables programmatic access to the BlazeMeter cloud load testing platform supporting JMeter, Gatling, Locust, and Selenium.

**Human URL:** https://guide.blazemeter.com/hc/en-us/categories/200698715-BlazeMeter-API

**Tags:** BlazeMeter, JMeter, Load Testing

### Azure Load Testing API

Azure's fully managed cloud load testing service based on Apache JMeter, integrated with Azure DevOps and GitHub Actions.

**Human URL:** https://learn.microsoft.com/en-us/azure/load-testing/

**Tags:** Azure, Cloud Load Testing, JMeter, Microsoft

**Properties**

- [Documentation](https://learn.microsoft.com/en-us/azure/load-testing/)
- [OpenAPI](https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/loadtestservice/resource-manager/Microsoft.LoadTestService/stable/2022-12-01/loadtestservice.json)

### Apache JMeter

The most widely used open-source load testing tool supporting HTTP, JDBC, JMS, LDAP, SOAP, and REST protocols.

**Human URL:** https://jmeter.apache.org/

**Tags:** JMeter, Load Testing, Open Source, Apache

**Properties**

- [Documentation](https://jmeter.apache.org/usermanual/index.html)
- [GitHub](https://github.com/apache/jmeter)

### Locust

A scalable distributed load testing framework written in Python with a REST API for CI/CD integration.

**Human URL:** https://locust.io/

**Tags:** Load Testing, Locust, Open Source, Python

**Properties**

- [Documentation](https://docs.locust.io/en/stable/)
- [GitHub](https://github.com/locustio/locust)

### Gatling

A high-performance open-source load testing framework using a Scala/Java/Kotlin DSL built on Akka and Netty.

**Human URL:** https://gatling.io/

**Tags:** Gatling, Load Testing, Open Source, Java, Scala

**Properties**

- [Documentation](https://docs.gatling.io/)
- [GitHub](https://github.com/gatling/gatling)

## JSON Schema

- [json-schema/scalability-testing-test-result-schema.json](json-schema/scalability-testing-test-result-schema.json) — Schema for aggregated load test results including configuration, performance metrics (p50, p90, p95, p99), error rates, and SLA validation

## JSON Structure

- [json-structure/scalability-testing-test-result-structure.json](json-structure/scalability-testing-test-result-structure.json) — Field-level documentation for the LoadTestResult entity structure

## JSON-LD

- [json-ld/scalability-testing-context.jsonld](json-ld/scalability-testing-context.jsonld) — Linked data context mapping scalability testing concepts (LoadTest, VirtualUser, Metric, Percentile) to schema.org vocabulary

## Examples

- [examples/scalability-testing-k6-test-result-example.json](examples/scalability-testing-k6-test-result-example.json) — Example k6 Cloud API test result for a 30-minute, 1000 VU load test with full metrics

## Vocabulary

- [vocabulary/scalability-testing-vocabulary.yml](vocabulary/scalability-testing-vocabulary.yml) — Comprehensive vocabulary covering test types (Load, Stress, Spike, Soak), performance metrics (throughput, Apdex, percentiles, error rate), tools (k6, JMeter, Gatling, Locust), and testing methodologies

## Common Properties

- [k6 Open Source](https://github.com/grafana/k6)
- [Apache JMeter](https://github.com/apache/jmeter)
- [Locust](https://github.com/locustio/locust)
- [Gatling](https://github.com/gatling/gatling)
- [k6 Documentation](https://grafana.com/docs/grafana-cloud/testing/k6/)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
