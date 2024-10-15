# The-Simon-Game

This is a web-based implementation of the classic Simon Game. The game displays a series of colored buttons in a random order, and the player must repeat the sequence in the correct order. With each successful repetition, the sequence gets longer, making the game progressively harder

A live demo of the Simon Game is available at: GitHub Pages Link (https://mukul-405.github.io/The-Simon-Game/)

# Features

Four different colored buttons: Red, Blue, Green, Yellow.
Random sequence generation that increases in length with each successful round.
Sound effects associated with each button press.
Game-over sequence when the player makes an incorrect choice, with the option to restart the game.

# Gameplay

Press any key to start the game.
Watch the sequence of flashes and sounds.
Repeat the sequence by clicking the colored buttons in the correct order.
If you click the wrong button, the game ends, and you can restart by pressing any key again.

# Technologies Used

HTML: Structure of the game.
CSS: Styling for the game buttons and layout.
JavaScript (jQuery): Game logic, sequence generation, user input handling, and animations.

# Code Explanation

The game follows these main functions:

nextSequence():

Generates a random color from the available buttonColours array.
Increments the level and displays the sequence.
Plays the corresponding sound and animation for each color.
checkAnswer(index):

Compares the user's selected button sequence with the generated game pattern.
If the player clicks the correct button, the game continues. Otherwise, the game resets.
playSound(name):

Plays the sound corresponding to the button that was clicked or generated in the sequence.
animatePress(currentColor):

Adds a visual effect to the button when pressed, creating a feedback loop for the player.
startOver():

Resets the game variables when the player makes a mistake.

# Contribution

If you'd like to contribute, feel free to fork the repository, make your changes, and submit a pull request. Contributions and suggestions are always welcome!
