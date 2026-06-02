---
title: 'Maximizing Throughput with Apache Hudi NBCC: Stop Retrying, Start Scaling'
url: https://hudi.apache.org/blog/2025/12/16/maximizing-throughput-nbcc
date: '2025-12-16'
author: ''
feed_url: https://hudi.apache.org/blog/rss.xml
---
Data lakehouses often run multiple concurrent writers—streaming ingestion, batch ETL, maintenance jobs. The default approach, Optimistic Concurrency Control (OCC), assumes conflicts are rare and handles them through retries. That assumption breaks down in increasingly common scenarios, such as running maintenance batch jobs on tables receiving streaming writes. When conflicts become the norm, retries pile up with OCC, and the write throughput tanks.
