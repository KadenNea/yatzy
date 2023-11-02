# Yatzy Game Project

## Overview
Welcome to the Yatzy Game project! This digital version of the classic Yatzy game allows players to roll dice, score points, and compete against each other. It's a fun and strategic game that tests your luck and decision-making skills.

## Rules
Here are the basic rules of the Yatzy game:

- **Objective**: The goal is to score as many points as possible over several rounds.
- **Equipment**: The game is played with five dice and a scorecard.
- **Gameplay**:
  1. Players take turns rolling five dice.
  2. After each roll, they can choose which dice to keep and which to re-roll, for a maximum of three rolls per turn.
  3. Players must select a scoring category for their roll, such as "Ones," "Twos," "Three of a Kind," etc.
  4. The score is calculated based on the chosen category and the dice values.
  5. Once a category is used, it cannot be selected again in future turns.
  6. The game consists of 13 rounds, and the player with the highest total score at the end wins.

Detailed rules and scoring categories can be found [here](https://en.wikipedia.org/wiki/Yatzy).

## Design System Documentation

### Color Scheme
- Backround Colour: Grey 
- Board Colour: Green
- Table Colour:Black


### Fonts
- Heading Font: "Times new roman", sans-serif
- Body Text Font: "Roboto", sans-serif
- Yahtzee title font: "Arial"


## Dice Design

### Dice Appearance
- Size: 50px x 50px
- Color: Blue
- Dots (Pips):White

**Rationale**: The dice are designed to be clear and easily readable. Black dots on a white background provide high contrast for better visibility.

### Digital Representation
![dice6](https://github.com/KadenNea/yatzy/assets/144380812/2d367021-79e0-41f4-9352-a9cfbe899fd4)
![dice5](https://github.com/KadenNea/yatzy/assets/144380812/1d20f285-cfd1-45fd-ae91-80ff96d295b9)
![dice4](https://github.com/KadenNea/yatzy/assets/144380812/72a75732-eb10-4005-ac0e-dbba1b28e083)
![dice3](https://github.com/KadenNea/yatzy/assets/144380812/2397be8d-e112-4823-b74e-3f902c1ddff0)
![dice1](https://github.com/KadenNea/yatzy/assets/144380812/0aa1e10d-4f9b-4e00-ad60-369bb0a8baae)
![dice2](https://github.com/KadenNea/yatzy/assets/144380812/012c2b60-7cc3-4d4a-9957-74e3fe4c75a5)


## Game Mock-ups

### HTML/CSS Code
Here's a simplified mock-up of the game's HTML structure and CSS styles:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Yatzy Game</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <header>
        <h1>Yatzy Game</h1>
    </header>
    <main>
        <div class="game-board">
            <!-- Dice, scorecard, and other game components go here -->
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>
