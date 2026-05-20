---
title: "An Interesting Optimization"
url: "https://vitess.io/blog/2024-07-22-an-interesting-optimization/"
date: "Mon, 22 Jul 2024 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
Introduction # I recently encountered an intriguing bug. A user reported that their query was causing vtgate to fetch a large amount of data, sometimes resulting in an Out Of Memory (OOM) error. For a deeper understanding of grouping and aggregations on Vitess, I recommend reading this prior blog post.
