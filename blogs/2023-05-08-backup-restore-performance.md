---
title: "Backup & Restore Performance"
url: "https://vitess.io/blog/2023-05-08-backup-and-restore-performance/"
date: "Mon, 08 May 2023 00:00:00 +0000"
author: ""
feed_url: "https://vitess.io/blog/rss/"
---
The performance of backups and restores is a business requirement for Vitess users and an ongoing concern for Vitess maintainers. For sufficiently large databases, if we can't take backups fast enough, we risk missing daily SLAs in a production context. In the event we need to perform an emergency restore, it is paramount that we can do so as fast as possible.
