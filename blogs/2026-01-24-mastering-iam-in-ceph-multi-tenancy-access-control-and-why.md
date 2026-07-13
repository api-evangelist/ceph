---
title: "Mastering IAM in Ceph: Multi-Tenancy, Access Control, and Why ACLs Must Die"
url: "https://ceph.io/en/news/blog/2026/mastering-iam/"
date: "2026-01-24"
author: "Daniel Alexander Parkes, Anthony D'Atri"
feed_url: "https://ceph.io/en/news/blog/feed.xml"
---
Introduction ¶ Introduction: When Security Theater Becomes a Real Disaster ¶ In March 2017, a misconfigured S3 bucket at Verizon exposed the personal information of 14 million customers. The root cause wasn't a sophisticated attack; it was a simple oversight in access permissions. The bucket was set to be publicly accessible due to S3 permission misconfiguration, and no one noticed because ACLs were managed separately from the company's centralized IAM policies.
