---
title: "Recover the Ceph Monitor Store Using OSDs"
url: "https://ceph.io/en/news/blog/2026/mon-recovery-from-osds/"
date: "2026-07-04"
author: "Eugen Block, crossposted by Anthony D'Atri"
feed_url: "https://ceph.io/en/news/blog/feed.xml"
---
Introduction ¶ A few weeks ago I helped a Ceph user to recover his broken cluster (see this thread ). Basically, after his Monitors stopped working he re-deployed a new cluster with the same Ceph FSID and attached the existing OSDs to the re-deployed hosts. But it’s not that easy to re-activate those OSDs because the new Monitors don’t have the old osdmap, hence they don’t know anything about the existing OSDs.
