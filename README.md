# Iris Reproducible Experiment

## Objective
Classify Iris flowers using a Random Forest model and demonstrate reproducible computing.

## Dataset
Iris dataset from scikit-learn, containing 150 samples.

## Tools
- Python
- Google Colab
- scikit-learn
- GitHub

## Experiment Settings
- Model: RandomForestClassifier
- Number of trees: 100
- Test size: 0.25
- Model random state: 42
- Split random states tested: 42 and 7

## How to Run
1. Open iris_experiment.ipynb in Google Colab.
2. Run all cells in order.
3. Compare the accuracy results.

## Results

Experiment 1:
- Test size: 0.25
- Split random state: 42
- Accuracy: 1.0 (100%)

Experiment 2:
- Test size: 0.25
- Split random state: 7
- Accuracy: 0.8947 (89.47%)

Re-running Experiment 2 with the same settings
produced the same accuracy.
