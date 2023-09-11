---
title: "Unsaturated Transport Modeling: Random-Walk Particle-Tracking as a Numerical-Dispersion Free and Efficient Alternative to Eulerian Methods"
collection: publications
permalink: /publication/2022-07-06-Henri-and-Diamantopoulos
excerpt: ''
date: 2022-07-06
venue: 'Journal of Advances in Modeling Earth Systems'
paperurl: ''
citation: 'Henri, C. V., & Diamantopoulos, E. (2022). Unsaturated transport modeling: Random-walk particle-tracking as a numerical-dispersion free and efficient alternative to Eulerian methods. Journal of Advances in Modeling Earth Systems, 14, e2021MS002812. https://doi.org/10.1029/2021MS002812'
---

<center>
<a href="Henri_and_Diamantopoulos_2022.pdf">Download link</a>
</center>


Abstract: 
Lagrangian methods, such as the random-walk particle-tracking (RWPT), are often qualified as a potentially valuable alternative to error-prone Eulerian methods for simulating solute transport in unsaturated porous media. Yet, the RWPT method has not yet been validated against - and compared to - currently used Eulerian solutions for simulating solute transport under a range of typical unsaturated conditions. This paper presents a new implementation of the RWPT approach for advective - dispersive transport problems under variably saturated conditions. We first show that, as previously demonstrated for a heterogeneous dispersion tensor, using an interpolation scheme in the RWPT algorithm performs well for problems with abrupt changes in the water content. The new model is then compared against a simple 1D uniform transport problem, for which an analytical solution exist, and against a variety of 1D and 3D numerical solutions using the different Eulerian schemes implemented in Hydrus software suite. Results show that, while the Eulerian solutions significantly suffer from numerical dispersion in case of a coarse spatial discretization of the simulation domain, the new Lagrangian model provides accurate solutions for all problems. Furthermore, RWPT reproduces accurately solute transport for typical unsaturated flow conditions (infiltration, evaporation). Moreover, the Lagrangian model appears to be orders of magnitude faster than its Eulerian alternative to solve a 3D heterogeneous problem. Thus, RWPT should be seen as an attractive, stable and efficient alternative for simulating solute transport in the vadose zone, especially in case of complex and large problems.


