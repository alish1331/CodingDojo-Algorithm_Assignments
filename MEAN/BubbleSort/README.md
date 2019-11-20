<h1>Bubble Sort</h1>
<h2>Objectives:</h2>
<p>1. Familiarity with nested loops.</p>
<p>2. Familiarity with a classic sorting algorithm./p>
<hr>

<p>Google CEO Eric Schmidt once asked Senator Barack Obama what the best way to sort a million 32-bit integers would be. Obama responded with,
"I think the bubble sort would be the wrong way to go."
Maybe it isn't the most efficient sort out there, but there are times when it is an appropriate choice!</p>

It's called Bubble Sort because we can imagine we are sliding a bubble along the array. 
<p>⬩ The bubble encompasses two neighboring values. </p>
<p>⬩ If the larger number is to the left, we swap those values. </p>
<p>⬩ Then we slide the bubble over one position. </p>
<p>⬩ Once the bubble reaches the end of the array, we know that the largest value is in its proper position.</p>
<p>⬩ We can then repeat the process for all the values except for the last value, since we know that it is already in place.</p>
<p>⬩ And then we'll do it again, and again, and again, until we know all values are in their proper positions. </p>

<h3>BONUS 1:</h3> Imagine you had to watch the gif above sort an array with 8000 elements - 1000x more elements than it currently has. How long would that take? Would it take 1000 times longer? No, much much worse! It would take 1000^2 times longer, or 1,000,000 times longer! But what if the array was already sorted, or very close to sorted? Bubble sort has the advantage that we may simultaneously detect whether the array is already sorted as we're sorting. If so, we may terminate the algorithm early. This is known as a fast exit. Implement a fast exit in your bubble sort.

<h3>BONUS 2:</h3> Big O Notation is how we express the time and space complexities of our algorithms. Big O is used to describe the worst case scenario of the algorithm - for example, the absolute maximum amount of time required to run the algorithm. However, we cannot put a number on how long the algorithm would take. The actual time required would be dependent on the inputs provided and the hardware being used to run the algorithm. What we can do is describe how the time or space required would change depending on the inputs. The Big O Time complexity of this algorithm is O(n^2) (read as "O of n squared"). This means that as the array provided gets longer, the amount of time required will experience quadratic growth. That's not very good and is why the bubble sort is often scorned. Only under special circumstances may we do a fast exit and possibly complete in just O(n) time, meaning the time required only increases linearly with the length of the array provided. Take some time to research O(1), O(n), O(n^2), and O(log n). 