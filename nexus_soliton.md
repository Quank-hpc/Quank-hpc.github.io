---
layout: default
---

# Library: Nexus-Soliton (NS)

- 15. Nov. 2022

> The NS project was started five years ago during my PhD time. The outputs have generated two major publications for 2D system. One of them is published on [Nature Communication](https://www.nature.com/articles/s41467-018-08204-8).
>
> When two continuous symmetry breaking phase transitions happen consecutively in superfluid system, there is a chance that new phase is made out by fribration of vacua of the first and the second phase transitions. [reference](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.023263)
> This results in composite defects described by relative homotopy groups. Moreoever, the isomorphic relationship of these relative homotopy make composite objects even more compilcate --- they form nexus.
> 1D nexus has been observed expermentally, with a very good coincidence with NS simulations. [read more in paper](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.043356)

|:-------------------------------------------------------------------------------------------|

Libaray NS was developed with [BFGS nonlinear optimization algorithm](https://en.wikipedia.org/wiki/Broyden–Fletcher–Goldfarb–Shanno_algorithm) and [Galekin method of eigen problem](https://en.wikipedia.org/wiki/Galerkin_method). Finite element Discretization is used for numerical system.

The codes was implemented with Matlab and c++. c++ codes will be complied to be dynamic object files (.so files) with suitbale interfaces before Matlab scripts could call them. Programs could run without c++ parts, but a little bit slower. Matlab parfor is used for parallelism, and addtional shell scripts are necessary for running on cluster.

Link of repo:

openaccess data: