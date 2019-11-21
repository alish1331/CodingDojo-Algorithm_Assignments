<h1>Traveling</h1>
<h2>Objectives:</h2>
<ol>
    <li>Start building a simple game that can be played in the browser's console. </li>
    <li>Create a player object that points to a location on the map. </li>
    <li>Have the player move by changing the player's pointer depending on user input.</li>
</ol>

<p>In the last assignment, we created a map of the Hundred Acre Wood! Now let's use it to start building a simple game. First, our player will need a way to travel around the map. We'll get you started by creating a player object. The player object will have the attribute "location", which will be a pointer to Tigger's home. Assuming that we are using the code in the previous module, the variable tigger points to the location in memory where we stored Tigger's home object. If you did not use the variable tigger, your code may look different </p>

<p>Create a function that will move the player to the north, south, east, or west, depending on the direction provided to it. Call this function move. Have the move function console.log the player's current location so that you can verify that the code is working as expected. If a direction is passed to the move function that does not lead anywhere, have it console.log "You may not go that way!"</p>

<ul>
    <li>Create the player object with the location attribute </li>
    <li>Assign the player's location to the tigger object </li>
    <li>Create the function move, which takes a direction as a parameter</li>
    <li>When the move function is invoked, change the player's location accordingly and log a message</li>
    <li>If the move function is passed an invalid direction, log a message to inform the user</li>
</ul>
