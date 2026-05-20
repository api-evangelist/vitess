---
title: "Online DDL: why FOREIGN KEYs are not supported"
url: "https://vitess.io/blog/2021-06-15-online-ddl-why-no-fk/"
date: "Tue, 15 Jun 2021 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
This post explains the inherent problem of running online schema changes in MySQL, on tables participating in a foreign key relationship. We'll lay some ground rules and facts, sketch a simplified schema, and dive into an online schema change operation. Our discussion applies to gh-ost, pt-online-schema-change, and VReplication based migrations, or any other online schema change tool that works with a shadow/ghost table like the Facebook tools.
