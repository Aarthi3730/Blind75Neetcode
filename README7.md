Step 1: Create an array to store numbers
Type: int[] (integer array)
Variable: numbers
Meaning: stores all the elements entered by the user
Example Value: [2, 7, 11, 15]
Step 2: Input the target sum value
Type: int
Variable: target
Meaning: the value we want two numbers to add up to
Example Value: target = 9
Step 4: Create new array a with 1-based indexing
Type: int[]
Variable: a
Meaning: new array that starts indexing from 1 instead of 0
In Java, array indices normally start from 0.
(Example: numbers[0], numbers[1], etc.)
But the problem requires indices to start from 1.
So, we create a new array a[] with one extra space.
The first element (a[0]) is not used.
Finding Two Numbers Whose Sum Equals Target:
The program uses two nested loops to check all possible pairs of elements.
The outer loop variable i starts from 1 and the inner loop variable j starts from i + 1.
For each pair (a[i], a[j]), the program checks if their sum equals the target.
If the condition is true, the program prints the indices [i, j] and stops.
and it checks remaining by creating an array

Values from the numbers array are copied starting from index 1.
