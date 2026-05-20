---
title: "A new Protocol Buffers generator for Go"
url: "https://vitess.io/blog/2021-06-03-a-new-protobuf-generator-for-go/"
date: "Thu, 03 Jun 2021 09:07:21 -0800"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
Although the main interface between applications and a Vitess database is through the MySQL protocol, Vitess is a large and complex distributed system, and all the communication between the different services in a Vitess cluster is performed through GRPC. Because of this, all service boundaries and messages between Vitess' systems are specified using Protocol Buffers. The history of Vitess' integration with Protocol Buffers is rather involved: We have been using and keeping up to date with the Go Protocol Buffers package since its earliest releases, up until May last year, when Google…
