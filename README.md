# Credit Risk Modeling and Scorecard Development

This repository demonstrates the development of a Credit Risk Model and a Credit Scorecard using Python. It leverages historical loan data from 2007 to 2014 to predict the likelihood of a loan default and create a tool for assessing the creditworthiness of applicants.

## Project Overview

The main objectives of this project are:

1. **Credit Risk Modeling**: Build a model to predict the probability of loan default.
2. **Scorecard Development**: Use the model to create a credit scorecard that simplifies credit risk evaluation.

## Project Structure

### Environment Setup

**Libraries**: 
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

**Tools**:
- Jupyter Notebook
- Google Colab

### Data Import and Exploration

**Dataset**: 
- Historical loan data from Lending Club.

**Tasks**: 
- Initial data exploration
- Data type verification
- Null value analysis

### Data Cleaning and Preprocessing

- Handle missing values and remove redundant or forward-looking columns.
- Convert categorical data into numerical formats using dummy variables.

### Feature Selection

- **Techniques**: 
  - Chi-squared statistic for categorical features.
  - ANOVA F-statistic for numerical features.
- **Multicollinearity detection** through pairwise correlations.

### Weight of Evidence (WoE) Binning

- Apply WoE and Information Value (IV) transformations to improve model interpretability and performance.

### Model Development

- **Logistic Regression**: Chosen for its simplicity and interpretability.
- **Performance Metrics**: 
  - Confusion matrix
  - ROC-AUC score
  - Precision-Recall curves

### Credit Scorecard Development

- Translate model outputs into a scoring framework for lenders.

## Outputs

- A trained logistic regression model.
- A credit scorecard for evaluating loan applicants.

## Results

### Model Performance:

- **ROC-AUC**: 0.85
- **Precision and Recall**: 0.80, 0.85

### Scorecard Insights:

- Key thresholds for credit approval or rejection.
- Visualization of risk levels.

## Medium Article

A detailed explanation of the model can be found [here](https://towardsdatascience.com/how-to-develop-a-credit-risk-model-and-scorecard-91335fc01f03?source=friends_link&sk=473eece07f71357852e91e3aa650294f).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Additional Notes

- The credit scorecard is a simplified example for educational purposes.
- While the methodology can be applied to other datasets, further validation is needed for real-world applications.
- This project does not constitute financial advice.
