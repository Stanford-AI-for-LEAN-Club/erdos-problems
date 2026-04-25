\# v10 correction notice for Erdős Problem #278



This correction separates packable-subgraph optimization from the full #278 maximum-coverage objective.



Main corrections:



1\. Packable-subgraph optimization is not the same as full #278 maximum coverage.

2\. Perfect packing still gives exact #278 maxima when the whole support family is perfectly packable.

3\. Weighted graph-link results should be read as exact packable-subgraph / disjoint-construction results, not automatic full #278 maximum theorems.

4\. The old nonuniform clique-link criterion using `c\_i - 2` was incorrect; the corrected triangle-plus-stars construction uses `b\_i - 3` for the star-center capacities.

5\. Arbitrary-weight clique threshold formulas are demoted unless special hypotheses are proved.

6\. The true full-coverage frontier is the one-layer union objective `U\_d(H)`.

