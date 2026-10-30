# AI Search Visibility: Brand Mentions in ChatGPT, Perplexity & AI Overviews by CrakSEO

AI search visibility for SEO and GEO: check brand mentions in ChatGPT, Perplexity and Google AI Overviews, and see which sources and citations AI answers use.

See how AI search treats your brand. Check whether ChatGPT and Perplexity mention your brand for the prompts your customers ask, see the sources and citations behind each answer, and find which sites Google AI Overviews cite for your keywords. Compare your AI visibility with competitors for generative engine optimization (GEO), answer engine optimization (AEO) and LLM visibility. Each check is a sample, not continuous monitoring.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/ai-visibility` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Free to connect, and `get_api_credit_balance` is free. Data calls use prepaid API credits; each tool states its cost. Pricing: https://docs.crakseo.com/pricing/api-credits |
| Docs | https://docs.crakseo.com/mcp-servers/ai-visibility |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `get_ai_overview_sources` | Google AI Overview sources | API credits |
| `check_chatgpt_brand_mentions` | ChatGPT brand mentions | API credits |
| `check_perplexity_brand_mentions` | Perplexity brand mentions | API credits |
| `get_api_credit_balance` | API credit balance | Free |

## Questions it answers

- Does ChatGPT mention my brand for this buyer question?
- Does Perplexity mention my brand and which sources does it cite?
- How do I check which pages Google's AI Overview cites?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-ai-visibility": {
      "url": "https://crakseo.com/mcp/ai-visibility"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/ai-visibility

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
