page-title: Developments in Algorithmic, Discrete and Tropical Geometry
---
:::{style="width: 70%; margin: 0 auto;"}

## Titles and abstracts of poster presentations

**Ansgar Freyer (FU Berlin) - Bounds on the lattice width of convex bodies with few interior points**

The classical flatness theorem states that the lattice width of a convex body without interior lattice points is bounded by a constant depending only on the dimension. Similarly, a convex body with volume at most 1 is known to have bounded lattice width. Our goal is to bridge these two problems by studying bounds on the lattice width of convex bodies with a bounded, but positive, number of interior lattice points. While there are good asymptotic bounds available, there is little knowledge about the exact values of the upper bounds in such problems. In the plane, the flatness problem was fully settled by Hurkens, while Makai and Fejes Toth solved the volumetric problem. We show that the lattice width of a planar convex body with at most one interior lattice point is uniquely maximized by the third dilate of an empty lattice triangle. As a corollary, we obtain an isominwidth inequality for the lattice point enumerator. That is, among convex bodies that contain the origin in their interior, the ratio w^2 / i, where w is the lattice width and i is the number of interior points, is maximized by the third dilate of an empty triangle. This is joint work with Gennadiy Averkov, Giulia Codenotti and Kyle Huang.

**Oskar Henriksson (MPI CBG) - Tropical root bounds and homotopies**

Accurate upper bounds on the number of roots of a polynomial system play a key role in numerical algebraic geometry. We develop a tropical root-counting strategy for sharpening the classical BKK bound for parametrized polynomial systems with dependencies among the coefficients, which also gives an algorithm for constructing generalized polyhedral homotopies. As a case study, we use steady state systems from chemical reaction network theory, for which our tropical root bounds can be shown to be generically sharp. This is based on joint works with Elisenda Feliu, Paul Helminck, Yue Ren, Benjamin Schröter and Máté Telek.

**Elena Hoster (Ruhr-Uni­ver­si­tät Bo­chum) - Extending the ab-index**

This poster presents joint work with Christian Stump and Lorenzo Vecchi on the extended ab-index of finite, graded, bounded posets.
The extended ab-index was introduced by Dorpalen-Barry, Maglione, and Stump as the ab-index weighted by the Poincaré polynomial. It is a polynomial in two noncommuting variables whose coefficients are polynomials with nonnegative integer coefficients, and it specializes to several well-known polynomial invariants of posets, including the classical ab-index, the Poincaré polynomial, the Chow polynomial and the chain polynomial.
We show that the extended ab-index not only specializes to the classical ab-index, but can also be fully recovered from it via the omega-transformation, thereby proving a conjecture of Dorpalen-Barry, Maglione, and Stump. The omega-transformation generalizes the c-2d-index of an oriented matroid introduced by Billera, Ehrenborg, and Readdy. A variant of this transformation was studied by Ehrenborg for distributive lattices.
This perspective yields new proofs of structural results for polynomial invariants arising as specializations of the extended ab-index and connects conjectures on real-rootedness within this family.

**Kyle Huang (BTU Cottbus) - UniTriSat: Unimodular triangulations via SATISFIABILITY**

