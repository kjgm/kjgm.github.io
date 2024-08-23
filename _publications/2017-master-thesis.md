---
title: "Decision Diagrams for Decomposed Mixed Integer Linear Programs"
collection: publications
category: other
permalink: /publication/2017_master_thesis
excerpt: 'Optimizing mixed-integer linear programs with decision diagrams by decomposing the problem using benders decomposition.'
date: 2017-08-31
venue: 'Master Thesis'
#slidesurl: 'tbd'
paperurl: 'https://repository.tudelft.nl/file/File_ed30abb9-0db3-4865-b421-4ec16017a536'
citation: 'Van der Linden, K. (2017). <i>Decision Diagrams for Decomposed Mixed Integer Linear Programs</i> [Master thesis, Delft University of Technology]. TU Delft Research Repository.'
---

A recent development in the field of discrete optimization is the combined use of (binary) decision diagrams (DD) and branch and bound for optimization. This method has been shown to outperform integer linear programming on several classic problems. The performance of DDs in integer optimization raises the question if this method can be extended to solve mixed integer problems (MIP), because of the prevalence of MIP modelling. This thesis is an effort to answer that question. Currently DD-based optimization does not allow for continuous variables. We propose a method that uses Benders Decomposition to divide MIP problems into a discrete master problem and a continuous subproblem. DD-based optimization is used to solve the master problem. The subproblem can be solved by linear programming. The results presented in this thesis show that our method can be used for MIP problems whose integer variables play a dominant role, and are hard to solve by MIP solvers. An advantage of our method is that it provides feasible solutions as early as the first iteration.