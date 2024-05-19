---
title: "Towards Timing-Driven Routing: An Efficient Learning Based Geometric Approach"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
date: 2023-11-30
venue: 'ICCAD'
paperurl: 'https://mrsun0.github.io/gwsun.github.io/files/Routing_Wirelength_Timing.pdf'
author: '*Liying Yang, * **Guowei Sun** and Hu Ding (Co-author)'
excerpt: '*Liying Yang, * **Guowei Sun** and Hu Ding (Co-author)'
citation: 'L. Yang, G. Sun and H. Ding, "Towards Timing-Driven Routing: An Efficient Learning Based Geometric Approach," 2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD), San Francisco, CA, USA, 2023, pp. 1-9, doi: 10.1109/ICCAD57390.2023.10323981. keywords: {Heating systems;Geometry;Design automation;Neural networks;Routing;Delays;Task analysis},

'
---

As the rapid increasing of the circuits complexity,
it is urgent to develop efficient algorithmic techniques for EDA.
In this paper, we consider the routing problem which is a key
part for designing high-quality chips. In particular, we combine
both the max path length and total wirelength for modeling our
optimization objective, since the path delay often causes timing
issue that can seriously degrade the whole routing efficiency
(even if the total wirelength is small). Comparing with most of
the previous works that only considering wirelength, the timing-driven routing objective is much more challenging to optimize.
We propose an efficient learning-based approach together with
several novel insights in geometry. For moderate-degree nets,
our approach can yield a better smooth trade-off between the
wirelength and max path length comparing with the state-of-the-art methods. For large-degree nets, we propose an elegant
and easy-to-implement geometric data structure called “data-dependent polar quadtree” in the space; using this structure, we
can successfully plug our learning-based approach into a divide
& merge framework and the optimization quality over the whole
instance can be well preserved.
