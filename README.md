# MCP_Claude_Test

## Overview
The Model Context Protocol allows applications to provide context for LLMs in a standardized way, separating the concerns of providing context from the actual LLM interaction. This Python SDK implements the full MCP specification, making it easy to:

- Build MCP clients that can connect to any MCP server  
- Create MCP servers that expose resources, prompts and tools  
- Use standard transports like stdio, SSE, and Streamable HTTP  
- Handle all MCP protocol messages and lifecycle events

---

## Installation

### Adding MCP to your Python project

We recommend using [uv](https://github.com/astral-sh/uv) to manage your Python projects.

If you haven't created a uv-managed project yet, create one:

```bash
uv init mcp-server-demo
cd mcp-server-demo
```

Then add MCP to your project dependencies:

```bash
uv add "mcp[cli]"
```

Alternatively, for projects using pip for dependencies:

```bash
pip install "mcp[cli]"
```

Running the standalone MCP development tools
To run the mcp command with uv:

```bash
uv run mcp
```
You can install this server in Claude Desktop and interact with it right away by running:

```bash
uv run mcp install main.py
```

