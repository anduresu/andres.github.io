---
title: "Indexed Dynamic Programming to Boost Edit Distance and LCSS Computation"
collection: publications
permalink: /publication/2018-SPIRE
excerpt: 'Conference Talk + Publication. Instance Optimal Edit Distance Algorithm under swap, insert and delete operations.'
date: 2018-10-01
venue: 'Published in SPIRE'
---
There are efficient dynamic programming solutions to the
computation of the Edit Distance from S ∈ [1..σ] n to T ∈ [1..σ] m , for
many natural subsets of edit operations, typically in time within O(nm)
in the worst-case over strings of respective lengths n and m (which is
likely to be optimal), and in time within O(n+m) in some special cases
(e.g., disjoint alphabets). We describe how indexing the strings (in linear
time), and using such an index to refine the recurrence formulas underly-
ing the dynamic programs, yield faster algorithms in a variety of models,
on a continuum of classes of instances of intermediate difficulty between
the worst and the best case, thus refining the analysis beyond the worst
case analysis. As a side result, we describe similar properties for the
computation of the Longest Common Sub Sequence LCSS(S, T ) between
S and T , since it is a particular case of Edit Distance, and we discuss
the application of similar algorithmic and analysis techniques for other
dynamic programming solutions. More formally, we propose a parame-
terized analysis of the computational complexity of the Edit Distance
for various sets of operators and of the Longest Common Sub Sequence
in function of the area of the dynamic program matrix relevant to the
computation.

[Download paper here](https://anduresu.github.io/files/spire2018.pdf)