# Project Title

Connect 4
## Summary

This game/program will be a re-create of the board game connect four. This will mainly be player vs AI, with the AI being tough to beat. The program is also very slow.

## Background

I was interested in making connect 4 AI because most of the time, on most websites, whenever I played agaisnt some sort of AI in, for example tic tak toe, the opponent would start getting repetitive and it starts to get boring as you just repeat moves over and over.


## How is it used?

The program will be created starting by opening a compiler.
We then go ahead and create a 2d array(this will be the board)
We then set up the rules of the game(ex: when you say a number your piece would fall there to the bottom) + win/lose conditions
Now we set up the player inputs and finish the game without the AI to test for any huge bugs. (player vs player for testing)
After evertything seems good, we now start setting up the AI.
The AI will use a +1 , -1, strategy and predict every possible move and stores it in multidimensional arrays.
We then search through those arrays and find the best (highest number) possible path and runs moves according to that path.
Set up the basics for a game(ex: play button and reset button).

## Data sources and AI methods
The main data will come from the AI itself.
The method used will be a +1 -1 prediction method (dont remember name of method) to find the best route and follow through.

## Challenges

The main challenge would be ballecing the AI, as the main issue is that if a bot is too hard or easy, it isn't fun and most will not use/test it.
## What next?
We could make this more using deep learning. I would need more experience with this method to use it, but if I do learn it, it would use strategies instead of looking through every possible moveset as this would make it interesting (also the AI would be incrementally more difficult making it also good for a human to learn the game).
