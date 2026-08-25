# Python-flashcard-quiz
An interactive terminal-based Python flashcard quiz app featuring random question sampling and input validation.

# Python Flashcard Quiz App

An interactive command-line / Jupyter Notebook quiz application built in Python. It pulls random questions from a larger pool, tracks scores in real-time, and provides instant feedback after each answer.

## Features

- **Random Sampling:** Uses Python's `random.sample()` to pull 5 unique questions from a 20+ question bank every round.
- **Dynamic Interface:** Clears and refreshes the display after each question for a clean user experience.
- **Deadlock-Safe Input Handling:** Optimized input ordering to prevent Jupyter Notebook kernel hangs.
- **Case-Insensitive Validation:** Automatically strips trailing spaces and handles uppercase/lowercase variations.
- **Score Tracking & Percentage:** Calculates correct answers and presents a formatted score at the end of each round.

## How to Run

1. Open the notebook (`.ipynb`) in Jupyter Notebook, VS Code, or Google Colab.
2. Run the code cells.
3. Type your answer into the prompt and press **Enter**.
4. Choose whether to play another 5-question round when finished!

## Prerequisites

- Python 3.x
- `IPython` library (included by default with Jupyter)
