# Mini Project: Pig Game & Matplotlib Story Generator

## Overview

This mini project includes two interactive Python programs:

1. **Pig Game**: A simple dice game for two players. The goal is to reach 100 points first by rolling dice and accumulating points. But beware—rolling a 1 will reset your turn's score to zero!
   
2. **Matplotlib Story Generator**: A Mad Libs-style story generator. The program asks for user input (nouns, verbs, adjectives, etc.) and fills them into a pre-written story. Once completed, it uses Matplotlib to visually present the final story.

3. ## Pig Game

### How to Play

1. Run `pig.py` using Python.
2. Players take turns rolling a die.
3. On each turn, a player can choose to:
   - **Roll**: Add the result to their turn score, but if a 1 is rolled, they lose the points for that turn and it's the other player's turn.
   - **Hold**: Keep their current points and end their turn.
4. The first player to reach 50 points wins!

5. ## Matplotlib Story Generator

### How it Works

1. Run `matplotGenerator.py` using Python.
2. The program will prompt you for a series of inputs (e.g., nouns, verbs, adjectives).
3. After collecting your inputs, the program will replace the placeholders in a pre-written story with your words.
4. The final story is then displayed using Matplotlib, with a fun, graphical representation of the story.

5. ### Example

The program will ask for inputs like:
- A noun: `dog`
- A verb: `run`
- An adjective: `happy`

And the output could be a story like:
> "The happy dog loves to run in the park!"

### Story Visualization

Once the story is generated, it will be displayed using Matplotlib in a creative way, such as visual text arrangement or artistic formatting.

## Requirements

Make sure you have Python installed. You will also need to install the following packages for the Matplotlib Story Generator:

```bash
pip install matplotlib
