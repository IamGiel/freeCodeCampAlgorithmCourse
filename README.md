# freeCodeCampAlgorithmCourse

## Here I tried to complete the algo course in FreeCodeCamp.Org
Notes:

My solution to 'Largest Number in an Array' has completed its task succesfully.  It was not accepted as a correct asnwer until I declared the var that holds empty array locally.  But it works otherwise.  I see this as a possible glitch that perhaps needs to be addressed.

UPDATE: 

So, I learned that my code works for  '_Largest Number in an Array' - challenge_.    **BUT** I need to empty the array inside the function.  This way the function would work at any sample provided.  My solution only works on the given test sample but will not work again on other samples.  By declaring the variable for empty array inside the function, I am clearing the array and is able to be used again.

This has something to do with scopes.  By declaring variable locally, I am able to use this variable as part of the function.  Everytime I call the function, it starts as en empty array.  Cool stuff!
