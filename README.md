<div align="center">

# Performance Ai MCP

**Performance AI MCP Server**

[![PyPI](https://img.shields.io/pypi/v/meok-performance-ai-mcp)](https://pypi.org/project/meok-performance-ai-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-MCP_Server-purple)](https://meok.ai)

</div>

## Overview

Performance AI MCP Server
Web performance analysis and optimization tools powered by MEOK AI Labs.

## Tools

| Tool | Description |
|------|-------------|
| `analyze_waterfall_data` | Analyze a resource loading waterfall for performance bottlenecks. |
| `suggest_optimizations` | Suggest performance optimizations based on page characteristics. |
| `calculate_core_web_vitals` | Calculate and rate Core Web Vitals scores. |
| `image_optimization_hints` | Analyze images and suggest optimization strategies. |

## Installation

```bash
pip install meok-performance-ai-mcp
```

## Usage with Claude Desktop

Add to your Claude Desktop MCP config (`claude_desktop_config.json`):

```json
{
  "mcpServers": {
    "performance-ai": {
      "command": "python",
      "args": ["-m", "meok_performance_ai_mcp.server"]
    }
  }
}
```

## Usage with FastMCP

```python
from mcp.server.fastmcp import FastMCP

# This server exposes 4 tool(s) via MCP
# See server.py for full implementation
```

## License

MIT © [MEOK AI Labs](https://meok.ai)
