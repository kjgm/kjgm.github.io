---
title: "Optimal Classification Trees for Continuous Feature Data Using Dynamic Programming with Branch-and-Bound"
collection: publications
category: articles
permalink: /publication/2025_contree
excerpt: 'ConTree computes optimal binary classification trees on datasets with continuous features using dynamic programming with branch-and-bound.'
date: 2025-02-27
venue: 'Proceedings of AAAI-25'
#slidesurl: 'tbd'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/33210/35365'
sourceurl: 'https://github.com/consol-lab/contree'
citation: 'Brita, C. E., van der Linden, J. G. M., & Demirović, E. (2025). &quot;Optimal Classification Trees for Continuous Feature Data Using Dynamic Programming with Branch-and-Bound.&quot; <i>Proceedings of AAAI-25</i>, 11131--11139.'
---

Computing an optimal classification tree that provably maximizes training performance within a given size limit, is NP-hard, and in practice, most state-of-the-art methods do not scale beyond computing optimal trees of depth three. Therefore, most methods rely on a coarse binarization of continuous features to maintain scalability. We propose a novel algorithm that optimizes trees directly on the continuous feature data using dynamic programming with branch-and-bound. We develop new pruning techniques that eliminate many sub-optimal splits in the search when similar to previously computed splits and we provide an efficient subroutine for computing optimal depth-two trees. Our experiments demonstrate that these techniques improve runtime by one or more orders of magnitude over state-of-the-art optimal methods and improve test accuracy by 5% over greedy heuristics.

![An example of how ConTree uses similarity to compute lower bounds and skip thresholds](/images/contree-animation.gif)