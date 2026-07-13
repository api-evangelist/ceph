---
title: "Breaking the Static Key Habit: Modernizing Ceph RGW S3 Security with STS"
url: "https://ceph.io/en/news/blog/2025/rgw-modernizing-sts/"
date: "2025-12-18"
author: "Daniel Alexander Parkes, Anthony D'Atri"
feed_url: "https://ceph.io/en/news/blog/feed.xml"
---
Introduction: The USD 148 Million Lesson ¶ In late 2016, Uber learned that intruders had accessed a trove of personal data stored in an Amazon S3 bucket. The entry point was painfully mundane: attackers accessed Uber's source code on GitHub using stolen credentials, found an AWS credential, and used it to access Uber’s data. That single, long-lived credential exposed data on roughly 57 million users and 600,000 drivers.
