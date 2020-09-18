#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) O(n), the while loop will run as many times as (n) increases.

b) O(n log n) while quicksorting, the two loops will split, the first loop runs through all of the ns which makes it linear, the second loops operations are increasing at a slower rate than O(n) which makes it O(log n) and O(n) \* O(n log n) = O(n log n)

c) O(n), recursion of n times, basecase and of (n) recursions.

## Exercise II

lowest floor
highest floor is the last number in the list
middle floor cuts the list in half
start at the middle and check if the egg breaks

if the middle floor breaks the egg, set the new height to be half of middle floor. keep checking if egg breaks and repeat slicing in half above or below the middle floor. if the egg doesn't break from the middle floor, set a new height of the building to be the top half. throw egg from new floor repeat the process of moving top or bottom until f is found.

lowest = 0
mid = len(arr) / 2
highest = len(arr) - 1
start at the middle and check if egg breaks
if egg breaks go down and if it doesnt go up
