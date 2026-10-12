# GetQueryly MCP Server

**AI data analysis for your AI assistant.** Connect Claude Desktop, Cursor, or any MCP client to GetQueryly and analyze spreadsheets in plain English — CSV, Excel, JSON, PDF, SPSS, images. The AI writes and runs real Python against your file, proves every number, and returns charts.

Hosted server — no install, no setup. Just point your client at the URL and add your API key.

## Connect in 30 seconds

**Claude Desktop / Cursor / any MCP client** (streamable HTTP):

```json
{
  "mcpServers": {
    "getqueryly": {
      "url": "https://getqueryly.com/mcp/mcp",
      "headers": { "X-API-Key": "YOUR_GETQUERYLY_API_KEY" }
    }
  }
}
```

Get a free API key (10 free Makes/day): **https://getqueryly.com/keys**

## What your assistant can do

| Tool | What it does |
|---|---|
| `analyze_file` | **One call deep analysis**: upload → quality score → insights → chart → plain-English answer |
| `ds_upload` | Upload CSV/Excel/JSON/PDF/SPSS/image, get a session id |
| `ds_query` | Ask anything about your data — AI writes and runs real code |
| `ds_health_check` | Honest 0-100 data quality score with exact issues |
| `ds_insights` | Auto-surface patterns, anomalies, correlations |
| `ds_swarm` | Multiple AI analyst personas analyze independently, then reach consensus |
| `chart` | Bar, line, scatter, heatmap, box plot, treemap — any chart |
| `smart_test` | AI picks the right statistical test and runs it |
| `ds_report` | Generate a shareable PDF report |
| `ds_dashboard` | Auto-build an executive dashboard (KPIs, charts) |
| `ds_graph` | Knowledge-graph (GraphRAG) over your dataset |
| `kaggle_search` / `kaggle_load` / `kaggle_analyze` | Search 200K+ Kaggle datasets and analyze them in place |
| `generate_diagram` / `create_infographic` / `create_comparison` | Visual explainers from descriptions |
| `get_usage` / `get_costs` | Free balance + pricing lookups |

## Pricing

Free: **10 Makes/day** with an API key (no card). Paid packs (GHS): Starter 50 / Growth 200 / Pro 600 — never expire. Full table: https://getqueryly.com/pricing

## Links

- Web app: https://getqueryly.com
- API docs: https://getqueryly.com/api-docs
- llms.txt (for AI crawlers): https://getqueryly.com/llms.txt
- Keys: https://getqueryly.com/keys

## Notes

- Transport: streamable HTTP (MCP 2025-03-26)
- Your files are processed in-memory; sessions auto-expire
- Every analysis is metered in "Makes" so costs are predictable

MIT licensed. Built by [GetQueryly](https://getqueryly.com).

## Official MCP Registry

Listed in the official registry: [`io.github.thesinbin12-jpg/getqueryly`](https://registry.modelcontextprotocol.io/v0/servers/io.github.thesinbin12-jpg%2Fgetqueryly/versions/latest)
