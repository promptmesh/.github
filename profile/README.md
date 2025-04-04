# Prompt Mesh

Promptmesh is a collection of open-source tools for working with LLMs using the Model Context Protocol (MCP).

We build SDKs, APIs, and examples to make it easier to:

- Connect to MCP servers
- Use tools and prompts dynamically
- Read resources in a structured way

## Projects

- **[easymcp](https://github.com/promptmesh/easymcp)** – Python SDK for working with MCP servers
- **[SemanticTool](https://github.com/promptmesh/semantictool)** – REST/GQL API built on top of `easymcp`, with support for semantic tool search and remote function calling.
- **[RelayMCP](https://github.com/promptmesh/relaymcp)** - OpenAPI to Streaming HTTP MCP gateway service.

## Goals

- Keep things modular and composable
- Support local and remote tool execution
- Provide clean, typed interfaces for orchestration
- Build on top of the Model Context Protocol (MCP)

## License

MIT license unless noted otherwise in individual repositories.
