# Churn Prediction Project

## Overview

This repository hosts a straightforward churn prediction project using logistic regression. Churn prediction aims to identify customers likely to stop using a product or service. In this project, we build a predictive model to identify potential churners.

## Project Structure

- **churn_prediction.ipynb**: Jupyter notebook covering the entire project, from loading data to model evaluation.
- **churn_prediction.csv**: Dataset used for the project.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- Python libraries: `numpy`, `pandas`, `seaborn`, `matplotlib`, `scikit-learn`

## Getting Started

### Clone the Repository:

```bash
git clone https://github.com/your-username/churn-prediction.git
cd churn-prediction
```
## Install Dependencies:

Make sure you have Python 3.x installed.

```bash
pip install -r requirements.txt
## What's in the Notebook? (Continued)
```
## What's in the Notebook?

1. **Loading Data:**
   - Load the dataset (`churn_prediction.csv`) into a Pandas DataFrame.

2. **Handling Missing Values:**
   - Explore and fill in missing values for key features like 'gender' and 'days_since_last_transaction'.

3. **Feature Engineering:**
   - Convert 'gender' to numerical values.
   - One-hot encode the 'occupation' column.

4. **Scaling Numerical Features:**
   - Log-transform and standardize numerical features for logistic regression.

5. **Building the Model:**
   - Train a logistic regression model using a subset of features.

6. **Model Evaluation:**
   - Assess model performance using ROC AUC, recall, and precision scores.
   - Visualize the ROC curve and confusion matrix.

## What to Expect:

- The project guides you through exploring, preprocessing, and building a predictive model for churn prediction.
- Expect clear insights into the dataset, effective data cleaning steps, and a practical approach to building and evaluating the model.

**Feel free to reach out for any questions or improvements!**

## Contributing

Feel free to contribute by providing feedback or suggesting improvements through issues or pull requests.

## Author
**Kusumanjli**
**https://www.linkedin.com/in/kusumanjli-khattar-166b881b1/**

