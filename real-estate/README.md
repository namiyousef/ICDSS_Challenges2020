# Contents of sub-directory


## Project description:
Create a regression model for sales prices of different properties.

Key highlights of the problem:
- Dataset is has many attributes (82)
- Dataset only has a fraction of continuous data (around 25%), the rest are categorical (split roughly 50-50 into nominal and ordinal) and discrete

**Data:** contains the data required for this project

**PythonFiles:** contains python files that have functions relevant to the analysis

**real-estate.ipynb:** the notebook where exploration / analysis is conducted

Key highlights of analysis:
- Decreased attributes to ~30 by removing those that were deemed redundant or irrelevant
- PCA/MCA and factor analysis did not provide attributes that explain the data sufficiently well
- Ridge regression used with lambda = 8, resulting in a model with a low MAE (0.15), but also a low R^2 (0.48)

**real-estate-2.ipynb:** for the second iteration of the project, Support Vector regression was used to 
obtain a higher accuracy.

Key highlights of analysis:
- Overall improvement to R^2: 30%
- Overall effect on mean squared error: 20% lower
- Can you find methods of reducing the dimensions even further?

**real-estate-3.ipynb:** for the third iteration, autoencoders are used to extract useful information form the data

# Note:

Please note that the following files have been taken from the ICDSS GitHub repository.

- data.csv
- reader.py
