# TIC-TAK-TOE

<h4>index.html: This file contains the structure of the project.</h4>
<h4>style.css: This file contains the styling of the application.</h4>
<h4>script.js: This file contains the logic of the game.</h4>

<h4>A tic-tac-toe game requires 9 cells (3x3). Instead of a full blown menu, We will just add a message at the end with the restart button</h4>

<h4>I create a constant variable for our x and o characters. The table under presents combinations of movements for winning the game. These combinations will help us determine if the game is over or not, by checking if any of the combinations match the current gameplay.</h4>

<h4>I used the id tags I assigned in the index.html to save the values of all the board elements, winning message and the restart button. For this I used the JavaScript method getElementById(). For the winning message text element I used the querySelector() method which returns the first element within the document that matches the specified selector. I also used the squared brackets ([]) to target the data-cell attribute.</h4>

<h4>I created a function for starting the game called gameStart(). I set the isPlayer_O_Turn variable to false, meaning the first to play will be an x character. The rest of the function removes all the characters left from previous gameplay. Here I also trigger the events which may happen on our board, which are the mouse clicks.</h4>

<h4>In the function handleClick I handle the mouse click events for the cells in the board. Most of the functions called here will be separately explained. In short, the currentClass variable saves the character (X or O), whose turn it is at the moment. Another function is used in the if statement to check if someone has already won by comparing the winning combinations to the gameplay. This way it determines whether there is a draw or not.</h4>

<h4>The placeMark() places the character in the cell, currentClass being either an X or an O depending on whose turn it is. The swapTurns() function is the one which swaps the turns after the character is placed in a cell.</h4>

<h4>checkWin() which is called to check if our board matches any of the winning combinations.
  
<h2>Output</h2>
<img src="https://github.com/Fhini/TIC-TAK-TOE/assets/118623264/a5e13038-b997-43a5-ad3f-b29f3317343f">

<h3><a href="https://tikktakt0e.netlify.app/" target="_blank">Click here to play</a></h3>
