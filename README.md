# Customer_Loyalty_Prediction
Machine learning models for predicting customer loyalty using k-NN and Naïve Bayes in KNIME. The models analyze customer attributes like delivery speed, product quality, and customer type to predict future partnerships. Includes model comparison and accuracy analysis for better predictions.




# Customer Loyalty Prediction Using Machine Learning

This repository contains an assignment completed using KNIME, where we implement two machine learning models — k-Nearest Neighbors (k-NN) and Naïve Bayes — to predict customer loyalty based on various customer data attributes.

## Project Overview
The goal of this project is to predict customer loyalty, which is defined by the likelihood of a customer maintaining future partnerships with a company. The primary predictors used in the analysis include:

- **Delivery Speed**: The speed at which customers receive their products.
- **Product Quality**: Customer satisfaction with product quality.
- **Customer Type**: A classification of customers based on loyalty metrics.

### Models Used:
1. **k-Nearest Neighbors (k-NN)**:
   - **Accuracy (Run 1)**: 73.33%
   - **Accuracy (Run 2)**: 78.33%
   - The second run, with fewer variables, provided better accuracy, making it the preferred model.

2. **Naïve Bayes**:
   - **Accuracy (Run 1)**: 70.00%
   - **Accuracy (Run 2)**: 58.33%
   - Despite this, the k-NN model was preferred due to its higher accuracy.

### Files in the Repository:
- **KNIME Workflows**: Contains the workflows used for running the models.
- **Data Files**: Sample data for customer attributes used in model training and testing.
- **Results**: Output metrics and accuracy results from both models.

### Key Insights:
- **k-NN Performance**: The k-NN model achieved higher accuracy with fewer predictors, making it more efficient for this dataset.
- **Naïve Bayes**: Although the Naïve Bayes model offered valuable insights, it performed less accurately, particularly after the second run.
- **Top Predictors**: The most significant predictors of customer loyalty were `Customer Type`, followed by `Delivery Speed` and `Product Quality`.

### Usage Instructions:
1. **Download KNIME**: [KNIME Download](https://www.knime.com/downloads)
2. **Open the Workflow**: Import the workflow file into your KNIME workspace.
3. **Run the Models**: Execute the k-NN and Naïve Bayes nodes to view results and analyze customer loyalty predictions.



