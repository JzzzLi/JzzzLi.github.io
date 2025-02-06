---
title:          "[<strong>HotStorage'22</strong>] ScalaRAID: optimizing linux software RAID system for next-generation storage"
date:           2022-06-27 00:00:00 +0000
selected:       false
pub:            "Proceedings of the 14th ACM Workshop on Hot Topics in Storage and File Systems (HotStorage'22)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-success badge-system">System</span>'
pub_date:       "2022"

abstract: >-
    RAID has been widely adopted to enhance the performance, capacity, and reliability of the existing storage systems. However, we observe that the Linux software RAID (mdraid) suffers from its poor implementation of the lock mechanism. To address this, we propose ScalaRAID, which refines the role domain of locks and designs a new data structure to prevent different threads from preempting the RAID resources. By doing so, ScalaRAID can maximize the thread-level parallelism and reduce the time consumption of I/O request handling. Our evaluation results reveal that ScalaRAID can improve throughput by 89.4% while decreasing 99.99th percentile latency by 85.4% compared to mdraid.
# cover:          /assets/images/covers/cover3.jpg
authors:
  - Shushu Yi
  - Yanning Yang
  - Yunxiao Tang
  - Zixuan Zhou
  - Junzhe Li
  - Chen Yue
  - Myoungsoo Jung
  - Jie Zhang#
links:
  Code: https://github.com/ChaseLab-PKU/ScalaRAID
---
