---
title: "Hardening EmergencyReparentShard in v25"
url: "https://vitess.io/blog/2026-09-23-hardening-emergency-reparent-shard/"
date: "2026-09-23"
feed_url: "https://vitess.io/blog/rss/"
---
EmergencyReparentShard operations are being hardened in upcoming release v25. In this blog, we cover how ERS works and the upcoming changes that make recovery safer, faster and less brittle What is EmergencyReparentShard? # EmergencyReparentShard (ERS) is the Vitess failover process used when a shard's current primary is dead or unreachable.
