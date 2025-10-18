Algorithm (Step-by-Step in Theory)
Step 1: Declare Variables
int n → stores the number of lines (height.length).
int maxWater → stores the maximum area found so far.
Initialize it to 0.
int i, j → loop variables for iterating through all line pairs.
Step 2: Loop through every pair of lines
Use two nested loops:
The outer loop runs i from 0 to n-1.
The inner loop runs j from i+1 to n-1.
This ensures we check every unique pair (i, j) once.
Step 3: Compute the width
For each pair of lines:
int width = j - i;
Type: int
Meaning: The horizontal distance between the two lines on the x-axis.
Step 4: Compute the height of the container
int h = Math.min(height[i], height[j]);
Type: int
Meaning: The smaller height between the two lines determines how high the water can go.
Step 5: Compute the area
int area = width * h;
Type: int
Meaning: The total area (amount of water) that can be held between line i and line j.
Step 6: Update the maximum area
if (area > maxWater) {
    maxWater = area;
}
Type: int
Meaning: If the current area is greater than the previously stored maximum, update maxWater.
Step 7: After both loops end
Return the maximum area found:
return maxWater;
Type: int
Meaning: If the current area is greater than the previously stored maximum, update maxWater.

