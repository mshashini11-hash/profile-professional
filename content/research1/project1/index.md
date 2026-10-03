---
title: "Quantum Low-Dimensional Topology"
layout: "research1/single-content"
image: "/uploads/project1.png"
summary: "Quantum invariants of 3-manifolds and the generalized Turaev–Viro volume conjecture."
weight: 1

papers:
  - key: "turaev1992state"
    authors: "Turaev, V. G. and Viro, O. Ya."
    title: "State sum invariants of 3-manifolds and quantum 6j-symbols"
    journal: "Topology"
    year: 1992
    url: "https://doi.org/10.1016/0040-9383(92)90015-A"

  - key: "reshetikhin1991invariants"
    authors: "Reshetikhin, N. and Turaev, V. G."
    title: "Invariants of 3-manifolds via link polynomials and quantum groups"
    journal: "Invent. Math."
    year: 1991
    url: "https://doi.org/10.1007/BF01239527"

  - key: "kirby19913"
    authors: "Kirby, R. and Melvin, P."
    title: "The 3-manifold invariants of Witten and Reshetikhin–Turaev for sl(2,C)"
    journal: "Invent. Math."
    year: 1991
    url: "https://doi.org/10.1007/BF01232277"

  - key: "kauffman1994temperley"
    authors: "Kauffman, L. H. and Lins, S."
    title: "Temperley–Lieb recoupling theory and invariants of 3-manifolds"
    journal: "Princeton University Press"
    year: 1994

  - key: "turaev2010quantum"
    authors: "Turaev, V. G."
    title: "Quantum invariants of knots and 3-manifolds"
    journal: "de Gruyter"
    year: 2010

  - key: "chen2018volume"
    authors: "Chen, Q. and Yang, T."
    title: "Volume conjectures for the Reshetikhin–Turaev and the Turaev–Viro invariants"
    journal: "Quantum Topol."
    year: 2018
    url: "https://doi.org/10.4171/QT/111"

  - key: "detcherry2018turaev"
    authors: "Detcherry, R., Kalfagianni, E. and Yang, T."
    title: "Turaev–Viro invariants, colored Jones polynomials, and volume"
    journal: "Quantum Topol."
    year: 2018
    url: "https://doi.org/10.4171/QT/120"

  - key: "detcherry2020gromov"
    authors: "Detcherry, R. and Kalfagianni, E."
    title: "Gromov norm and Turaev–Viro invariants of 3-manifolds"
    journal: "Ann. Sci. Éc. Norm. Supér. (4)"
    year: 2020
    url: "https://doi.org/10.24033/asens.2449"

  - key: "ohtsuki2016asymptotic"
    authors: "Ohtsuki, T."
    title: "On the asymptotic expansion of the Kashaev invariant of the 5₂ knot"
    journal: "Quantum Topol."
    year: 2016
    url: "https://doi.org/10.4171/QT/83"
---

> The whole theory has been, to a great extent, inspired by ideas that arose in theoretical physics. … The development of this subject shows once more that physics and mathematics intercommunicate and influence each other. — Vladimir G. Turaev

## Overview

My research is in **low-dimensional topology**, with an emphasis on 3-manifolds and links. My thesis work lies in **quantum topology**, a field that originated with the discovery of the Jones polynomial and ideas from theoretical physics. It is built around *quantum invariants* and structures known as *topological quantum field theories (TQFTs)*.

The central aim of my thesis is to understand **how quantum invariants reflect the geometry of a 3-manifold.** Here the geometry comes from Thurston's geometrization theorem, under which every 3-manifold can be cut along spheres and tori into geometric pieces. On the quantum side, I study the **Turaev–Viro invariants**, introduced through a state-sum model on a triangulation of a 3-manifold. The *generalized Turaev–Viro volume conjecture* makes this connection precise: it predicts that the large-level growth rate of these invariants recovers the simplicial volume of the manifold. This is the 3-manifold analogue of the Kashaev and Murakami–Murakami volume conjecture for knots; it was formulated by Chen and Yang for hyperbolic manifolds and extended to all 3-manifolds by Detcherry and Kalfagianni.

My thesis establishes the conjecture for several large classes of 3-manifolds, using three different sets of tools: **analytic estimates**, **TQFT methods**, and **Ohtsuki's saddle-point method**, supported by computer experiments in Python.

## The volume conjecture

Let $M$ be a compact oriented 3-manifold with empty or toroidal boundary, let $r \geq 3$ be odd, and let $TV_r(M, q)$ denote the $SO(3)$ Turaev–Viro invariants. The **simplicial volume** $\mathrm{Vol}(M)$ is the sum of the hyperbolic volumes of the hyperbolic pieces in the JSJ decomposition of $M$. Set

$$LTV(M) := \limsup_{r \to \infty,\ r \text{ odd}} \frac{2\pi}{r} \log \left| TV_r\!\left(M, e^{2\pi i / r}\right) \right|.$$

**Conjecture (Generalized Turaev–Viro Volume Conjecture).** For every compact orientable 3-manifold $M$ with empty or toroidal boundary, $LTV(M) = \mathrm{Vol}(M)$.

---

## Project 1: Seifert fibered 3-manifolds and the volume conjecture

