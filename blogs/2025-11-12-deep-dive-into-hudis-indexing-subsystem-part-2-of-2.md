---
title: Deep Dive Into Hudi's Indexing Subsystem (Part 2 of 2)
url: https://hudi.apache.org/blog/2025/11/12/deep-dive-into-hudis-indexing-subsystem-part-2-of-2
date: '2025-11-12'
author: ''
feed_url: https://hudi.apache.org/blog/rss.xml
---
In part 1, we explored how Hudi's metadata table functions as a self-managed, multimodal indexing subsystem. We covered its internal architecture—a partitioned Hudi Merge-on-Read (MOR) table using HFile format for efficient key lookups—and how the files, column stats, and partition stats indexes work together to implement powerful data skipping. These indexes dramatically reduce I/O by pruning partitions and files that don't contain the data your query needs.
