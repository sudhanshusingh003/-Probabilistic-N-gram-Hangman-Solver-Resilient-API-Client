# -Probabilistic-N-gram-Hangman-Solver-Resilient-API-Client
A sophisticated Hangman solver that uses character **n-gram language models (1-gram to 5-gram)** to predict the most likely next letter from English word patterns — with adaptive blending, smart fallbacks, dynamic recalibration, and a resilient API client.

---

##🚀 Feature

-N-gram Language Models: Utilizes 1-gram to 5-gram character frequency   analysis for accurate predictions.

-Adaptive Blending: Combines probabilities from different n-gram models using a weighted average for superior accuracy.

-Smart Fallbacks: Implements vowel preference and general letter frequency strategies when n-gram data is sparse.

-Dynamic Recalibration: Prunes the dictionary and rebuilds n-gram models on the fly when remaining attempts are low, adapting to the game's constraints.

-Robust API Client: Features a resilient HTTP client to interact with the game server, handling network issues with automatic retries.
