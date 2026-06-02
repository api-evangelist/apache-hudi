---
title: 'Partition Stats: Enhancing Column Stats in Hudi 1.0'
url: https://hudi.apache.org/blog/2025/10/22/Partition_Stats_Enhancing_Column_Stats_in_Hudi_1.0
date: '2025-10-22'
author: ''
feed_url: https://hudi.apache.org/blog/rss.xml
---
For those tracking Apache Hudi's performance enhancements, the introduction of the column stats index was a significant development, as detailed in this blog. It represented a major advancement for query optimization by implementing a straightforward yet highly effective concept: storing lightweight, file-level statistics (such as min/max values and null counts) for specific columns. This provided Hudi's query engine a substantial performance improvement.
