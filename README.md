# Project-11-SimonGame

This is a web-based implementation of the classic Simon game, created using mainly JavaScript, HTML, and CSS.
Game Rules

The Simon game has four colored buttons, each producing a particular sound when pressed or activated by the game. A round in the game consists of the game lighting up one or more buttons in a random order, after which the player must repeat the sequence by pressing the buttons in the same order. The game then adds one more button to the sequence in the next round. The game continues in this way, with the player repeating each sequence and the game adding one more button each round until the player makes an incorrect move.

<h3>How to Play</h3>

To play the Simon game, simply open the webpage and click on the "Start" button. The game will begin with a sequence of one button, and the player must repeat that sequence by clicking on the buttons in the same order. If the player succeeds, the game will add one more button to the sequence in the next round, and the player must repeat that longer sequence. The game continues in this way until the player makes an incorrect move. At that point, the game ends, and the player's score is displayed.

<h3>Implementation Details</h3>

The Simon game is implemented using JavaScript, HTML, and CSS. The game uses event listeners to detect when the user clicks on each button and checks whether the user's sequence matches the game's sequence. If the user's sequence matches the game's sequence, the game adds one more button to the sequence and plays the sequence again. If the user makes an incorrect move, the game ends, and the player's score is displayed. The game also uses audio files to play the sounds associated with each button.
