For the input {1, 2, 3, 4}, the output is [24, 12, 8, 6] that is 
At index 0 → product of [2, 3, 4] = 24
At index 1 → product of [1, 3, 4] = 12
At index 2 → product of [1, 2, 4] = 8
At index 3 → product of [1, 2, 3] = 6
to find the length of the array we have to declARE a variable n and its its type is array of int 
we have to declare a variable with name result and type array of int
we have to declare two another variables i and j type int nad their value is 0 initially
we have to take a variable name product and initialize type int and value 1
i starts at 0 and goes up to n - 1
It represents the current element for which you are calculating the product.
When i = 0, you are calculating the product of all elements except nums[0].
When i = 1, you are calculating the product of all elements except nums[1].
j starts at 0 and goes up to n - 1
The inner loop goes through all elements j = 0, 1, 2, 3.
Used to loop through all elements and multiply them, except when j == i.
They work together to ensure that for each element in the array, you multiply all other elements and skip the one at the current index.
if j is not equal to i, it multiplies nums[j] into product.
This way, all elements except nums[i] are multiplied.
finally Stores the calculated product for index i in the result array.
Returns the final array after the loops are done.
