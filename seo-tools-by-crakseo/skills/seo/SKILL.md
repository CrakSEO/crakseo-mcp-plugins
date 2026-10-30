---
name: seo
description: SEO tools in one connection - keyword research, search volume, live Google SERP, rank tracking, backlinks, site audit, local SEO and AI search visibility. Use when the user asks: How do I research keywords and check Google rankings? How do I check a website's backlinks? How do I find SEO competitors and keyword gaps?
---

# SEO Tools: Keyword Research, SERP, Backlinks & Rank Tracking by CrakSEO

## When to use

Start here for paid SEO research with one connection. Includes all seven focused SEO data servers' tools at the same prices and from the same API-credit balance; do not connect both for duplicate results. Search Console reporting and URL Indexing are separate connections.

- How do I research keywords and check Google rankings? Use `get_keyword_search_volume`, `get_keyword_difficulty`, `check_google_rankings`.
- How do I check a website's backlinks? Use `check_backlinks`, `get_referring_domains`, `get_backlink_anchors`.
- How do I find SEO competitors and keyword gaps? Use `find_competitor_domains`, `find_competitor_keywords`.

## Steps

1. Start with the free `get_api_credit_balance` call to confirm the connection and the available balance.
2. Pick the tool that answers the question and pass the user's own keywords, domains, URLs and market.
3. Tell the user what a paid call costs and get their approval before calling it. Never buy credits.

## Rules

- Free to connect, and `get_api_credit_balance` is free. Data calls use prepaid API credits; each tool states its cost. Pricing: https://docs.crakseo.com/pricing/api-credits
- Never promise rankings, indexing or timing.
- Never ask for or store passwords or API keys in chat; the client's OAuth sign-in handles access.
