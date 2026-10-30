# Google Search Console Indexing: Index Checker, IndexNow & Force Indexing by CrakSEO

Google Search Console indexing for SEO: Google index checker, request indexing via IndexNow, Bing and sitemap resubmission, and force indexing for pages Google won't index.

Check and fix Google indexing for SEO. See whether your pages are in the Google index with the index checker, then get new and updated pages indexed faster: submit URLs to IndexNow and Bing, and resubmit your sitemap to Google Search Console, all free. For pages stuck in 'crawled, currently not indexed' or 'discovered, currently not indexed', use force indexing to push public URLs to Google through an indexing service, paid with URL credits after a quote and your approval. Works alongside CrakSEO's Google Search Console connector for URL inspection and index coverage. Built for SEO teams, developers shipping new pages, and site migrations.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/url-indexing` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Free to connect. IndexNow, Bing, sitemap resubmission and index checks are free. Force indexing is optional and paid with URL credits, always after an exact quote and the account owner's approval in the CrakSEO dashboard. |
| Docs | https://docs.crakseo.com/mcp-servers/url-indexing |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `submit_urls_to_indexnow` | Free URL submission: IndexNow | Free |
| `submit_urls_to_bing` | Free URL submission: Bing Webmaster Tools | Free |
| `notify_search_engines_free` | Free URL submission: IndexNow, Bing and the Google next step | Free |
| `check_if_url_is_indexed` | Free index check: are URLs indexed in Google | Free |
| `submit_sitemap` | Submit a sitemap to Google and Bing | Free |
| `get_force_indexing_balance` | Force indexing: read URL credits and readiness | Free |
| `quote_force_indexing` | Force indexing: quote URLs (backlink and Google indexer) | Free quote; submission uses URL credits |
| `submit_force_indexing` | Force indexing: submit approved quote | 1 URL credit per URL the indexing service accepts |
| `get_force_indexing_job` | Force indexing: read job | Free |
| `list_force_indexing_jobs` | Force indexing: list jobs | Free |

## Questions it answers

- How do I submit my website's new pages to IndexNow?
- How do I check whether my page is indexed in Google?
- How do I request backlink indexing with a quote and owner approval?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-url-indexing": {
      "url": "https://crakseo.com/mcp/url-indexing"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/url-indexing

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
