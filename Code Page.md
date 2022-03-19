# Example of my code

## Below I have pasted my answer to our recent FizzBuzz assignment that I did very well on:



    function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 0; i < 100; i++) {
		displayHTML += "<p>" + i + "</p>";
		
		if(i % 3== 0 && i % 5==0)
		{
			displayHTML+= "FizzBuzz";
		}

		else if(i% 3 == 0 )
		{
			displayHTML += "Fizz";
		}
		else if(i % 5 == 0)	
		{
			displayHTML+= "Buzz";
		}
				
		else{
			continue;
		}
	
	}
	 	
	display.innerHTML = displayHTML

# This is missing the syntax that is required in HTML documents, however it does diplay the function and the logic that I used to complete this assignment.
