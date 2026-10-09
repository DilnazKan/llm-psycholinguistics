# LLM vs Human Word Norms

Can large language models replace human ratings of word meaning? This project compares LLM-generated concreteness and valence ratings with human norms, and tests whether the model truly understands words or partly recognises them from training data.

_Project for the course Cognitive & Behavioural Measures_

## 1️⃣ LLM norms validation

Compared three prompting strategies (zero-shot, few-shot, definition-based), checked rating stability across runs, validated LLM ratings against human norms and tested whether they predict word recognition times.

## 2️⃣ Frequency & contamination

Compared LLM accuracy on high- vs low-frequency words, then slightly misspelled the words (e.g. harp → harg) to test whether the model reasons about meaning or recalls ratings it has already seen.

## Key findings
LLM ratings follow the same ranking as human norms, with few-shot prompting closest to humans.
Exact values differ: the model underestimates concreteness and polarises emotions (negative words more negative, positive more positive).
Agreement drops sharply on misspelled words, suggesting the model partly recognise familiar words rather than reasoning about them.

## Tools
Python · pandas · NumPy · SciPy · statsmodels · Matplotlib · Seaborn · R · Jupyter
