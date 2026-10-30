# Local SEO: Google Maps Rank Checker & Business Profile Ratings by CrakSEO

Local SEO for Google Maps: check Maps rankings for any keyword and location, with Google Business Profile ratings and review counts for you and local competitors.

Local SEO data for Google Maps and Google Business Profile. Check where a business ranks on Google Maps for any keyword and place, see the local competitors ranking above it, and compare Google Business Profile ratings and review counts. Use it for local rank tracking, local search checks across neighborhoods and cities, and reporting for multi-location businesses. Review text isn't included.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/local-seo` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Free to connect, and `get_api_credit_balance` is free. Data calls use prepaid API credits; each tool states its cost. Pricing: https://docs.crakseo.com/pricing/api-credits |
| Docs | https://docs.crakseo.com/mcp-servers/local-seo |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `check_google_maps_rankings` | Google Maps rankings | API credits |
| `get_google_business_profile` | Google Business Profile and reviews summary | API credits |
| `get_api_credit_balance` | API credit balance | Free |

## Questions it answers

- How do I check my business's Google Maps ranking?
- How do Google Maps results differ between locations?
- How do I check a Google Business Profile's rating and review count?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-local-seo": {
      "url": "https://crakseo.com/mcp/local-seo"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/local-seo

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
