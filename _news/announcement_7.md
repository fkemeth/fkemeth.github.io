---
layout: post
date: 2025-11-26 12:00:00-0400
inline: true
related_posts: false
---

I've published a new article, **"AI News Agent: A Smarter Newsletter That Knows When to Send"**, where I share an intelligent n8n workflow that decides when news is actually worth sending.

Unlike fixed-schedule newsletters, this **AI News Agent** uses an editorial AI to evaluate whether today's news meets quality thresholds—with built-in deduplication against the last 5 editions and configurable frequency guardrails (min/max days between sends). The workflow fetches news via **SerpAPI's DuckDuckGo News**, stores articles with automatic deduplication, and enriches selected pieces with **Tavily** web search before delivering via Telegram.

You can read it on Akribic [here](https://www.akribic.com/blog/ai-news-agent).