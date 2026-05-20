---
title: "Examining query plans in MySQL and Vitess"
url: "https://vitess.io/blog/2021-09-07-examine-query-plan/"
date: "Tue, 07 Sep 2021 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
Originally posted at Andres's blog. Traditional query optimizing is mostly about two things: first, in which order and from where to access data, and then how to then combine it. You have probably seen the tree shapes execution plans that are produced from query planning.
