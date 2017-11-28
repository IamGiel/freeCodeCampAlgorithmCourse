# freeCodeCampAlgorithmCourse

## Journey: Attempt to complete the algo course in FreeCodeCamp.Org
Notes:

**UPDATE Nov 28th 2017:**
As I test the output of the codes in the console, I seem to encounter the same problem with for loops not iterating- Especially when I use for loops and if statements that has a 'return'.  This stops the loop.  To show iteration in the console, I had to move the if statements outside the scope of the for loop, this makes all the variables undefined.

On lines 234 - 250, not sure if its because of ES6 updates, this challenge exemplifies what I mean.  For some reason, Line 240 (if statement) did not need an open and close bracket for the condition inside it to work.  This is also a challenge wherein 'return' stops the loop and is enough to satisfy the solution.


**UPDATE Nov 27th 2017:**
I learned that my code works for  '_Largest Number in an Array' - challenge_.    **BUT** I need to empty the array inside the function.  This way the function would work at any sample provided.  My solution only works on the given test sample but will not work again on other samples.  By declaring the variable for empty array inside the function, I am clearing the array and is able to be used again.

This has something to do with scopes.  By declaring variable locally, I am able to use this variable as part of the function.  Everytime I call the function, it starts as en empty array.  Cool stuff!
