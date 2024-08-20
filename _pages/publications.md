---
layout: page
permalink: /publications/
title: publications
description: 
years: [2024, 2023, 2022]
nav: true
nav_order: 1
---

<div class="publications">


<h1 class="bibliography">Preprints</h1>

{% bibliography -f {{ site.scholar.bibliography }} -q @unpublished --sort_by year, month --order descending, descending %}

<h1 class="bibliography">Journal papers</h1>

{% bibliography -f {{ site.scholar.bibliography }} -q @article --sort_by year, month --order descending, descending %}

<h1 class="bibliography">Theses</h1>

{% bibliography -f {{ site.scholar.bibliography }} -q @thesis --sort_by year, month --order descending, descending %}

</div>

---

# Talks

### 2024
 - Optimality and uniqueness of the D4 root system, <a href="https://euro2024cph.dk/programme/conference-program">EURO2024</a>, Copenhagen, 01-03/07/2024.
 - From approximate to exact optimal solutions to large semidefinite programs, <a href="https://www.tilburguniversity.edu/about/schools/economics-and-management/news-and-events/seminars/operations-research">Operations Research seminar</a>, Universiteit Tilburg, 23/05/2024.
 - Rounding solutions of semidefinite programs, DMO Seminar, TU Delft, 26/01/2024.

### 2023
 - The second step of the Lasserre hierarchy for the kissing number problem, <a href="https://conferences.cirm-math.fr/2892.html">Conference on Symmetry, Stability, and interactions with Computation</a>, CIRM, Marseille, 13/11/2023-17/11/2023.
 - The second step of the Lasserre hierarchy for the kissing number problem, Seminar, Cologne, 07/11/2023.
 - Max Cut and Grothendieck's inequality, Blackboard talk, DMO Blackboard Seminar, TU Delft, 10/10/2023.


### 2022
 - A specialized SDP solver for sums-of-squares problems in discrete geometry, <a href="http://www.mi.uni-koeln.de/opt/three-days-of-computational-methods-for-extremal-discrete-geometry/"> Three days of computational methods for extremal discrete geometry</a>, University of Cologne, K&ouml;ln, 30/11/2022 - 02/31/2022.
 - Solving clustered low-rank semidefinite programs arising in polynomial optimization, Seminar Polynomial Optimization, LAAS-CNRS, Toulouse, 26/09/2022
 - Computations using higher-level correlations of the zeros of the Riemann Zeta-function, <a href="https://event.cwi.nl/semester-programs/2022/PolOpt/indexW1.html"> Workshop on Semidefinite and Polynomial Optimization </a>, CWI, Amsterdam, 29/08/2022 - 02/09/2022.
 - <a href="https://www.esi.ac.at/events/t634/">A specialized SDP solver for sums-of-squares problems in discrete geometry</a>, <a  href="https://www.esi.ac.at/events/e427/">Workshop Optimal Point Configurations on Manifolds</a>, ESI, 10/01/2022 - 21/01/2022, online .

