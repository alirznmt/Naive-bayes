# Learning Naive Bayes Model

## Overview
This project involves learning a Naive Bayes model to classify data using Maximum Likelihood Estimation (MLE) and Bayesian approach (MAP). The dataset used is the Breast Cancer dataset from UCI, which contains 9 binary features and a binary class variable.

## Dataset
The dataset is provided in a file called `BreastCancer.rar`, available on the course webpage. Details about the dataset can be found at Breast Cancer UCI.

## Project Steps
1. **Parameter Estimation using MLE**:
   - Split the data into training (80%) and testing (20%) sets.
   - Estimate the parameters for the conditional probability distributions in the network using MLE on the training data.
   - Replicate this process 20 times and report the mean of the performance measure (rate of misclassification).
   - Use the constructed Naive Bayesian network to classify samples by applying Bayes' rule to compute conditional class probabilities \( P(C | A1, A2, ..., A9) \) and predict the label with the highest probability.
   - Record the parameters \( \theta_C \) and \( \theta_{A1|C} \), and the percentage of classification error on the testing data.

2. **Parameter Estimation using MAP**:
   - Estimate the parameters for the conditional probability distributions in the network using the Bayesian approach (MAP) on the training data.
   - Specify the prior distribution and report the error results and estimates.
   - Compare the results with the MLE approach from part (i).

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn

## How to Run
1. Clone the repository.
2. Extract the `BreastCancer.rar` file and place the dataset in the appropriate directory.
3. Install the required libraries.
4. Run the Jupyter notebook or Python scripts provided for both MLE and MAP estimations.

## Results
- Mean performance measure (rate of misclassification) for MLE over 20 trials.
- Parameters \( \theta_C \) and \( \theta_{A1|C} \) for the Naive Bayes model.
- Percentage of classification error on the testing data for both MLE and MAP.
- Comparison of error results between MLE and MAP.

## Conclusion
This project demonstrates the implementation of Naive Bayes classifiers using both MLE and MAP approaches, providing insights into their performance and differences in parameter estimation.


