---
title: "Structure-preserving parametric finite element method for surface diffusion based on Lagrange multiplier approaches"
collection: publications
category: manuscripts
permalink: /publication/2025-09-01-paper-6-Lagrange-SISC
authors: '(Joint with Harald Garcke, Wei Jiang and Chunmei Su)'
date: 2025-09-01
venue: 'SIAM Journal on Scientific Computing, 47(3), Pages A1983-A2011'
paperurl: 'https://epubs.siam.org/doi/10.1137/24M1687546'
---

Abstract: We propose a novel formulation for parametric finite element methods to simulate surface diffusion, which incorporates two scalar Lagrange multipliers and two evolution equations involving the surface area and volume, respectively, to ensure that the resulting numerical methods preserve the geometric structure of surface diffusion, i.e., the area-decreasing and volume-preserving properties. By discretizing the spatial variable using piecewise linear finite elements and the temporal variable using either the Crank-Nicolson method or the backward differentiation formulae method, we develop several high-order temporal schemes that effectively preserve the structure at a fully discrete level. These new schemes are implicit and can be efficiently solved using Newton's method. Extensive numerical experiments demonstrate that our methods achieve the desired temporal accuracy, as measured by the manifold distance or Hausdorff distance, while simultaneously preserving the geometric structure of surface diffusion.
