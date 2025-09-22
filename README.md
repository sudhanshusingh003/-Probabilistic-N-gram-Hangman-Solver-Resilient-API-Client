# -Probabilistic-N-gram-Hangman-Solver-Resilient-API-Client
A sophisticated Hangman solver that uses character n-gram language models (1-gram to 5-gram) to predict the most likely next letter from English word patterns — with adaptive blending, smart fallbacks, dynamic recalibration, and a resilient API client.
🚀 Features

N-gram Language Models: 1-gram through 5-gram character frequency analysis.

Adaptive Blending: Weighted probability combination across different context lengths.

Smart Fallbacks: Vowel preference and frequency-based strategies when evidence is weak.

Dynamic Recalibration: Prunes the dictionary and rebuilds n-grams as incorrect guesses accumulate.

Robust API Client: Handles network issues with retries and backoff.

Regex Pre-filtering: (Suggested) quick mask-based dictionary filtering to speed up inference.
