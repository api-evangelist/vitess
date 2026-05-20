---
title: "schemadiff: Vitess In-memory Schema Diffing, Normalization, Validation and Manipulation"
url: "https://vitess.io/blog/2023-04-24-schemadiff/"
date: "Mon, 24 Apr 2023 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
Introducing schemadiff, an internal library in Vitess that has been one of its best-kept secrets until now. At its core, schemadiff is a declarative, programmatic library that can produce a diff in SQL format of two entities: tables, views, or full blown database schemas. But it then goes beyond that to normalize, validate, export, and even apply schema changes, all declaratively and without having to use a MySQL server.
