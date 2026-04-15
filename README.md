# Performance Ai

> By [MEOK AI Labs](https://meok.ai) — MEOK AI Labs MCP Server

Performance AI MCP Server

## Installation

```bash
pip install performance-ai-mcp
```

## Usage

```bash
# Run standalone
python server.py

# Or via MCP
mcp install performance-ai-mcp
```

## Tools

### `analyze_waterfall_data`
Analyze a resource loading waterfall for performance bottlenecks.

**Parameters:**
- `resources` (str)

### `suggest_optimizations`
Suggest performance optimizations based on page characteristics.

**Parameters:**
- `page_data` (str)

### `calculate_core_web_vitals`
Calculate and rate Core Web Vitals scores.

**Parameters:**
- `lcp_ms` (float)
- `fid_ms` (float)
- `inp_ms` (float)

### `image_optimization_hints`
Analyze images and suggest optimization strategies.

**Parameters:**
- `images` (str)


## Authentication

Free tier: 15 calls/day. Upgrade at [meok.ai/pricing](https://meok.ai/pricing) for unlimited access.

## Links

- **Website**: [meok.ai](https://meok.ai)
- **GitHub**: [CSOAI-ORG/performance-ai-mcp](https://github.com/CSOAI-ORG/performance-ai-mcp)
- **PyPI**: [pypi.org/project/performance-ai-mcp](https://pypi.org/project/performance-ai-mcp/)

## License

MIT — MEOK AI Labs
