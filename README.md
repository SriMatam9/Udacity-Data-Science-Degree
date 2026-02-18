# Udacity-Data-Science-NanoDegree
Project No. 1 in the Udacity Data Science Nanodegree by Sri Matam

# AI Adoption in Stack Overflow Developer Survey 2025

This repository contains code and assets for a blog post analyzing AI adoption, AI models used, perceived AI threat, and AI agent usage among developers, using the 2025 Stack Overflow Developer Survey public data(https://survey.stackoverflow.co/2025).

## Contents
- `ai_survey_2025_analysis.ipynb` — Jupyter notebook with EDA, modeling, and a scenario prediction following CRISP-DM.
- `survey_results_public2025.csv` — Source data (placed locally).

## Environment & Libraries
- Python 3.x
- pandas, numpy, matplotlib, scikit-learn, nbformat

## How to Run
1. Place `survey_results_public2025.csv` in the project root.
2. Open and run `ai_survey_2025_analysis.ipynb`.

## Summary of Results
- A majority of respondents report using AI tools at least weekly.
- OpenAI GPT and Claude lead the list of models developers have worked with.
- Most respondents **do not** see AI as a job threat; a sizable minority are unsure.
- AI agent usage is emerging: small daily/weekly core, many planning to start, and a large "do not plan" segment.
- A simple logistic model predicting daily/weekly AI usage from demographics achieves ~0.59 accuracy and ~0.63 ROC-AUC.

## Acknowledgments
- Data: Stack Overflow Developer Survey 2025 (public dataset).


