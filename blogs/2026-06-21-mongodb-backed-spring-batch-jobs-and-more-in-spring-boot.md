---
title: "MongoDB-backed Spring Batch jobs and more in Spring Boot 4.1"
url: "https://spring.io/blog/2026/06/21/spring-boot-41-and-spring-batch"
date: "2026-06-21"
author: "joshlong"
feed_url: "https://spring.io/blog.atom"
---
Spring Boot 4.1 introduces MongoDB support for Spring Batch's JobRepository, eliminating the requirement to maintain a separate SQL database for batch metadata. The post walks through a complete ETL example that stores batch metadata in MongoDB while reading from CSV and writing to PostgreSQL, covering automatic schema initialization, tasklet-based cleanup steps, and chunked reader-processor-writer patterns. It also covers GraalVM native image compilation with runtime hints and lazy datasource connection retrieval, with the code example available on GitHub.
