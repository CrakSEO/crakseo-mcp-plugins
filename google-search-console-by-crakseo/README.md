# Free Google Search Console (GSC) & Bing Webmaster Tools by CrakSEO

Free Google Search Console (GSC) for SEO: your own Search Console search analytics, keywords, search rankings, clicks, impressions, URL inspection and Bing Webmaster Tools.

Connect your own Google Search Console (GSC) and Bing Webmaster Tools accounts for SEO. Pull Search Console search analytics from Google Search: clicks, impressions, CTR, average position, keywords and search rankings for every query and page, for any date range. Run URL inspection to see a page's Google index status, check sitemaps and crawl issues, and see your Bing URL submission quota. Use your Search Console data to find why organic traffic dropped, which keywords are close to page one (striking distance keywords), and which pages compete for the same keyword (keyword cannibalization). Your first-party Google data, not third-party estimates. Free.

| | |
| --- | --- |
| Endpoint | `https://crakseo.com/mcp/search-console` |
| Transport | Streamable HTTP |
| Sign-in | OAuth (a CrakSEO account is created on first sign-in) |
| Price | Every tool is free. Google and Bing quotas apply. |
| Docs | https://docs.crakseo.com/mcp-servers/search-console |

## Tools

| Tool | What it does | Price |
| --- | --- | --- |
| `list_search_console_properties` | List Search Console and Bing sites | Free |
| `get_search_console_performance` | Google Search Console performance | Free |
| `inspect_url_in_google` | Inspect a URL in Google Search Console | Free |
| `list_sitemaps` | List Search Console sitemaps | Free |
| `submit_sitemap` | Submit a sitemap to Google and Bing | Free |
| `get_bing_webmaster_stats` | Bing Webmaster Tools stats | Free |
| `get_bing_crawl_issues` | Bing crawl issues | Free |
| `get_bing_url_submission_quota` | Bing URL submission quota | Free |

## Questions it answers

- Which Google search queries bring clicks to my website?
- Why is my page not indexed in Google?
- How do I check Bing search traffic, crawl issues and sitemap submissions?

## Install

Install from the Cursor Marketplace, or add the server to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "crakseo-search-console": {
      "url": "https://crakseo.com/mcp/search-console"
    }
  }
}
```

Other clients: https://docs.crakseo.com/mcp-servers/search-console

## Privacy and support

- Privacy: https://crakseo.com/privacy
- Terms: https://crakseo.com/terms
- Support: support@crakseo.com

The files in this folder are MIT-licensed. That does not license the hosted CrakSEO service.
