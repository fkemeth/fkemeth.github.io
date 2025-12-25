---
layout: post
date: 2025-12-25 12:00:00-0400
inline: true
related_posts: false
---

I've published a new article, **"GPT-5.1 vs Ministral-3 3B: Evaluating AI Newsletter Quality For Local AI Newsletter Generation"**, where I test whether a $0 local model can match a frontier cloud model for automated newsletters.

I ran the same 6-stage **n8n** workflow—news ingestion, relevance scoring, editorial decision, research enrichment, formatting, and delivery—with both **GPT-5.1** and **Ministral-3 3B** (via Ollama on a MacBook). Using **LLM-as-a-judge** evaluation across five topics, the local model scored 3.47 vs 4.07—closer than expected. The post covers three techniques that make local models viable: task decomposition, JSON auto-correction, and short context windows.

You can read it on Akribic [here](https://www.akribic.com/blog/multi-agent-newsletter).