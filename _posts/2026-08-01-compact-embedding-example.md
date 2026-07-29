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

Compact embeddings are among the most important tools in functional analysis and partial differential equations. They allow us to obtain strong convergence from bounded sequences and play a fundamental role in existence theories for elliptic equations.

<!--more-->

Let $\Omega\subset\mathbb{R}^n$ be a bounded domain. A classical Sobolev embedding theorem states that

$$
W^{1,p}(\Omega)\hookrightarrow L^q(\Omega),
$$

for suitable values of $p$ and $q$.

The compactness of this embedding depends on the geometry of the domain and the relationship between the exponents.

## The Rellich--Kondrachov Theorem

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

where

$$
p^*=\frac{np}{n-p}.
$$

This means every bounded sequence in $W^{1,p}(\Omega)$ contains a subsequence converging strongly in $L^q(\Omega)$.

## Example

Consider a bounded sequence

$$
\{u_k\}_{k=1}^{\infty}\subset W^{1,p}(\Omega)
$$

satisfying

$$
\|u_k\|_{W^{1,p}(\Omega)}\leq C.
$$

Then there exists a subsequence $(u_{k_j})$ and a function $u\in L^q(\Omega)$ such that

$$
u_{k_j}\rightarrow u
$$

strongly in $L^q(\Omega)$.
