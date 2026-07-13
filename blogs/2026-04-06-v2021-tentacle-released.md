---
title: "v20.2.1 Tentacle released"
url: "https://ceph.io/en/news/blog/2026/v20-2-1-tentacle-released/"
date: "2026-04-06"
author: "Yuri Weinstein"
feed_url: "https://ceph.io/en/news/blog/feed.xml"
---
This is the first minor release in the Tentacle series. We recommend that all users update to this release. Release Date ¶ April 06, 2026 Notable Changes ¶ OSD / BlueStore ¶ EC Recovery: Fixed a length calculation bug in erase_after_ro_offset() that caused empty shards to retain data, leading to shard_size >= tobj_size assertion failures when recovering small objects in EC pools.
