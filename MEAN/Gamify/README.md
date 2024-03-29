<h1>Gamify</h1>
<h2>Objectives:</h2>
<ol>
    <li>Provide a mission for the player to accomplish.</li>
    <li>Provide the logic in the game to determine whether the player accomplishes the mission. </li>
</ol>

<p>Congratulations! We have a map of the Hundred Acre Wood and our characters are greeting us as we visit their homes! Now let's create a mission for the player so that we can truly call this a game.</p>

<p>Let's have the player deliver honey to a particular home. The player will need to gather honey from the bees and then carry that honey to the destination.</p>

<p>First, we will need a way to know if the player is carrying honey. Give the player the attribute of honey and set it to false, so by default, the player is not carrying honey.</p>

<p>Now we'll need a way to change the player's honey status to true. Create a function called pickUp. Invoking pickUp() should change the player's attribute of honey to true, but only if it is called when the player is at the Bees' location. Invoking pickUp() at any other location should log a message that there is no honey at this location.</p>

<p>Next, create a mission for the player. Create the mission by writing a function called mission that randomly selects any of the locations, except for the Bees. This will be the location where the player must deliver the honey. Have mission() invoked immediately and log a message so that the user knows who needs the honey.</p>

<p>Finally, we'll need a way to win! Create a function called drop, which, when invoked at the location determined by mission(), will log a message to let the user know that they've just won! This will also set the player's honey attribute to false, since the player is no longer carrying any honey. If the player invokes drop() when they don't have any honey or if they're not at their destination, log a message to let them know what's wrong.</p>

<ul>
    <li>Add an attribute to the player to track whether the player has honey or not</li>
    <li>Create a mission function so that the user is given a destination</li>
    <li>Create a pickUp function that changes the player's honey status to true if it is invoked when the player is at the bees' location</li>
    <li>Create a drop function that allows the player to deliver honey to the proper destination</li>
</ul>
