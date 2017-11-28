# freeCodeCampAlgorithmCourse

## Journey: Attempt to complete the algo course in FreeCodeCamp.Org
Notes:

**UPDATE Nov 28th 2017:**
Felt really good to complete line 285 - 296.  I wrote the steps I need and was able to complete the task for every steps.  Its not always like that but when the workflow works as planned IT MAKES SENSE coding the way its coded.  

//plan:
	//push the value in the array
	//sort it
	//get its index value
	//return it
    
    Heres the execution:
    
    function getIndexToIns(arr, num) {
	  
	  const addNum = arr.push(num);
	  console.log(arr);
	  arr.sort(function(a,b){
	  	return a - b;
	  })
	  console.log(arr.indexOf(num));
	  return arr.indexOf(num);
	}
	getIndexToIns([40, 60], 50);


**UPDATE Nov 28th 2017:**
Lesson to take from - function bouncer(arr); (line 253 at the moment) that the expression that is passed, when returned it only returns true values from the array that the expression represents. 


**UPDATE Nov 27th 2017:**
I learned that my code works for  '_Largest Number in an Array' - challenge_.    **BUT** I need to empty the array inside the function.  This way the function would work at any sample provided.  My solution only works on the given test sample but will not work again on other samples.  By declaring the variable for empty array inside the function, I am clearing the array and is able to be used again.

This has something to do with scopes.  By declaring variable locally, I am able to use this variable as part of the function.  Everytime I call the function, it starts as en empty array.  Cool stuff!
