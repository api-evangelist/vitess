---
title: "Consistent Lookup Vindex: Achieving Data Consistency without 2PC"
url: "https://vitess.io/blog/2024-04-29-consistent-lookup-vindex/"
date: "Mon, 29 Apr 2024 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
Vindex # Vitess uses Vindexes (short for Vitess Index) to associate rows in a table with a designated address known as Keyspace ID. This allows Vitess to direct a row to its intended destination, typically a shard within the cluster. Vindexes play a dual role: enabling data sharding through Primary Vindexes and facilitating global indexing via Secondary Vindexes.
