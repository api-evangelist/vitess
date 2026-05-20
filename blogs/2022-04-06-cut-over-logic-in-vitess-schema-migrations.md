---
title: "Cut-over logic in vitess schema migrations"
url: "https://vitess.io/blog/2022-04-06-online-ddl-vitess-cut-over/"
date: "Wed, 06 Apr 2022 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
Vitess supports managed, non-blocking schema migrations based on VReplication, aptly named vitess migrations. Vitess migrations are powerful, revertible, and failure agnostic. They take an asynchronous approach, which is more lightweight on the database server.
