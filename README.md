# Spring Batch 5.1

Spring Batch 5.1 is a lightweight, comprehensive batch framework designed to enable the development of robust batch applications vital for the daily operations of enterprise systems. Version 5.1 delivers Micrometer metrics, virtual thread support (Java 21), and enhanced chunk-oriented processing with retry, skip, and restart capabilities.

- **URL:** https://spring.io/projects/spring-batch
- **Type:** Open Source
- **Tags:** Batch Processing, Data Processing, Enterprise, ETL, Java, Job Scheduling, Spring Framework

## APIs

### Spring Batch 5.1 Core API

Core API for Spring Batch 5.1 providing batch processing capabilities including job and step configuration, chunk-oriented processing, job repository persistence, and fault tolerance.

- [Documentation](https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/)
- [API Documentation](https://docs.spring.io/spring-batch/docs/5.1.x/api/)
- [GitHub Repository](https://github.com/spring-projects/spring-batch)
- [Getting Started Guide](https://spring.io/guides/gs/batch-processing/)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.batch/spring-batch-core/5.1.0)
- [Issues](https://github.com/spring-projects/spring-batch/issues)
- [Sample Projects](https://github.com/spring-projects/spring-batch/tree/main/spring-batch-samples)
- [Release Notes](https://github.com/spring-projects/spring-batch/releases)

### Spring Batch 5.1 Actuator Monitoring

Spring Boot Actuator-based monitoring for Spring Batch 5.1 applications providing health, execution status, and Micrometer metrics.

- [Documentation](https://docs.spring.io/spring-batch/docs/5.1.x/reference/html/monitoring-and-metrics.html)

## OpenAPI Specifications

| API | File |
|-----|------|
| Spring Batch 5.1 Actuator API | [openapi/spring-batch-51-openapi.yml](openapi/spring-batch-51-openapi.yml) |

## Spectral Rules

| Ruleset | File |
|---------|------|
| Spring Batch 5.1 Rules | [rules/spring-batch-51-rules.yml](rules/spring-batch-51-rules.yml) |

## Capabilities

### Shared Definitions

| API | File |
|-----|------|
| Spring Batch 5.1 Actuator API | [capabilities/shared/spring-batch-51-actuator.yaml](capabilities/shared/spring-batch-51-actuator.yaml) |

### Workflow Capabilities

| Workflow | Description | File |
|----------|-------------|------|
| Batch Job Monitoring | Monitor Spring Batch job executions, metrics, and health | [capabilities/batch-job-monitoring.yaml](capabilities/batch-job-monitoring.yaml) |

## JSON Schemas

| Schema | File |
|--------|------|
| Job Execution | [json-schema/spring-batch-51-job-execution-schema.json](json-schema/spring-batch-51-job-execution-schema.json) |
| Job Parameters | [json-schema/spring-batch-51-job-parameters-schema.json](json-schema/spring-batch-51-job-parameters-schema.json) |

## JSON Structures

| Structure | File |
|-----------|------|
| Job Execution Domain Model | [json-structure/spring-batch-51-job-execution-structure.json](json-structure/spring-batch-51-job-execution-structure.json) |

## JSON-LD Contexts

| Context | File |
|---------|------|
| Spring Batch 5.1 | [json-ld/spring-batch-51-context.jsonld](json-ld/spring-batch-51-context.jsonld) |

## Examples

| Example | File |
|---------|------|
| Get Application Health | [examples/spring-batch-51-get-health-example.json](examples/spring-batch-51-get-health-example.json) |
| List Job Executions | [examples/spring-batch-51-list-job-executions-example.json](examples/spring-batch-51-list-job-executions-example.json) |
| Get Metric Value | [examples/spring-batch-51-get-metric-example.json](examples/spring-batch-51-get-metric-example.json) |

## Vocabulary

| Vocabulary | File |
|------------|------|
| Spring Batch 5.1 Domain Terms | [vocabulary/spring-batch-51-vocabulary.yml](vocabulary/spring-batch-51-vocabulary.yml) |

## Common Properties

- [Blog](https://spring.io/blog/category/batch)
- [Support](https://spring.io/support)
- [Forum](https://stackoverflow.com/questions/tagged/spring-batch)
- [GitHub Issues](https://github.com/spring-projects/spring-batch/issues)
- [Maven Central](https://search.maven.org/search?q=g:org.springframework.batch)

## Maintainers

- Spring Team — spring-batch@vmware.com
