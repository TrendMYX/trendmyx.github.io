---
title: "Random Gradient Hyper-heuristics Can Learn to Escape Local Optima in Multimodal Optimisation"
collection: publications
category: conferences
permalink: /publication/conference-1
date: 2025-03-19
venue: 'GECCO'
excerpt: 'Accepted by the Theory track'
paperurl: 'https://gecco-2025.sigevo.org/Accepted-Papers#&sort[wptrackerlist23-1]=0-1'
---

Abstract: Selection hyper-heuristics (SHHs) select from a set of low-level heuristics which to apply during the optimisation process. One such approach, namely the random gradient SHH, which continues to apply a randomly selected heuristic as long as it remains successful, has been shown to be able to effectively select heuristics leading to optimal expected runtimes on a range of unimodal functions.

In this work, we extend the analysis of the  random gradient SHH to multimodal optimisation problems to assess their performance at escaping from local optima. 
We consider the **TwoRates** benchmark function which includes several consecutive local optima separated by gaps of two alternating different sizes. 

The function was recently introduced to assess the performance of the *flex-EA* that uses an archive to store and re-apply the two most suitable Randomized Local Search (RLS*k*) operators to make the jumps of different lengths.
We show that the SHH can optimise the function considerably faster by identifying and consecutively re-applying  the single  best heuristic to overcome all of the local optima. 
This performance also holds when the set of low-level heuristics contains all the *n* possible RLS*k* operators, where *n* is the problem size.