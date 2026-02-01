# Predictive Model of Rural Attractiveness for Urban Youth
This repository contains the source code, synthetic dataset, and visualizations for a logistic regression model that predicts the attractiveness of rural territories for urban youth migration. It supports the analysis described in the manuscript: *"Youth and Rurality: Perceptions, Motivations, and Barriers to Rural Migration Among Urban Youth."*

## Objective
The purpose of the model is to estimate the probability that a rural territory is perceived as "attractive" for young people, based on key dimensions derived from survey results:
- Environmental appeal
- Emotional well-being
- Socioeconomic opportunities
- Infrastructural access
- Behavioral intentions (e.g., telework, local consumption)
## Contents

- **data/**: Includes the simulated dataset with 500 synthetic territories.
- **src/**: Contains the main Python script for generating data, training the model, and evaluating performance.
- **figures/**: ROC curve and confusion matrix output.
- **docs/**: (Optional) Includes manuscript or supplementary explanations.

## How to Run

```bash
# Clone this repository
git clone https://github.com/your-username/rural-youth-attractiveness-model.git
cd rural-youth-attractiveness-model/src

# Install dependencies (if using virtualenv)
pip install -r requirements.txt

# Run the model
python Logistic_Model_Rural_Attractiveness.py
