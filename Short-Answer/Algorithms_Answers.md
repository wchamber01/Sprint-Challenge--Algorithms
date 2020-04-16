#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)

b)

c)

## Exercise II

I would use something like a merge sort algorithm.

1. Split the array in half.
2. Drop an egg.
3. If the egg breaks from the mid-point then you are too high and need to start looking at the floors on the left side of the array otherwise too low and need to look at the floors on the right side of the array.
4. Use recursion to continue splitting which ever half of the array we are in (left or right) and drop another egg at each split until we have reached floor "f".

5. The runtime complexity of merge sort is O(n log(n))
