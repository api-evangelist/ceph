---
title: "KV Caching with vLLM, LMCache, and Ceph"
url: "https://ceph.io/en/news/blog/2025/vllm-kv-caching/"
date: "2025-12-10"
author: "Kyle Bader, Tushar Gohad"
feed_url: "https://ceph.io/en/news/blog/feed.xml"
---
Inference accounts for 90% of machine learning costs for deployed AI systems, and it is no surprise that inference optimization is a burgeoning topic in the research community. IDC estimates that global enterprises will invest $307 billion USD on AI solutions in 2025, and that number is expected to grow aggressively year-over-year. Understanding the workload ¶ Unlike training, inference for autoregressive language models only involves the forward pass, which itself is broken up into two distinct phases: prefill and decode.
