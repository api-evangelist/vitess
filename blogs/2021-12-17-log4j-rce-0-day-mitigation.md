---
title: "Log4j RCE 0-day Mitigation"
url: "https://vitess.io/blog/2021-12-17-log4j-cve-patches/"
date: "Fri, 17 Dec 2021 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
Background # A critical vulnerability CVE-2021-44228 in the Apache Log4j logging library was disclosed on Dec 9. The project provided release 2.15.0 with a patch that mitigates the impact of this CVE. It was quickly found that the initial patch was insufficient, and an additional CVE CVE-2021-45046 followed.
