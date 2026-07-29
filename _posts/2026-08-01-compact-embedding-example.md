---
title: "A Simple Introduction to Compact Embeddings"
date: 2026-08-01
categories:
  - Mathematics
tags:
  - Functional Analysis
  - Sobolev Spaces
  - PDE
---

# Introduction

Compact embeddings are one of the fundamental tools in analysis and partial differential equations.
They allow us to extract convergent subsequences from bounded sequences and play a central role
in proving existence results for elliptic equations.

Let $\Omega\subset\mathbb{R}^n$ be a bounded domain. A classical Sobolev embedding theorem states that

$$
W^{1,p}(\Omega)\hookrightarrow L^q(\Omega),
$$

for suitable values of $p$ and $q$.

However, the embedding is not always compact. The compactness depends on the geometry of the
domain and the relationship between the exponents.

---

# The Rellich--Kondrachov Theorem

A fundamental result states that if

$$
1\leq p<n,
$$

then

$$
W^{1,p}(\Omega)\hookrightarrow L^q(\Omega)
$$

is compact whenever

$$
1\leq q<p^*,
$$

where the critical Sobolev exponent is

$$
p^*=\frac{np}{n-p}.
$$

This means that every bounded sequence $(u_k)$ in $W^{1,p}(\Omega)$ contains a subsequence
which converges strongly in $L^q(\Omega)$.

---

# Example

Consider a bounded sequence

$$
\{u_k\}_{k=1}^{\infty}\subset W^{1,p}(\Omega)
$$

satisfying

$$
\|u_k\|_{W^{1,p}(\Omega)}\leq C.
$$

By compactness, there exists a subsequence $(u_{k_j})$ and a function
$u\in L^q(\Omega)$ such that

$$
u_{k_j}\rightarrow u
$$

strongly in $L^q(\Omega)$.

This compactness principle is one of the main ingredients in the analysis of degenerate elliptic
equations.

---

# Further Reading

More advanced versions involve weighted Sobolev spaces, metric measure spaces, and degenerate
elliptic operators.
