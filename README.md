# Hidden Markov Model (HMM) Project

A Python implementation of a Hidden Markov Model (HMM) with the Viterbi Algorithm for biological sequence analysis.

This project demonstrates how HMMs can be used to model hidden biological states and determine the most probable sequence of states for a given DNA sequence.

---

# Features

- Hidden Markov Model implementation
- State transition probability matrix
- Emission probability matrix
- Log probability calculations
- Viterbi Algorithm
- Backtracking to find optimal hidden states
- DNA sequence analysis


# Technologies Used

- Python 3
- NumPy
- Jupyter Notebook / Google Colab


# Hidden States

| State | Meaning |
|------|------|
| s | Start State |
| E | Exon |
| 5 | Splice Site |
| I | Intron |
| e | End State |


# Example DNA Sequence

CTTCATGTGAAAGCAGACGTAAGTCA

The model predicts the most probable hidden state sequence corresponding to the DNA sequence.


# Algorithms Implemented

# 1. Log Probability Calculation
Calculates the probability of a sequence using logarithmic probabilities.

# 2. Viterbi Algorithm
Finds the most probable sequence of hidden states.

Steps:
1. Initialization
2. Recursion
3. Traceback
4. Final state prediction


# Installation

Clone the repository:

git clone https://github.com/your-username/HMM-project.git

Move to project folder:

cd HMM-project

Install dependencies:

pip install numpy


# Running the Project

Open the notebook using Jupyter:

jupyter notebook HMM_project.ipynb

Or run it directly in Google Colab.


# Sample Output

Most Probable Path:

EEEEEE5IIIIIIIIIIIIIIIIIII


# Concepts Covered

- Hidden Markov Models
- Dynamic Programming
- Bioinformatics
- DNA Sequence Analysis
- Probability Theory
- Viterbi Decoding


# Future Improvements

- Add Forward Algorithm
- Baum-Welch Training
- Better visualization
- Larger genomic datasets support
- GUI/Web interface


# Author

Saket kumar

GitHub: https://github.com/saketchoudhary2147-hue
