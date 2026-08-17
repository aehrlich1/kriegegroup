---
title: "Latex Example Post"
url: "/latex-example-post/"
---

# Latex Example Post

At first, we sample \(f(x)\) in \(N\) equidistant points around \(x^*\):

```text
f_k = f(x_k),  x_k = x^* + kh,
k = -(N-1)/2, …, (N-1)/2
```

where \(h\) is some step. Then we interpolate the points \((x_k,f_k)\) by the polynomial

```text
P_(N-1)(x) = Σ_(j=0)^(N-1) a_j x^j
```

Its coefficients are found as a solution of a system of linear equations.

