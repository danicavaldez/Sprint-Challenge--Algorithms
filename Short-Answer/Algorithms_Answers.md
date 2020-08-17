#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Run time complexity is O(n) and increases proportionally to size of n.

# O(1 + n * 1) --> Remove constants --> O(n)


b) Run time complexity is O(n log n)
  
  # O(1) + O(n) * O(log n) * O(1 + 1) --> Drop constants --> O(n) * O(log n) --> O(n log n)


c) Run time complexity is O(n)
  
  # O(1) + O(n) --> Drop constants --> O(n)

## Exercise II

I would first initialize min/max floor, min_floor = 0, max_floor = n. From here we can find the mid point (min_floor + max_floor) // 2, then drop the egg. If the egg doesn't break, then we know we need to move higher, find the new mid-point and repeat the process. If the egg does break, we will move lower, find the new mid-point and repeat the process.

Since we are going through this process of elimination by halves, this would be a run time of O(log n).


