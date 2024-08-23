---
title: "Piecewise Constant and Linear Regression Trees: An Optimal Dynamic Programming Approach"
collection: publications
category: highlights
permalink: /publication/2024_regression
excerpt: 'We use DP to generate optimal regression trees with constant and (simple) linear regression models in the leaf node. Our method improves scalability by one or more orders of magnitude in comparison to the state-of-the-art.'
date: 2024-07-31
venue: 'Proceedings of ICML-24'
#slidesurl: 'tbd'
paperurl: 'https://openreview.net/pdf?id=rXnBvu5D7i'
citation: 'Van den Bos, M., van der Linden, J. G. M., & Demirović, E. (2024). &quot;Piecewise Constant and Linear Regression Trees: An Optimal Dynamic Programming Approach.&quot; <i>Proceedings of ICML-24</i>.'
---

Regression trees are a human-comprehensible machine-learning model that can represent complex relationships. They are typically trained using greedy heuristics because computing optimal regression trees is NP-hard. Contrary to this standard practice, we consider optimal methods and improve the scalability of optimal methods by developing three new dynamic programming approaches. First, we improve the performance of a piecewise constant regression tree method using a special algorithm for trees of depth two. Second, we provide the first optimal dynamic programming method for piecewise multiple linear regression. Third, we develop the first optimal method for piecewise simple linear regression, for which we also provide a special algorithm for trees of depth two. The experimental results show that our methods improve scalability by one or more orders of magnitude over the state-of-the-art optimal methods while performing similarly or better in out-of-sample performance.