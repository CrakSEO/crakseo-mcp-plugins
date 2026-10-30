# Keyword Research: Search Volume, Keyword Difficulty & CPC by CrakSEO

Keyword research for SEO: monthly search volume, keyword difficulty, CPC, keyword ideas, related keywords and competitor keyword gaps for any topic and country.

Keyword research for SEO and content planning. Get monthly search volume, keyword difficulty and CPC for any keyword by country, and generate keyword ideas and related keywords for any topic or seed keyword. Find competitor keyword gaps: the keywords a competitor ranks for that you don't. Use it to choose target keywords, size topics, plan content clusters, and decide whether a keyword is worth a page. Live keyword data that web search can't provide.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/keyword-research` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Free to connect, and `get_api_credit_balance` is free. Data calls use prepaid API credits; each tool states its cost. Pricing: https://docs.crakseo.com/pricing/api-credits |
| Docs | https://docs.crakseo.com/mcp-servers/keyword-research |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `get_keyword_search_volume` | Keyword search volume, CPC and difficulty | API credits |
| `find_keyword_ideas` | Find keyword ideas | API credits |
| `get_keyword_difficulty` | Keyword difficulty | API credits |
| `find_competitor_keywords` | Find competitor keywords (keyword gap) | API credits |
| `get_api_credit_balance` | API credit balance | Free |

## Questions it answers

- How do I check keyword search volume and CPC?
- How do I check how difficult a keyword is to rank for?
- How do I find keyword ideas and competitor keyword gaps?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-keyword-research": {
      "url": "https://crakseo.com/mcp/keyword-research"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/keyword-research

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
