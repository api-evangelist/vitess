---
title: "Vitess Now Supports Recursive CTEs: A Step Closer to Full MySQL Compatibility"
url: "https://vitess.io/blog/2024-08-23-recursive-cte/"
date: "Fri, 23 Aug 2024 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/index.xml"
---
We are excited to announce that Vitess now supports recursive Common Table Expressions (CTEs), marking another significant step in our journey to fully align with MySQL’s capabilities. Recursive CTEs, often a critical feature for complex query handling, allow for the execution of recursive queries within a single CTE. This addition brings more flexibility and power to developers using Vitess, especially those working with distributed databases.
One of the key challenges in implementing recursive CTEs within a sharded environment is managing the distribution of data across multiple shards.
