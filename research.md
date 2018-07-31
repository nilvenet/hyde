---
layout: page
title: Research
---

<script type="text/x-mathjax-config">
    MathJax.Hub.Config({
      tex2jax: {
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
        inlineMath: [['$','$']]
      }
    });
  </script>
  <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script> 


### Spatiotemporal statistics for global climate data

### Positive definite kernels on metric spaces

In the context of data science, positive definite kernels are interesting for at least two reasons:

- Whenever you get a positive kernel $K$ on a space $E$, there exists an Hilbert space $\mathcal{H}$ and a map $\Phi: E \rightarrow \mathcal{H}$ such that

  $$K(x,y) = \left\langle \Phi(x), \Phi(y) \right\rangle_{\mathcal{H}}.$$

  This allows to substitute a positive definite kernel to a scalar product when the latter is not available on $E$, providing the whole arsenal of learning methods on Euclidean spaces.

- Positive definite kernels are the covariances of random processes. In particular they are sufficient to give existence of Gaussian processes.

### Asymptotic results for Gaussian process modelling