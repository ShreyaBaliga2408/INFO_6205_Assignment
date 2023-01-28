TASK:
Solve 3-SUM using the Quadrithmic, Quadratic, and quadraticWithCalipers approaches, as shown in skeleton code in the repository.


Approach:
For Cubic:
Implementation of ThreeSum which follows the brute-force approach of testing every candidate
in the solution-space.The array provided in the constructor may be randomly ordered.
* Construct a ThreeSumCubic on a.
* @param a :an array.
For Quadratic:
Implementation of ThreeSum which follows the approach of dividing the solution-space into
* N sub-spaces where each sub-space corresponds to a fixed value for the middle index of the
three values.
* Each sub-space is then solved by expanding the scope of the other two indices outwards from
the starting point.
* Since each sub-space can be solved in O(N) time, the overall complexity is O(N^2).
* Construct a ThreeSumQuadratic on a.
* @param a :a sorted array.
* Get a list of Triples such that the middle index is the given value j.
* @param j :the index of the middle value.
* @return a Triple
For Quadratic with Calipers:
Implementation of ThreeSum which follows the approach of dividing the solution-space into
* N sub-spaces where each sub-space corresponds to a fixed value for the middle index of the
three values.
* Each sub-space is then solved by expanding the scope of the other two indices outwards from
the starting point.
* Since each sub-space can be solved in O(N) time, the overall complexity is O(N^2).
The array provided in the constructor MUST be ordered.
* Construct a ThreeSumQuadratic on a.
* @param a: a sorted array.
* Get a list of Triples such that the middle index is the given value i.
* @param a : a sorted array of ints.
* @param i : the index of the first element of resulting triples.
* @param function : a function which takes a triple and returns the comparison of sum of the
triple with zero.
* @return a Triple




Relationship Conclusion: It can be observed from the results of the benchmark test:
In the worst case scenario which happens when we generate all possible triplets and compare
the sum of every triplet with the given value and therefore, runs in cubic time: O(n^3).
In the average and best case scenario which follows the approach of dividing the solution-space
into N sub-spaces where each sub-space corresponds to a fixed value for the middle index of
the three values. Each sub-space is then solved by expanding the scope of the other two
indices outwards from the starting point. The array provided must be sorted.Since each
sub-space can be solved in O(N) time, the overall complexity is O(N^2).
