# PacManAI-Reinforcement_learning
This project provides a demo game of Pacman, as well as the Q-learning method to train an AI player.
To start a default game, use the command python pacman.py.
To start an AI, use the command -p ApproximateQAgent that chooses a Q-learning Agent and -a extractor=SimpleExtractor that chooses the feature extractor.
To set the time of training, use the command -x, such as -x 50 means the AI will be trained 50 times before showing a test demo.
To set the time of total times of the game (including training), use the command -n.
To set the map, use the command -l mediumClassic.
Example: python pacman.py -p ApproximateQAgent -a extractor=SimpleExtractor -x 50 -n 51 -l mediumClassic
The command above will use Approximate Q-learning Agent and Simple Extractor to train the pacman 50 times in the mediumClassic layout and 1 time of test demo will be shown.
