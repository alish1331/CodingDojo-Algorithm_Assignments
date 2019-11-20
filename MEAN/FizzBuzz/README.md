<h1>Fizz Buzz</h1>
<h2>Objectives:</h2>
<p>1 Use of the modulus operator</p>
<p>2 Familiarity with loops</p>
<p>3 Familiarity with conditionals</p>
<hr>

Create a function called fizzbuzz that accepts a parameter n. Have the function log all the numbers from 1 to n in order with the following exceptions:
<p>⬩ If the number is divisible by both 3 and 5, log "FizzBuzz" instead of the number</p>
<p>⬩ If the number is divisible by 3 but not by 5, log "Fizz" instead of the number</p>
<p>⬩ If the number is divisible by 5 but not by 3, log "Buzz" instead of the number</p>
<p>⬩ Write your code and run it with several examples to ensure it is working as expected. Use the modulus operator!</p>
Example - fizzbuzz(15) would log the following (each element on its own line):
<p><i> 1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz</i></p>

<h3>BONUS 1: Validate the user input. If the function is not passed a positive number, either throw an error or return null.</h3>
Example - fizzbuzz("fifteen") would throw the following error:
<p>⬩ Parameter must be a positive number</p>

<h3>BONUS 2: Rather than have the function log each element, return a nicely formatted string with all the elements. Include commas where appropriate to make it easier to read.</h3>
Example - fizzbuzz(15) would return the following string:
<p><i> 1, 2, Fizz, 4, Buzz, Fizz, 7, 8, Fizz, Buzz, 11, Fizz, 13, 14, and FizzBuzz.</i></p>