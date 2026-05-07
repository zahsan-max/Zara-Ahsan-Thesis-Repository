The repository contains Python scripts, R scripts, CSV files, and speech txt files.

The speeches folder contains the speeches from each candidate that were used in the following models.

Each Python script is its own model for the respective hypothesis. The files cannot be fully run without an API key:
- Making_The_Opponent_Look_Small.ipynb
- pity_party.ipynb
- Us_vs_Them.ipynb

training_set.xlsx is an additional training set for the model used in pity_party.ipynb

The CSV files are the results from each of the models with the relevant characterstics being standardized (divided by the length of the speech then multiplied by 1000):
- Making_the_Opponent_Look_Small_results.csv
- pity_party_scores.csv
- Us_vs_Them_Framing.csv

statistical-analysis.qmd is an R-script that performs the statistical analyses (logitistic regression and Mann-Whitney U Tests)



