# Backlink Checker: Backlinks, Referring Domains & Anchor Text by CrakSEO

Backlink checker for SEO: backlinks, referring domains and anchor text for any website or competitor. Link analysis for backlink audits and link building.

Check the backlink profile of any website for SEO. The backlink checker returns backlinks, referring domains and anchor text for your site or a competitor's, so you can see who links to a domain and how its anchor text is distributed. Use it for link analysis, backlink audits, competitor backlink research and planning link building. Analysis only: it doesn't build or index links.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/backlinks` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Free to connect, and `get_api_credit_balance` is free. Data calls use prepaid API credits; each tool states its cost. Pricing: https://docs.crakseo.com/pricing/api-credits |
| Docs | https://docs.crakseo.com/mcp-servers/backlinks |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `check_backlinks` | Check backlinks | API credits |
| `get_referring_domains` | Referring domains | API credits |
| `get_backlink_anchors` | Backlink anchor texts | API credits |
| `get_api_credit_balance` | API credit balance | Free |

## Questions it answers

- How do I check my website's or a competitor's backlinks?
- Which websites link to a domain?
- How do I check the anchor text of backlinks?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-backlinks": {
      "url": "https://crakseo.com/mcp/backlinks"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/backlinks

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
