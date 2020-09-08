---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 522 homework

[Submit with gradescope](https://www.gradescope.com/courses/170391)

## Week 2 (Due Thursday, September 10)

1. (3.2) Prove that the properties (a)--(c) of a measure imply *continuity from below*: if $A\_n$ is an increasing sequence of sets and $A=\bigcup A\_n$, then $m(A)=\sup m(A\_n)$. Then prove *continuity from above*: if $A\_n$ is a decreasing sequence of sets, $m(A\_n)$ is finite, and $A=\bigcap A\_n$, then $m(A)=\inf m(A\_n)$.
2. (3.4) Prove directly from the definition of null set that the null sets are closed under countable unions. (The definition of $A$ is null: for all $\epsilon>0$ there exist intervals $I\_n$ such that $A\subset\bigcup I\_n$ and $\sum l(I\_n)\lt\epsilon$.)
3. (4.1) Show that the following sets are all in bijection with one another: $\mathbb R$, $(0,1)$, $(0,\infty)$, $\mathcal P(\mathbb N)$, and $\set{A\in P(\mathbb N)\mid A\text{ is infinite}\}$.
4. (4.2) Which of the following categories satisfy the analog of the Cantor--Schroder--Bernstein theorem? (That is, monomorphisms $A\to B\to A$ implies isomorphism $A\cong B$.) linear orders with order-preserving maps; groups with group homomorphisms; topological spaces with continuous maps; topological spaces with piecewise continuous maps.

## Week 1 (Due Tuesday, September 1)

1. (1.1) With the definition of $C+C'$ for Dedekind cuts, show that addition is commutative and associative.
2. (1.4) Show that any two complete ordered fields are isomorphic as ordered fields. [Hint: observe that both must contain a copy of $\mathbb Q$ which is dense.]
3. (2.1) Compute the sum of the lengths of all of the intervals removed from $[0,1]$ in the construction of the Cantor set. What if some fraction other than $1/3$ is removed at each stage?
4. (2.2) Prove proposition 2.4 in the notes: $A$ is nowhere dense iff $\bar A$ contains no intervals of positive-length iff $A$ is non-dense in every open set.

<script type='text/x-mathjax-config'>
  MathJax.Hub.Config({
    tex2jax: {
      inlineMath: [['$','$'], ['\\(','\\)']],
      processEscapes: true
    },
    TeX: {
      Macros: {
        set: ["{\\left\\{ #1 \\right\\}}", 1],
        abs: ["{\\left| #1 \\right|}", 1],
        lt: ["<"]
      }
    }
  });
</script>
<script src='https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-AMS_HTML'></script>