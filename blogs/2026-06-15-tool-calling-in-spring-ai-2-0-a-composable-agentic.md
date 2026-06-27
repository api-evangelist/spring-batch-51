---
title: "Tool Calling in Spring AI 2.0: A Composable, Agentic Architecture"
url: "https://spring.io/blog/2026/06/15/spring-ai-composable-tool-calling"
date: "2026-06-15"
author: "tzolov"
feed_url: "https://spring.io/blog.atom"
---
A technical guide to Spring AI 2.0's redesigned tool-calling system, which elevates tool execution to first-class, composable advisor components, with the @Tool annotation handling automatic JSON schema generation. ToolCallingAdvisor implements a recursive loop until the model responds without tool invocations, while ToolSearchToolCallingAdvisor enables progressive tool disclosure that scales to hundreds of tools with 34-64% token reduction. It also covers memory integration, MCP tool integration, and migration guidance for breaking changes from Spring AI 1.x such as FunctionCallback being renamed to ToolCallback.
