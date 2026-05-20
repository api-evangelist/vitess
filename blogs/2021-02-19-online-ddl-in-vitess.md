---
title: "Online DDL in Vitess"
url: "https://vitess.io/blog/2021-02-19-online-ddl-in-vitess/"
date: "Fri, 19 Feb 2021 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
Vitess introduces a new way to run schema migrations: non-blocking, asynchronous, scheduled online DDL. With online DDL Vitess simplifies the schema migration process by taking ownership of the operational overhead, and providing the user a simple, familiar interface: the standard ALTER TABLE statement. Let’s first give some background and explain why schema migrations are such an issue in the databases world, and then dive into implementation details The relational model and the operational overhead # The relational model is one of the longest surviving models in the software world,…
