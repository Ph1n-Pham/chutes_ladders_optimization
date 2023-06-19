# Dynamic Programming and Reinforcement Learning Algorithms on Chutes and Ladders
Optimizing the childhood game of Chutes and Ladders using Dynamic Programming and Reinforcement Learning techniques

**Author**: [Phineas Pham](https://github.com/Ph1n-Pham), Tung Luu, Duc Doan, Uyen Le <br />
**Date**: April 2023

Chutes and Ladders is a classic childhood game in which players aim
to move their token from Square 0 to Square 100 on the board by rolling
dice. In the original version, strategic decision-making is not necessary, so
we add a strategic element to the game by having players choose among
four Efron dice with different possible moves. The objective is to deter-
mine which dice to play at each square to minimize the future number of
steps. Using four different frameworks, including Dynamic Programming
Solution, Monte Carlo, SARSA, and Q-Learning, we find that the optimal
policy allows us to win in an average of 10 steps. However, Q-Learning
outperforms the other three algorithms with the smallest expected num-
ber of steps, the smallest result variation, and shortest time to reach an
optimal policy.

Review our research paper where we summarize our experimentation and explanation [here](https://github.com/Ph1n-Pham/chutes_ladders_optimization/blob/main/research_report.pdf)!

## References:

1. Wikimedia Foundation. (2023, April 21). Q-learning. Wikipedia. Re-
trieved May 1, 2023, from https://en.wikipedia.org/wiki/Q-learning
2. Shyalika, C. (2021, July 13). A beginners guide to Q-learning. Medium.
Retrieved May 1, 2023, from https://towardsdatascience.com/a-beginners-guide-to-q-learning-c3e2a30a653c
3. Geron Aurelien. (2023). "Hands-on machine learning with Scikit-learn,
Keras, and TensorFlow concepts, tools, and techniques to build Intelligent
Systems." O’Reilly.
4. Marsland, S. (2014). ”Machine learning: An algorithmic perspective, sec-
ond edition.” Chapman & Hall/CRC
