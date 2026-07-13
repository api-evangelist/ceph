---
title: "Ceph Object Storage Deep Dive Series Part 3: Version and Object Lock"
url: "https://ceph.io/en/news/blog/2025/rgw-deep-dive-3/"
date: "2025-12-11"
author: "Daniel Alexander Parkes, Anthony D'Atri"
feed_url: "https://ceph.io/en/news/blog/feed.xml"
---
Introduction ¶ In the first and second parts of this deep dive series, we dissected the core foundations of Ceph RGW: stateless frontends, specialized RADOS pools, bucket index mechanics, and the head/tail data layout. We explored how the Ceph Object Gateway(RGW) achieves massive scalability through dynamic bucket sharding and how background processes, including Garbage Collection and Lifecycle Management, automate data governance. We now turn to two critical features for enterprise data protection: S3 Object Versioning and S3 Object Lock .
