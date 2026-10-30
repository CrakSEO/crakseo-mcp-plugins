# SEO Tools: Keyword Research, SERP, Backlinks & Rank Tracking by CrakSEO

SEO tools in one connection: keyword research, search volume, live Google SERP, rank tracking, backlinks, site audit, local SEO and AI search visibility.

All CrakSEO SEO tools in one connection, pay as you go from one balance: keyword research with search volume, keyword difficulty and CPC; live Google and Bing SERP data with AI Overview sources and Google Maps; Google rank checks, ranked keywords and competitor keyword gaps; backlinks, referring domains and anchor text; technical SEO site audits with Lighthouse and Core Web Vitals; local SEO Google Maps rankings; and AI search visibility in ChatGPT and Perplexity.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/seo` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Free to connect, and `get_api_credit_balance` is free. Data calls use prepaid API credits; each tool states its cost. Pricing: https://docs.crakseo.com/pricing/api-credits |
| Docs | https://docs.crakseo.com/mcp-servers/seo |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `check_google_rankings` | Check Google rankings for a domain | API credits |
| `get_google_serp` | Google SERP results | API credits |
| `get_bing_serp` | Bing SERP results | API credits |
| `get_ai_overview_sources` | Google AI Overview sources | API credits |
| `check_google_maps_rankings` | Google Maps rankings | API credits |
| `get_keyword_search_volume` | Keyword search volume, CPC and difficulty | API credits |
| `find_keyword_ideas` | Find keyword ideas | API credits |
| `get_keyword_difficulty` | Keyword difficulty | API credits |
| `check_backlinks` | Check backlinks | API credits |
| `get_referring_domains` | Referring domains | API credits |
| `get_backlink_anchors` | Backlink anchor texts | API credits |
| `get_ranked_keywords` | Ranked keywords for a domain | API credits |
| `find_competitor_keywords` | Find competitor keywords (keyword gap) | API credits |
| `find_competitor_domains` | Find competitor domains | API credits |
| `run_seo_site_audit` | SEO site audit for pages | API credits |
| `get_page_speed_scores` | Lighthouse and Core Web Vitals | API credits |
| `get_google_business_profile` | Google Business Profile and reviews summary | API credits |
| `check_chatgpt_brand_mentions` | ChatGPT brand mentions | API credits |
| `check_perplexity_brand_mentions` | Perplexity brand mentions | API credits |
| `get_api_credit_balance` | API credit balance | Free |

## Questions it answers

- How do I research keywords and check Google rankings?
- How do I check a website's backlinks?
- How do I find SEO competitors and keyword gaps?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-seo": {
      "url": "https://crakseo.com/mcp/seo"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/seo

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
