---
title: "A second-order in time, BGN-based parametric finite element method for geometric flows of curves"
collection: publications
category: manuscripts
permalink: /publication/2024-10-01-paper-3-BGN2-JCP
authors: '(Joint with Wei Jiang and Chunmei Su)'
date: 2024-10-01
venue: 'Journal of Computational Physics, 514, Paper 113220'
paperurl: 'http://Ganghui-Zhang.github.io/files/BGN2-JCP.pdf'
---

Abstract: Over the last two decades, the field of geometric curve evolutions has attracted significant attention from scientific computing. One of the most popular numerical methods for solving geometric flows is the so-called BGN scheme, which was proposed by Barrett et al. (2007) [8], due to its favorable properties (e.g., its computational efficiency and the good mesh property). However, the BGN scheme is limited to first-order accuracy in time, and how to develop a higher-order numerical scheme is challenging. In this paper, we propose a fully discrete, temporal second-order parametric finite element method, which integrates with two different mesh regularization techniques, for solving geometric flows of curves. The scheme is constructed based on the BGN formulation and a semi-implicit Crank-Nicolson leap-frog time stepping discretization as well as a linear finite element approximation in space. More importantly, we point out that the shape metrics, such as manifold distance and Hausdorff distance, instead of function norms, should be employed to measure numerical errors. Extensive numerical experiments demonstrate that the proposed BGN-based scheme is second-order accurate in time in terms of shape metrics. Moreover, by employing the classical BGN scheme as mesh regularization techniques, our proposed second-order schemes exhibit good properties with respect to the mesh distribution. In addition, an unconditional interlaced energy stability property is obtained for one of the mesh regularization techniques.
