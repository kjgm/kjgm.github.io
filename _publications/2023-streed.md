---
title: "Necessary and Sufficient Conditions for Optimal Decision Trees Using Dynamic Programming"
collection: publications
category: highlights
permalink: /publication/2023_streed
excerpt: 'We prove necessary and sufficient conditions for the use of DP for optimal decision trees and provide a framework STreeD that can optimize trees for a variety of objectives and constraints.'
date: 2023-12-31
venue: 'Advances in NeurIPS-23'
#slidesurl: 'tbd'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2023/file/1d5fce9627e15c84db572a66e029b1fc-Paper-Conference.pdf'
citation: 'Van der Linden, J. G. M., de Weerdt, M. M., & Demirović, E. (2023). &quot;Necessary and Sufficient Conditions for Optimal Decision Trees Using Dynamic Programming.&quot; <i>Advances in NeurIPS-23</i>, 9173-9212.'
---

Global optimization of decision trees has shown to be promising in terms of accuracy, size, and consequently human comprehensibility. However, many of the methods used rely on general-purpose solvers for which scalability remains an issue.Dynamic programming methods have been shown to scale much better because they exploit the tree structure by solving subtrees as independent subproblems. However, this only works when an objective can be optimized separately for subtrees.We explore this relationship in detail and show the necessary and sufficient conditions for such separability and generalize previous dynamic programming approaches into a framework that can optimize any combination of separable objectives and constraints.Experiments on five application domains show the general applicability of this framework, while outperforming the scalability of general-purpose solvers by a large margin.