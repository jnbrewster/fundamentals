# Game Logic

In Unit 4 we covered some game-changing concepts (pun intended). For example, can you guess what type of feature we can begin to implement in our memory card game? If you guessed game logic, you're right! For this section's homework, you will implement your knowledge of conditionals to help with the task of creating your game logic.

## Exercise

#### Requirements

- Create an `if else` statement checking for equality between two of your cards (you choose which ones)
  - if values are equal, execute an `alert` with the message, "You found a match!".
  - if values are not equal, execute an `alert` with the message, "Sorry, try again.".

**hint:** What's an `alert`? Check out the documentation [here](http://www.w3schools.com/jsref/met_win_alert.asp).

#### Below are the steps to complete the assignment.

1) Create an `if else` statement

```js
// `if` statement should consist of a boolean checking for equality between your created variables
if (cardTwo === cardsThree) {

} else {

}
```

2) Add `alert`s to appropriate conditional blocks

```js
// if the conditional is met, run the expression: alert("You found a match!")
if (cardTwo === cardsThree) {

  alert('You found a match!');

// else, run the expression: alert("Sorry, try again.")
} else {

  alert("Sorry, try again.");

}
```

#### Deliverable

Your memory card code should now look something like the following:

```js
var cardOne = "queen";

var cardTwo = "queen";

var cardThree = "king";

var cardFour = "king";

cardOne == cardFour

if (cardTwo === cardThree) {

  alert('You found a match!');

} else {

  alert("Sorry, try again.");

}
```