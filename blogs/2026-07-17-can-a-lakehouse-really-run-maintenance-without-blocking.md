---
title: "Can a Lakehouse Really Run Maintenance Without Blocking Writes?"
url: "https://hudi.apache.org/blog/2026/07/17/async-compaction-background-maintenance"
date: "2026-07-17"
feed_url: "https://hudi.apache.org/blog/rss.xml"
---
Async compaction in Hudi is not a performance tweak layered onto ingestion — it is the natural consequence of a storage engine that separates correctness from optimization, a principle mature databases have followed for decades.
