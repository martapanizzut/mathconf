page-title: Developments in Algorithmic, Discrete and Tropical Geometry
---
:::{style="width: 70%; margin: 0 auto;"}

## Titles and abstracts of poster presentations

**Ansgar Freyer (FU Berlin) - Bounds on the lattice width of convex bodies with few interior points**

The classical flatness theorem states that the lattice width of a convex body without interior lattice points is bounded by a constant depending only on the dimension. Similarly, a convex body with volume at most 1 is known to have bounded lattice width. Our goal is to bridge these two problems by studying bounds on the lattice width of convex bodies with a bounded, but positive, number of interior lattice points. While there are good asymptotic bounds available, there is little knowledge about the exact values of the upper bounds in such problems. In the plane, the flatness problem was fully settled by Hurkens, while Makai and Fejes Toth solved the volumetric problem. We show that the lattice width of a planar convex body with at most one interior lattice point is uniquely maximized by the third dilate of an empty lattice triangle. As a corollary, we obtain an isominwidth inequality for the lattice point enumerator. That is, among convex bodies that contain the origin in their interior, the ratio w^2 / i, where w is the lattice width and i is the number of interior points, is maximized by the third dilate of an empty triangle. This is joint work with Gennadiy Averkov, Giulia Codenotti and Kyle Huang.

**Oskar Henriksson (MPI CBG) - Tropical root bounds and homotopies**

Accurate upper bounds on the number of roots of a polynomial system play a key role in numerical algebraic geometry. We develop a tropical root-counting strategy for sharpening the classical BKK bound for parametrized polynomial systems with dependencies among the coefficients, which also gives an algorithm for constructing generalized polyhedral homotopies. As a case study, we use steady state systems from chemical reaction network theory, for which our tropical root bounds can be shown to be generically sharp. This is based on joint works with Elisenda Feliu, Paul Helminck, Yue Ren, Benjamin Schröter and Máté Telek.



**Kyle Huang (BTU Cottbus) - UniTriSat: Unimodular triangulations via SATISFIABILITY**

Given a lattice polytope, it is natural to ask if it has a unimodular triangulation. Unimodular triangulations have connections to toric geometry, tropical geometry, and enumerative combinatorics, while also being an interesting property in their own right, for various classes of lattice polytopes. With the Julia package UniTriSat, we present a new algorithm for computing unimodular triangulations and regular unimodular triangulations, via translation to a SATISFIABILITY problem. A QuickStart guide can be found at [github.com/krhuang/UniTriSat](https://github.com/krhuang/UniTriSat). 

**Aryaman Jal (Ruhr-Uni­ver­si­tät Bo­chum) - Rook matroids and log-concavity of P-Eulerian polynomials**

We introduce a new family of matroids whose bases correspond to certain restricted rook placements on skew-shaped boards. We study these rook matroids and relate them precisely to transversal matroids, lattice path matroids, and positroids. We end by relating these objects to linear extensions of posets and by doing so, make progress on the log-concavity consequence of the Neggers-Stanley conjecture in algebraic combinatorics.

**Niels Lindner (ZIB) - Discrete Geometry and Tropical Convexity for Public Transport Optimization**

Planning and operating public transportation systems is an intricate task. Solving the resulting scheduling and routing problems on a real-world scale requires careful mathematical modeling and tailored algorithmic techniques. We will present approaches to passenger routing and timetable optimization that are inspired by discrete-geometric methods, making use of polytropes, zonotopes, and tropical polynomials.


**Dante Luber (Padeborn) - Minuscule Coxeter Dressians**

Matroids admit a characterization as (0,1)-polytopes with edge directions in the type A root system. In this case, edges capture "symmetric exchange" between bases. Regular matroidal subdivisions of (Type A)-matroid polytopes are well studied. In particular, they are closely related to a tropical prevariety known as the Dressian, which is a subfan of the secondary fan of a given matroid polytope. Coxeter matroids generalize usual matroids, and can be characterized in terms of polytopes with edge directions in root systems beyond type A. Coxeter matroids which are said to be "minuscule" and possess the "strong exchange" property are the most honest incarnations of usual matroids outside type A. We will discuss subdivisions of minuscule Coxeter matroid polytopes, and study tropical prevarieties which (in most cases) capture subdivisions into cells which possess the strong exchange property.

**Francesco Nowell (TU Berlin) - Polyhedral Geometry of Max-Linear Conditional Independence**

The conditional independence (CI) relation of a distribution in a max-linear Bayesian network is fully determined by the combinatorics of critical paths in the underlying weighted graph. We call these CI structures maxoids, and prove that every maxoid can be obtained from a transitively closed weighted DAG. We show that the stratification of generic weight matrices by their maxoids yields a polyhedral fan which is the normal fan of the Minkowski sum of the Newton polytopes of path polynomials in the graph. The derived constructions and results form the basis for computational approaches to problems of enumeration and conditional independence implication.

**Arnau Padrol (Universitat de Barcelona) - The graph of (implicit) edge dependencies and indecomposability**

A polytope is called indecomposable if it cannot be expressed (non-trivially) as a Minkowski sum of other polytopes. This poster introduces the graph of (implicit) edge dependencies and uses it to state a new indecomposability criterion that unifies and generalizes most of the previous techniques. One of our main applications is providing new indecomposable deformed permutahedra that are not matroid polytopes.


**Diego A. Robayo Bargans (RPTU Kaiserslautern) - Enumeration of geometric Weierstrass points of metric graphs**

A classical result states that on a smooth algebraic curve of genus $g$ the number of Weierstrass points, counted with multiplicity, is g^3-g. We use tropical covers to introduce the notion of geometric Weierstrass points of metric graphs and show that a generic metric graph of genus g has g^3-g geometric Weierstrass points counted with multiplicity. The employed methods also provide a new proof of the existence of Weierstrass points on metric graphs of genus bigger than or equal to 2. 

**Leonard Schmitz - Signature tensors in OSCAR**

We introduce signatureTensors, a new package for computing signature
tensors of paths and membranes in the open-source computer algebra system
OSCAR. Highlights of our work include implementations of Lie group
barycenters and efficient algorithms for tensor learning. We present
several practical examples from geometric statistics, feature extraction,
and computational algebraic geometry. This is joint work with Gabriel
Riffo (TU Berlin).


**Ayush Kumar Tewari (RICAM, Linz) - On the Genus of One Degree of Freedom Planar Linkages via Tropical Geometry**

We focus on studying the configuration spaces of graphs realised in C^2, such that
the configuration space is, after normalisation, one dimensional. If this is the case, then the
configuration space is, generically, a smooth complex curve, and can be seen as a Riemann
surface. The property of interest is the genus of this curve. Using tropical geometry,
we give an algorithm to compute this genus. Using an implementation in Python we give
various examples. (based on joint work with Josef Schicho and Audie Warren) 


