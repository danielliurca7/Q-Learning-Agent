# Q Learning Agent
Implementation of a mouse that must chase after pieces of cheese while avoiding a cat in a grid world with obstacles, using Q Learning. If the cat gets close enough to the mouse it will chase it. We will look at four strategies for exploration.

## Exploring strategies
* Max First: it chooses the action with maximum utility
* Random: chooses random actions
* Exploiting: in state where there are unexplored actions choose a random one from these
* Weighted Exploration: balances exploring and exploiting with a probability based on the utility of the next state
