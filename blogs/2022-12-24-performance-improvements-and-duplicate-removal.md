---
title: "Performance Improvements And Duplicate Removal"
url: "http://geodb-cities-api.wirefreethought.com/entries/feature/performance-improvements-and-duplicate-removal"
date: "2022-12-24"
author: ""
feed_url: "http://geodb-cities-api.wirefreethought.com/entries.atom"
---
GeoDB has recently undergone the following major improvements: DB query optimizations together with LRU caching JVM garbage collection tuning Migration to a GCP Kubernetes 3-node regional cluster Import algorithm updates to remove places with the same name occurring within a localized radius of each other This has resulted in: Significantly improved backend latencies averaging less than 100 millis
