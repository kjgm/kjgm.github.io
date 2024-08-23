---
title: "Optimal Survival Trees: A Dynamic Programming Approach"
collection: publications
category: articles
permalink: /publication/2024_survival_analysis
excerpt: 'We provide the first approach to optimal survival trees (under the proportional hazards assumption).'
date: 2024-02-28
venue: 'Proceedings of AAAI-24'
#slidesurl: 'tbd'
paperurl: 'https://ojs.aaai.org/index.php/AAAI/article/view/29163/30199'
citation: 'Huisman, T., van der Linden, J. G. M., & Demirović, E. (2024). &quot;Optimal Survival Trees: A Dynamic Programming Approach.&quot; <i>Proceedings of AAAI-24</i>, 12680-12688.'
---

Survival analysis studies and predicts the time of death, or other singular unrepeated events, based on historical data, while the true time of death for some instances is unknown. Survival trees enable the discovery of complex nonlinear relations in a compact human comprehensible model, by recursively splitting the population and predicting a distinct survival distribution in each leaf node. We use dynamic programming to provide the first survival tree method with optimality guarantees, enabling the assessment of the optimality gap of heuristics. We improve the scalability of our method through a special algorithm for computing trees up to depth two. The experiments show that our method's run time even outperforms some heuristics for realistic cases while obtaining similar out-of-sample performance with the state-of-the-art.