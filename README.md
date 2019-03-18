# Extreme Tic-Tac-Toe Bot

An AI bot that plays a super-scaled variant of the popular Ultimate Tic Tac Toe game, with either a person or another bot.

### Running The Bot

The bot is written in Python2, so a Python2 runtime enviroment is required. It does not use any external libraries, so standard installation is sufficient. 

There are three options 
- Bot Vs. Bot
- Bot Vs. Player
- Player Vs. Player

```sh
$ python2 simulator.py [option]
```


# Features

  - Implemented the Mini Max Algorithm with alpha-beta pruning, with an excellent heuristic and evaluation function.
  - To improve the performance of the alpha-beta minimax algorithm, iterative deepening has been implemented, restricting the bot and player to 24 seconds per move.
  - Implemented a variant of Zobrist Hashing, needs completion.


## Todos

 - Further Improve Heuristic Function
 - Finish Zobrist Hashing
 - Explore other tree search algorithms (like the Monte Carlo Tree Search Algorithm)