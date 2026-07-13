---
title: "Source Code Walkthrough of the GPU Pod Scheduling Process in HAMi"
url: "https://project-hami.io/blog/hami-gpu-scheduling-source-code"
date: "2024-12-31"
author: ""
feed_url: "https://project-hami.io/blog/rss.xml"
---
During the use of HAMi, it is common for Pods to be created and remain in a Pending state, particularly due to the following two issues: Pod UnexpectedAdmissionError Pod Pending This section provides a rough walkthrough of the related code to explain the interactions between components during scheduling and how resources are calculated. Other details may be omitted. Scheduling Process ​ The official documentation provides a clear overview before looking at the code: The process can be broken...
