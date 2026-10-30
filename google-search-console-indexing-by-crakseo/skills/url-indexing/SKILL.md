---
name: url-indexing
description: Google Search Console indexing for SEO - Google index checker, request indexing via IndexNow, Bing and sitemap resubmission, and force indexing for pages Google won't index. Use when the user asks: How do I submit my website's new pages to IndexNow? How do I check whether my page is indexed in Google? How do I request backlink indexing with a quote and owner approval?
---

# Google Search Console Indexing: Index Checker, IndexNow & Force Indexing by CrakSEO

## When to use

Use after publishing or updating pages (free submission and index checks), when Search Console shows 'Crawled - currently not indexed' or 'Discovered - currently not indexed', or when backlinks and other pages you don't own need Google to crawl them (force indexing, paid).

- How do I submit my website's new pages to IndexNow? Use `submit_urls_to_indexnow`.
- How do I check whether my page is indexed in Google? Use `check_if_url_is_indexed`.
- How do I request backlink indexing with a quote and owner approval? Use `quote_force_indexing`, `submit_force_indexing`, `get_force_indexing_job`.

## Steps

1. Start with the free `get_force_indexing_balance` call to confirm the connection and the available balance.
2. Pick the tool that answers the question and pass the user's own keywords, domains, URLs and market.
3. Free submission only works for sites the user owns or has connected. For force indexing, get a quote first and send the user to approve it in the dashboard; never approve spending yourself.

## Rules

- Free to connect. IndexNow, Bing, sitemap resubmission and index checks are free. Force indexing is optional and paid with URL credits, always after an exact quote and the account owner's approval in the CrakSEO dashboard.
- Never promise rankings, indexing or timing.
- Never ask for or store passwords or API keys in chat; the client's OAuth sign-in handles access.
