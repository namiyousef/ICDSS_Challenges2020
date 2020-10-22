# Contents of sub-directory


## Project description:
Create a regression model for sales prices of different properties.

Key highlights of the problem:
- Dataset is has many attributes (82)
- Dataset only has a fraction of continuous data (around 25%), the rest are categorical (split roughly 50-50 into nominal and ordinal) and discrete

Key highlights of analysis:
- Decreased attributes to ~30 by removing those that were deemed redundant or irrelevant
- PCA/MCA and factor analysis did not provide attributes that explain the data sufficiently well
- Ridge regression used with lambda = 8, resulting in a model with a low MAE (0.15), but also a low R^2 (0.48)

**Data:** contains the data required for this project

**PythonFiles:** contains python files that have functions relevant to the analysis

**real-estate.ipynb:** the notebook where exploration / analysis is conducted

# Note:

Please note that the following files have been taken from the ICDSS GitHub repository.

- data.csv
- reader.py
