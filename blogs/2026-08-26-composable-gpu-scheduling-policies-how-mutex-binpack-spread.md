---
title: "Composable GPU Scheduling Policies: How mutex, binpack, spread, and numa Work Together"
url: "https://project-hami.io/blog/composable-scheduler-policies"
date: "2026-08-26"
feed_url: "https://project-hami.io/blog/rss.xml"
---
HAMi v2.10.0 lets hami.io/gpu-scheduler-policy take an ordered, comma-separated policy list. This post explains the filter-then-sort evaluation model behind the feature, the semantics of each policy, common recipes, and the steps to adopt and verify it.
