---
title: "Vitess Schema Tracking"
url: "https://vitess.io/blog/2022-01-11-schema-tracking/"
date: "Tue, 11 Jan 2022 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
What is Schema Tracking? # In a distributed relational database system, like Vitess, a central component is responsible for serving queries across multiple shards. For Vitess, it is VTGate. One of the challenges this component faces is being aware of the underlying SQL schema being used.
