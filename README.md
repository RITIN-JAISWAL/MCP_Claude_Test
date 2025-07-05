# MCP_Claude_Test

## Overview
The Model Context Protocol allows applications to provide context for LLMs in a standardized way, separating the concerns of providing context from the actual LLM interaction. This Python SDK implements the full MCP specification, making it easy to:

Build MCP clients that can connect to any MCP server
Create MCP servers that expose resources, prompts and tools
Use standard transports like stdio, SSE, and Streamable HTTP
Handle all MCP protocol messages and lifecycle events

## Installation
Adding MCP to your python project
We recommend using uv to manage your Python projects.

If you haven't created a uv-managed project yet, create one:
uv init mcp-server-demo
cd mcp-server-demo
