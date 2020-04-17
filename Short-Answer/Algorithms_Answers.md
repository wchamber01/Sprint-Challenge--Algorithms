#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a)O(n) - Because this is loop whose duration is dependant upon the value of 'n' and will take 'n' arguments.

b) O(n\*log(n)) - In mathematics, the logarithm is the inverse function to exponentiation. That means the logarithm of a given number x is the exponent to which another fixed number, the base n, must be raised, to produce that number x. For every time j doubles the sum increases by 1 which is 0(log(n)). J is the log of the sum. The function also loops through 'n' times until reaching 'n' which is O(n)

c)O(n) - This is a recursive problem. It has a base case. It calls itself. The value changes towards itself i.e. (n-1) each time it recurses.

## Exercise II

Assuming the data is already sorted, I would use something like a binary search.

1. Start at a floor near the middle of the building.
2. Drop an egg.
3. If the egg breaks from the mid-point then you are too high and need to start looking at the floors below otherwise start checking the floors above.
4. Continue to the mid-point of which ever half of the building you are in (top or bottom).
5. Drop another egg.
6. Using recursion, refer back to steps 3 & 4 and continue on until reaching the floor immediately below "f".
7. The runtime complexity of a binary is O(log(n))
