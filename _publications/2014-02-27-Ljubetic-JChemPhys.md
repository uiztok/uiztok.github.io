---
title: "Recovering position-dependent diffusion from biased molecular dynamics simulations"
collection: publications
date: 2014-02-27
venue: 'J. Chem. Phys.'
authors: 'Ajasja Ljubetič, Iztok Urbančič, Janez Štrancar'
paperurl: 'https://doi.org/10.1063/1.4866448'
doi: 10.1063/1.4866448
type: 'Paper'
header:
  teaser: #'/images/proj_Labelling2021.jpg'
project: #'nanotox, probes'
---

Abstract
--------
All atom molecular dynamics (MD) models provide valuable insight into the dynamics of biophysical systems, but are limited in size or length by the high computational demands. 
The latter can be reduced by simulating long term diffusive dynamics (also known as Langevin dynamics or Brownian motion) of the most interesting and important user-defined parts 
of the studied system, termed collective variables (colvars). A few hundred nanosecond-long biased MD trajectory can therefore be extended to millisecond lengths in the colvars subspace at a very 
small additional computational cost. In this work, we develop a method for determining multidimensional anisotropic position- and timescale-dependent diffusion coefficients (D) by analysing the 
changes of colvars in an existing MD trajectory. As a test case, we obtained D for dihedral angles of the alanine dipeptide. An open source Mathematica® package, capable of determining and visualizing 
D in one or two dimensions, is available at https://github.com/lbf-ijs/DiffusiveDynamics. Given known free energy and D, the package can also generate diffusive trajectories.