*Single-author paper.* [arXiv:2504.10682](https://arxiv.org/abs/2504.10682) · Submitted to the *International Journal of Mathematics*

Using analytic tools, I proved the volume conjecture for large families of oriented **Seifert fibered 3-manifolds** with empty or non-empty boundary, by studying the $SO(3)$ Turaev–Viro invariants at $q = e^{2\pi i/r}$ and their asymptotic behavior as $r \to \infty$. Starting from Hansen's explicit formula for the Witten–Reshetikhin–Turaev invariants of the double $D(M)$, I found a condition on the Seifert invariants under which almost all terms of the invariants vanish. This makes the computations tractable and gives evidence for why the conjecture is formulated using a $\limsup$ rather than a $\lim$: the invariants vanish for infinitely many $r$, so the growth rate is attained only along a subsequence.

The result covers, for example, Seifert fibered manifolds whose exceptional fibers have pairwise coprime multiplicities, as well as complements of links with zero simplicial volume in these manifolds.

---

## Project 2: Seifert cobordisms and the Chen–Yang volume conjecture

*Joint with Renaud Detcherry and Efstratia Kalfagianni.* [arXiv:2505.01546](https://arxiv.org/abs/2505.01546) · Submitted to the *Journal of the London Mathematical Society*

Most results in this area rely on direct analytic estimates. Since the Witten–Reshetikhin–Turaev invariants carry the structure of a TQFT, it is natural to ask whether that structure, together with 3-manifold topology, can replace brute-force analysis. We studied how the conjecture behaves when a Seifert fibered manifold $S$ is glued to a manifold $M$ with toroidal boundary. Decomposing $S$ into elementary cobordisms and bounding the operator norms of the associated TQFT maps, we showed that **the volume conjecture is closed under this gluing operation.** As applications, the conjecture holds for:

- all oriented Seifert fibered 3-manifolds with non-empty boundary, and closed ones admitting an orientation-reversing involution;
- large classes of plumbed (graph) 3-manifolds with boundary;
- iterated satellites of the figure-eight knot with torus-link patterns, where $LTV = \mathrm{Vol} \approx 2.0298832$.

---

## Project 3: Gluing figure-eight knot complements (in preparation)

*Joint with Ka Ho Wong and Efstratia Kalfagianni.*

Every extension of Ohtsuki's method so far concerns surgeries or fillings on a single knot complement, so manifolds obtained by gluing two hyperbolic knot complements are a natural next step. Let $M_p$ be the closed 3-manifold obtained by gluing two figure-eight knot complements along their boundary tori by $p$ positive Dehn twists, so that $\mathrm{Vol}(M_p) = 2\,\mathrm{Vol}(4_1) \approx 4.0598$. Using Ohtsuki's method (Poisson summation and multivariable saddle-point analysis), we obtained the asymptotic expansion of the invariants and **proved the volume conjecture for $M_p$ for every $p \in \mathbb{Z}$.**

A Python implementation I developed, which computes the growth rate for $r$ up to 20,000 in under a minute, confirms the result. It also gives evidence for the figure-eight/trefoil gluing, where one piece is Seifert fibered: there, the growth rate comes only from the hyperbolic piece.

| $p$ | −3 | −2 | −1 | 0 | 1 | 2 | 3 |
|---|---|---|---|---|---|---|---|
| $4_1 \cup 4_1$ | 4.0618976 | 4.0619119 | 4.0619212 | 4.0619244 | 4.0619212 | 4.0619118 | 4.0618973 |
| $4_1 \cup 3_1$ | 2.0297096 | 2.0297112 | 2.0283336 | 2.0297131 | 2.0283002 | 2.0297125 | 2.0297122 |

*Computed growth rates at $m = 10{,}000$ (where $r = 2m+1$). Targets: $2\,\mathrm{Vol}(4_1) = 4.0597664$ (top row) and $\mathrm{Vol}(4_1) = 2.0298832$ (bottom row).*

---

## Future directions

**Closed Seifert fibered manifolds and lens spaces.** For general closed Seifert fibered 3-manifolds, including lens spaces and small Seifert fibered spaces, the conjecture remains open. I plan to develop an approach that simplifies the invariants directly, without passing to the double, starting with small Seifert fibered manifolds with three exceptional fibers.

**Hyperbolic cobordisms.** Can the TQFT operator methods from Project 2 be pushed to gluings along hyperbolic pieces, which carry volume and must add to the growth rate? Can the argument be extended to Seifert pieces with a single boundary component?

**Beyond the figure-eight knot.** Can Ohtsuki's method be adapted to prove the mixed figure-eight/trefoil case, and can the figure-eight knot be replaced by other hyperbolic knots, such as the $5_2$ knot?

**Computation and software.** I plan to release my code as a documented open-source package for Reshetikhin–Turaev and Turaev–Viro invariants of gluings at large $r$, and to use it for systematic experiments where no theorem exists yet. This work is well suited to undergraduate and beginning graduate projects: the invariants are elementary to define, and the results can be checked immediately against geometry.

**Quantum computing.** Quantum invariants provide important mathematical structures for quantum computing: topological objects can represent quantum states, and operations such as braiding can represent quantum computations. In the longer term, I aim to use quantum invariants to study topological quantum computers, particularly systems based on anyons and braiding, and, conversely, to explore how quantum-computing techniques can provide new tools for computing difficult quantum invariants.
