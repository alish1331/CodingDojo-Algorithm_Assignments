<h1>User languages and interests</h1>
<h2>Objectives:</h2>
<p>1. Familiarity with moving through JavaScript objects to find relevant data.</p>
<p>2. Essential practice for when we need to sift through data we get from an API.</p>
<p>3. Familiarity with conditionals.</p>
<hr>
Notice that in the code snippet below, we have an array of users. Each user is an object. Each user has the key languages, which is associated with an array of strings. Each user also has the key interests, which is associated with an object. There are varying keys within this interests object, and each of those keys is associated with an array of strings.
<br>
Write a function called userLanguages that accepts an array of users, such as the one shown above. Return a string that lists all the users by first name and last name and the languages that each user knows. Make the string as nicely formatted as possible so that it is easy to read.
<br>
Example: userLanguages(users) returns
<ul>
    <li>Kermit the Frog knows Python, JavaScript, C#, HTML, CSS, and SQL. </li>
    <li>Winnie the Pooh knows Python, Swift, and Java. </li>
    <li>Arthur Dent knows JavaScript, HTML, and Go.</li>
</ul>

<h3>BONUS:</h3> Adjust the userLanguages function to also include what each user's interests are.
<br>
Example: userLanguages(users) returns
<ul>
    <li>Kermit the Frog knows Python, JavaScript, C#, HTML, CSS, and SQL.</li>
    <li>Kermit is also interested in guitar, flute, tap, salsa, Black Mirror, and Stranger Things.</li>
    <li>Winnie the Pooh knows Python, Swift, and Java. </li>
    <li>Winnie is also interested in honey, honeycomb, honeysuckle, and Heffalumps.</li>
    <li>Arthur Dent knows JavaScript, HTML, and Go.</li>
    <li>Arthur is also interested in stars, planets, improbability, tea, and yellow bulldozers.</li>
</ul>
