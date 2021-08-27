# Flashcards

Flashcards is a study tool

## Usage and Demonstration
Game is played via the Command Line Interface in Terminal. With the project directory installed, the user can run the index.js file in node. The user answers a round of 30 questions, receiving feedback on each answer as well as a score and time elapsed at the end of the round.

![Gameplay on Node in the terminal](https://media.giphy.com/media/NldIkrUTILn8mQgXeE/giphy.gif?cid=790b7611f41f3992810db25d596d034496224f0f8af77aea&rid=giphy.gif&ct=g)

## Programming Languages and Dependencies

This app was developed using:

- JavaScript
- Node
- Mocha
- Chai

## Architecture
- Card.js, Turn.js, Deck.js, Round.js, Game.js - components of the game built as classes
- Card-test.js, Turn-test.js, Deck-test.js, Round-test.js, Game-test.js - Mocha/Chai test suites for each component
- index.js - creates a server and starts the game by invoking the Game class
- util.js - facilitates question prompt/answer functionality
- data.js - contains information with which to build flashcards

## Contributions

_This app was developed by:_

[Nolan Caine](https://github.com/n0land0)

_Nolan is a student of front-end engineering at the Turing School of Software & Design._

## Resources
[Project board](https://github.com/n0land0/flashcards/projects/1) created using GitHub Projects

[Project spec](https://frontend.turing.edu/projects/flash-cards.html) provided by [Turing School of Software and Design](https://turing.edu/)
