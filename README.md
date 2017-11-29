# freeCodeCampAlgorithmCourse

## Journey: Attempt to complete the algo course in FreeCodeCamp.Org
Notes:

## **UPDATE Nov 29th 2017:**
**Ceasars Cipher** - 

one of the olders ciphers and most popular.  Each letter is converted to its ROT-13 (Rotated to 13 spaces).  I intentionally left the console.log to remind me later when I review my codes.  In the files pushed, I have the workflow itemized.  

	function rot13(str) { // LBH QVQ VG!
		var ceasar;
		var cipher;
		var arr = [];
		console.log(str);
		for (var i = 0; i < str.length; i++) {
				str[i];
				var given = str.charCodeAt(i);
				console.log(given);
			if (given <= 64) {
				ceasar = given;
				cipher = String.fromCharCode(ceasar).toUpperCase();
				console.log(arr.push(cipher));
			console.log(arr);
			}
			if (given >= 78) {
				console.log("this is given: " + given);
				ceasar = given-13; console.log(ceasar);
				cipher = String.fromCharCode(ceasar).toUpperCase();
				console.log(arr.push(cipher));
				console.log(arr);
			}
			if ((given <= 76) && (given >= 65)){
			
				console.log("this is given: " + given);
				ceasar = given+13; console.log(ceasar);
				cipher = String.fromCharCode(ceasar).toUpperCase();
				console.log(arr.push(cipher));
				console.log(arr);
			}
			if (given == 77) {
			
				console.log("this is given: " + given);
				ceasar = given+13; console.log(ceasar);
				cipher = String.fromCharCode(ceasar).toUpperCase();
				console.log(arr.push(cipher));
				console.log(arr);
			}				
		}	
		var answer = arr.join("");
		console.log(answer);
		return answer;
			
	}					

	// Change the inputs below 	to test
	// rot13("SERR CVMMN!");
	rot13("SERR YBIR?");
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
