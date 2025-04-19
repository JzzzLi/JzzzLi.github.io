---
title:          "[<strong>NDSS'25</strong>] Automatic Library Fuzzing through API Relation Evolvement"
date:           2025-02-24 00:00:00 +0800
selected:       true
pub:            "Network and Distributed System Security Symposium (NDSS)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-security">Security</span><span class="badge badge-pill badge-conference">Conference</span>'
pub_date:       "2025"

abstract: >-
    This work proposes NEXZZER, a new fuzzer that automatically detects vulnerabilities in libraries. NEXZZER employs a hybrid relation learning strategy to continuously infer and evolve API relations, incorporating a novel driver architecture to augment the testing coverage of libraries and facilitate deep vulnerability discovery. We evaluated NEXZZER across 18 libraries and the Google Fuzzer Test Suite. The results demonstrate its considerable advantages in code coverage and vulnerability-finding capabilities compared to prior works. NEXZZER can also automatically identify and filter out most API misuse crashes. Moreover, NEXZZER discovered 27 previously unknown vulnerabilities in well-tested libraries, including OpenSSL and libpcre2. At the time of writing, developers have confirmed 24 sof them, and 9 were fixed because of our reports.
cover:          /assets/images/covers/nexzzer.png
authors:
  - Jiayi Lin
  - Qingyu Zhang
  - Junzhe Li
  - Chenxin Sun
  - Hao Zhou
  - Changhua Luo#
  - Chenxiong Qian#
links:
  Code: https://figshare.com/s/9539927ac84ee6a7ac14
  Paper: assets/papers/nexzzer-ndss25.pdf
---
