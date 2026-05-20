---
title: "Vtctld Server API"
url: "https://vitess.io/blog/2023-04-17-vtctldserver-api/"
date: "Mon, 17 Apr 2023 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
We are thrilled to discuss VtctldServer, the new gRPC API for performing cluster management operations with vtctld components. This is the (near-) culmination of long, steady migration that began back in Vitess v9 (!!!) and went GA in Vitess v15, so we'd like to talk a bit about the motivation behind the move, the design of the new API, and where we go from here. Why? # Vitess users may have found themselves invoking various cluster management operations (think CreateKeyspace, EmergencyReparentShard, Backup, and so on) via the vtctlclient program.