Given a lattice polytope, it is natural to ask if it has a unimodular triangulation. Unimodular triangulations have connections to toric geometry, tropical geometry, and enumerative combinatorics, while also being an interesting property in their own right, for various classes of lattice polytopes. With the Julia package UniTriSat, we present a new algorithm for computing unimodular triangulations and regular unimodular triangulations, via translation to a SATISFIABILITY problem. A QuickStart guide can be found at [github.com/krhuang/UniTriSat](https://github.com/krhuang/UniTriSat). 

**Aryaman Jal (Ruhr-Uni­ver­si­tät Bo­chum) - Rook matroids and log-concavity of P-Eulerian polynomials**

We introduce a new family of matroids whose bases correspond to certain restricted rook placements on skew-shaped boards. We study these rook matroids and relate them precisely to transversal matroids, lattice path matroids, and positroids. We end by relating these objects to linear extensions of posets and by doing so, make progress on the log-concavity consequence of the Neggers-Stanley conjecture in algebraic combinatorics.


**Katarina Krivokuca (FU Berlin) - Upper Bounds on Covering Minima of Convex Bodies**

The covering minima are classical parameters in the Geometry of Numbers, interpolating between the reciprocal of the lattice width and the covering radius of a convex body. They were introduced by Kannan and Lovasz (1988) and further used to obtain the first polynomial bound on the flatness constant. We give two new upper bounds on intermediate covering minima of general convex bodies, with a view towards a conjecture of Codenotti, Santos and Schymura (2021) on the maximal covering radius of a non-hollow lattice polytope.


**Arne Kuhrs (Universität Paderborn) - Buildings and Limits of Tropical Linear Spaces**

Affine Bruhat-Tits buildings are geometric spaces extracting
the combinatorics of algebraic groups. The building of PGL parametrizes
flags of subspaces/lattices in or, equivalently, norms on a fixed
finite-dimensional vector space, up to homothety. The space of seminorms
compactifies the space of norms and admits a natural surjective
restriction map from the Berkovich analytification of projective space.
Inspired by Payne's result that the analytification is the limit of all
tropicalizations, we show that the space of seminorms is the limit of
all tropicalized linear subspaces (as the embedding and the dimension of
the ambient projective space vary). The building is in fact the tropical
linear space associated with the universal realizable valuated matroid,
extending a result of Dress and Terhalle. This is based on joint work
with Luca Battistella, Kevin Kühn, Martin Ulirsch and Alejandro Vargas.
In work with Kevin Kühn we obtain real analogues of our results,
employing the theory of real tropicalizations and analytifications.


**Niels Lindner (ZIB) - Discrete Geometry and Tropical Convexity for Public Transport Optimization**

Planning and operating public transportation systems is an intricate task. Solving the resulting scheduling and routing problems on a real-world scale requires careful mathematical modeling and tailored algorithmic techniques. We will present approaches to passenger routing and timetable optimization that are inspired by discrete-geometric methods, making use of polytropes, zonotopes, and tropical polynomials.


**Dante Luber (Universität Paderborn) - Minuscule Coxeter Dressians**

Matroids admit a characterization as (0,1)-polytopes with edge directions in the type A root system. In this case, edges capture "symmetric exchange" between bases. Regular matroidal subdivisions of (Type A)-matroid polytopes are well studied. In particular, they are closely related to a tropical prevariety known as the Dressian, which is a subfan of the secondary fan of a given matroid polytope. Coxeter matroids generalize usual matroids, and can be characterized in terms of polytopes with edge directions in root systems beyond type A. Coxeter matroids which are said to be "minuscule" and possess the "strong exchange" property are the most honest incarnations of usual matroids outside type A. We will discuss subdivisions of minuscule Coxeter matroid polytopes, and study tropical prevarieties which (in most cases) capture subdivisions into cells which possess the strong exchange property.

**Francesco Nowell (TU Berlin) - Polyhedral Geometry of Max-Linear Conditional Independence**

The conditional independence (CI) relation of a distribution in a max-linear Bayesian network is fully determined by the combinatorics of critical paths in the underlying weighted graph. We call these CI structures maxoids, and prove that every maxoid can be obtained from a transitively closed weighted DAG. We show that the stratification of generic weight matrices by their maxoids yields a polyhedral fan which is the normal fan of the Minkowski sum of the Newton polytopes of path polynomials in the graph. The derived constructions and results form the basis for computational approaches to problems of enumeration and conditional independence implication.

**Arnau Padrol (Universitat de Barcelona) - The graph of (implicit) edge dependencies and indecomposability**

A polytope is called indecomposable if it cannot be expressed (non-trivially) as a Minkowski sum of other polytopes. This poster introduces the graph of (implicit) edge dependencies and uses it to state a new indecomposability criterion that unifies and generalizes most of the previous techniques. One of our main applications is providing new indecomposable deformed permutahedra that are not matroid polytopes.


**Diego A. Robayo Bargans (RPTU Kaiserslautern) - Enumeration of geometric Weierstrass points of metric graphs**

A classical result states that on a smooth algebraic curve of genus $g$ the number of Weierstrass points, counted with multiplicity, is g^3-g. We use tropical covers to introduce the notion of geometric Weierstrass points of metric graphs and show that a generic metric graph of genus g has g^3-g geometric Weierstrass points counted with multiplicity. The employed methods also provide a new proof of the existence of Weierstrass points on metric graphs of genus bigger than or equal to 2. 

**Leonard Schmitz (TU Berlin) - Signature tensors in OSCAR**

We introduce signatureTensors, a new package for computing signature
tensors of paths and membranes in the open-source computer algebra system
OSCAR. Highlights of our work include implementations of Lie group
barycenters and efficient algorithms for tensor learning. We present
several practical examples from geometric statistics, feature extraction,
and computational algebraic geometry. This is joint work with Gabriel
Riffo (TU Berlin).

**Pardis Semnani (University of British Columbia) - Characteristic Imsets for Cyclic Linear Causal Models and the Chickering Ideal**

Two directed graphs are called covariance equivalent if they induce the same set of covariance matrices, up to a Lebesgue measure zero set, on the random variables of their associated linear structural equation models. For acyclic graphs, covariance equivalence is characterized both structurally, via essential graphs and characteristic imsets, and transformationally, through sequences of covered edge flips. However, when directed cycles are allowed, only a transformational characterization of covariance equivalence has been discovered. We consider a linear map whose fibers correspond to the sets of graphs with identical characteristic imset vectors, and study the toric ideal associated to its integer matrix. Using properties of this ideal we show that directed graphs with the same characteristic imset vectors are covariance equivalent. In applications, imsets form a smaller search space for solving causal discovery through linear programming. This is joint work with Joseph Johnson.


**Ayush Kumar Tewari (RICAM, Linz) - On the Genus of One Degree of Freedom Planar Linkages via Tropical Geometry**

We focus on studying the configuration spaces of graphs realised in C^2, such that
the configuration space is, after normalisation, one dimensional. If this is the case, then the
configuration space is, generically, a smooth complex curve, and can be seen as a Riemann
surface. The property of interest is the genus of this curve. Using tropical geometry,
we give an algorithm to compute this genus. Using an implementation in Python we give
various examples. (based on joint work with Josef Schicho and Audie Warren) 


