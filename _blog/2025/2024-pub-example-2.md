---
title:          "Userspace Memory Management"
date:           2024-12-09 00:01:00 +0800
selected:       true
pub:            "Operating Systems Design and Implementation (OSDI)"
pub_date:       "2025"
abstract: >-
  We introduce USM, a framework for rapid development of memory management (MM) policies in Linux. USM adopts a microkernel approach, allowing MM policies to run in
  userspace. We demonstrate the flexibility of USM by using it to implement various MM policies. Further, we evaluate USM’s performance, showing comparable or better results than Linux, with up to a $1.41×$ improvement for Redis using a basic MM policy. Additionally, we compare USM with the tate-of-the-art FBMM policy and show that USM supports implementing research MM policies such as the PTEMagnet policy for virtual machines.

#cover:          /assets/images/covers/cover2.jpg
authors:
  - Assane Fall+
  - Yves Kone
  - Kilian Kemgne
  - renaud lachaize 
  - Jean-Pierre Lozi
  - Alain Tchana
  - Luc MAHOP

links:
  Paper: https://www.biorxiv.org
  Code: https://github.com
  Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---