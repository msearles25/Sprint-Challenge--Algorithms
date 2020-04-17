#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) just one simple loop


b) O(n^2) a loop nested in another loop


c) O(n) because the input of a bunny stays linear, it only adds one more function call per bunny.

## Exercise II

Divide the floors in half, pick the highest floor in the lower half, if the egg doesn't break then move onto the upper half of floors because it didn't contain floor f. Once in the upper half split it in half test the highest floor in the lower half of those floors and continue until floor f is found. 

The runtime complexity of this would be O(log n) because each time you'll be splitting the floors in half.