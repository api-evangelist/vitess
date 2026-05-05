---
title: "Optimizing query planning in Vitess: a step-by-step approach"
url: "https://vitess.io/blog/2024-11-05-optimizing-query-planning-in-vitess-a-step-by-step-approach/"
date: "Tue, 05 Nov 2024 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/index.xml"
---
Introduction # In this blog post, we will discuss an example of a change to the Vitess query planner and how it enhances the optimization process. The new model focuses on making every step in the optimization pipeline a runnable plan. This approach offers several benefits, including simpler understanding and reasoning, ease of testing, and the ability to use arbitrary expressions in ordering, grouping, and aggregations.
Vitess distributed query planner # VTGate is the proxy component of Vitess.
