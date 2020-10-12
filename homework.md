---
header-includes: |
  \def\set#1{{\left\{#1\right\}}}
  \def\abs#1{{\left|#1\right|}}
  \def\lt{<}
---

# Math 522 homework

[Submit with gradescope](https://www.gradescope.com/courses/170391)

## Week 7 (Due Tuesday, October 13)

1. (11.1) Let $P=(I\_n)$ and $Q=(J\_n)$ be interval partitions of $\omega$, and let $x,y\in2^\omega$. Prove that $\mathrm{Diff}(P,x)\subset \mathrm{Diff}(Q,y)$ if and only if for all but finitely many $m$ there exists $n$ such that $I\_n\subset J\_m$ and $x\restriction I\_n=y\restriction I\_n$.
2. (12.1) If $A\subset 2^\omega$ is null, then there exists a closed set $K\subset 2^\omega\setminus A$ with the property that whenever $V\_s\cap K\neq\emptyset$ we have $V\_s\cap K$ is nonnull.  
   Hint: First show that there exists a closed set $C\subset 2^\omega\setminus A$ which is non-null. Let $D$ be the union of all basic open sets $V\_s$ such that $m(V\_s\cap C)=0$, and show that $m(D)=0$. Finally let $K=C\setminus D$ and show that $K$ has the desired properties.]

## Week 6 (Due Tuesday, October 6)

1. (9.1) Show that there is a homeomorphism between co-countable subsets of $\mathbb R$ and $2^\omega$.
2. (9.2) For $V\_s$ a basic open set of $2^\omega$, let $m(V\_s)=2^{-\abs{s}-1}$. Then $m$ extends to a measure on the Borel sets of $2^\omega$ (take this for granted). Show that there is a measure-preserving bijection between $[0,1]$ and $2^\omega$, after possibly throwing away countable subsets of each.
3. (10.1) Find a morphism behind the proof of the inequality $non(\mathcal I)\leq cof(\mathcal I)$ (Lemma 8.5). Check that it is dual to a morphism behind the inequality $add(\mathcal I)\leq cov(\mathcal I)$.
4. (10.2) Find a morphism behind the proof of the inequality $\mathfrak b\leq non(\mathcal M)$ (Theorem 9.4). Check that it is dual to a morphism behind the inequality $cov(\mathcal M)\leq\mathfrak d$.

## Week 5 (Due Tuesday, September 29)

1. (7.2) Find an example of a meager subset of $\omega^\omega$ which is not in $\mathcal K\_\sigma$.
2. (7.3) Let $X$ be the space $\mathbb R^\omega$ with the product topology. Decide whether $X$ is $\sigma$-compact.
3. (8.1) Show that $\mathrm{cof}(\mathcal K\_\sigma)=\mathfrak d$.
4. (8.2) Let $\mathcal I$ be the ideal of countable subsets of $\mathbb R$. Find the values of the four cardinal characteristics of $\mathcal I$.

## Weeks 3-4 (Due Tuesday, September 22)

1. (5.2) Prove the well-ordering principle: If $A$ is any set, then there exists a binary relation $\leq$ which is a well-order of $A$. [Use Zorn's Lemma!]
2. (5.3) If $A$ is an infinite set, show that $\abs{A}$ is equal to $\aleph\_\alpha$ for some ordinal $\alpha$.
3. (6.2) Give an example of an open subset of $\omega^\omega$ which is not closed.
4. (6.3) Show that $\omega^\omega$ is homeomorphic to its product with itself $\omega^\omega\times\omega^\omega$.

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