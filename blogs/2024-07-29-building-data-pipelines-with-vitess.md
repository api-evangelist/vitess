---
title: "Building Data Pipelines With Vitess"
url: "https://vitess.io/blog/2024-07-29-cdc-vstream/"
date: "Mon, 29 Jul 2024 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/index.xml"
---
Vitess is a popular CNCF project that is used to scale some of the largest MySQL installations in the world — by companies like Slack, Square, Shopify, and GitHub. It provides sharding, connection pooling, and many other features that make it easy to scale MySQL horizontally.
Vitess and MySQL are ideally suited for use as an Online Transaction Processing (OLTP) system — where the end-user interacts directly with the system and fast response times are essential as they get product and service information, generating critical business records such as orders, user profiles, and more.
