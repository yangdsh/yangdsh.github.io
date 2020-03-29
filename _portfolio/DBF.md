---
title: "Difference Bloom Filter (IEEE ICC 2017)"
excerpt: "A compact hash-based graph data structure for fast multiple sets membership query<br/><img src='/images/DBF.jpg'>"
collection: portfolio
---

In this paper, we propose a hash-based data structure named Difference Bloom Filter (DBF) for approxiamate multi-set membership query.
There are two key design principles for DBF.
The first one is to represent all elements with a single Bloom Filter so that all false positive can be eliminated.
The second one is to use the slow but cheap DRAM memory to improve the accuracy of the filter on the fast but expensive SRAM memory.
DBF is hundreds of times more accurate than all the Bloom Filter like algorithms.

[Paper Link](https://ieeexplore.ieee.org/document/7996678/) (There is a typo in the department name.)

[Code Link](https://github.com/yangdsh/DBF)
