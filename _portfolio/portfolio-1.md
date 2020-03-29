---
title: "Coloring Embedder (IEEE ICDE 2019)"
excerpt: "A compact hash-based graph data structure for fast multiple sets membership query<br/><img src='/images/coloringEmbedder.png'>"
collection: portfolio
---

**Multi-set query** is a fundamental issue in data science. When the sizes of multi-sets are large, exact matching methods like hash tables need too much memory, and they cannot achieve high query speed. Bloom filters are recently used to handle big data query, but they cannot achieve high accuracy when the memory space is tight. In this paper, we propose a new data structure named **coloring embedder**, which is fast, accurate as well as memory efficient. The insight is to first map elements to a high dimensional space to almost eliminate hashing collisions, and then use a dimensional reduction representation, which is similar to coloring a graph, to save memory. Theoretical proofs and experimental results show that compared to the state-of-the-art, the error rate of the coloring embedder is thousands of times smaller even with much less memory usage, and the query speed of the coloring embedder is about 2 times faster.

[Paper Link](https://ieeexplore.ieee.org/abstract/document/8731408)

[Code Link](https://github.com/4colorclassifier/4colorclassifier)
