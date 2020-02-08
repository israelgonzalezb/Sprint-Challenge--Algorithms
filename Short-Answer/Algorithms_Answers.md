#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(log n^3)


b) O(n^2)


c) O(n-1)

## Exercise II

We should find the halfway point between n and f, and call the midway point j. We would then drop an egg from j-1. If the egg breaks, we'll find the midway point between j and f, and do the same. If the egg doesn't break at j-1, we would try to drop an egg from j+1. If it breaks at j+1, then we know j+1 is f. If it doesn't break at j+1, we'd find the halfway point between n and j, and repeat the algorithm above.

This is similar to binary search, which is O(log n).
