---
title: "Managing Multiple Lua Scripts with Ceph Object Storage"
url: "https://ceph.io/en/news/blog/2026/rgw-multiple-scripts/"
date: "2026-06-10"
author: "Kirby Chin"
feed_url: "https://ceph.io/en/news/blog/feed.xml"
---
Since the Pacific release, Lua scripting in Ceph's RADOS Gateway (RGW) has provided users the ability to interpolate a single script to upload operations per request context and tenant. This way of working might be completely fine for a storage deployment with limited scripting customizations. However, script management becomes increasingly difficult as more than one team wants to get involved in managing the Lua script within the same context and tenant.
