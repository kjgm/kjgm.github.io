---
title: "Bachelor Honours Project 2022-2024"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/bhp-brita
#venue: "TU Delft"
date: 2024-07-01
#location: "Delft"
---

Supervision of the bachelor honours project of *Catalin Brita*, resulting in a [publication at AAAI-25](https://kjgm.github.io/publication/2025_contree).


Optimal Classification Trees for Continuous Feature Data Using Dynamic Programming with Branch-and-Bound
======
By: Catalin Brita

**abstract** Computing an optimal classification tree that provably maximizes training performance within a given size limit, is NP-hard, and in practice, most state-of-the-art methods do not scale beyond computing optimal trees of depth three. Therefore, most methods rely on a coarse binarization of continuous features to maintain scalability. We propose a novel algorithm that optimizes trees directly on the continuous feature data using dynamic programming with branch-and-bound. We develop new pruning techniques that eliminate many sub-optimal splits in the search when similar to previously computed splits and we provide an efficient subroutine for computing optimal depth-two trees. Our experiments demonstrate that these techniques improve runtime by one or more orders of magnitude over state-of-the-art optimal methods and improve test accuracy by 5% over greedy heuristics.
