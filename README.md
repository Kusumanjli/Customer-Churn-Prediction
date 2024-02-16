Churn Prediction Project
Overview
This repository contains a simple churn prediction project using logistic regression. Churn prediction is the task of identifying customers who might stop using a service or product. In this project, we build a predictive model to identify customers at risk of churning.

Project Structure
churn_prediction.ipynb: Jupyter notebook containing the entire project workflow, from loading the data to evaluating the model.
churn_prediction.csv: Dataset used for the project.
Prerequisites
Python 3.x
Jupyter Notebook
Required Python libraries: numpy, pandas, seaborn, matplotlib, scikit-learn
Getting Started
Clone the Repository:

Open your terminal.
Run the following commands:
bash
Copy code
git clone https://github.com/your-username/churn-prediction.git
cd churn-prediction
Install Dependencies:

Make sure you have Python 3.x installed.
Install required libraries by running:
bash
Copy code
pip install -r requirements.txt
Explore the Project:

Open churn_prediction.ipynb in Jupyter Notebook.
Run each cell sequentially to understand and reproduce the analysis.
What's in the Notebook?
Step 1: Loading Data

Load the dataset (churn_prediction.csv) into a Pandas DataFrame.
Step 2: Handling Missing Values

Explore and fill in missing values for key features like 'gender' and 'days_since_last_transaction'.
Step 3: Feature Engineering

Convert 'gender' to numerical values.
One-hot encode the 'occupation' column.
Step 4: Scaling Numerical Features

Log-transform and standardize numerical features for logistic regression.
Step 5: Building the Model

Train a logistic regression model using a subset of features.
Step 6: Model Evaluation

Assess model performance using ROC AUC, recall, and precision scores.
Visualize the ROC curve and confusion matrix.
What to Expect?
Understanding the Data:

Explore basic statistics and visualizations to grasp the dataset.
Data Cleaning and Preprocessing:

Handle missing values and convert categorical features into a suitable format.
Building and Evaluating the Model:

Train a logistic regression model on a simplified set of features.
Evaluate model performance using standard metrics.
Contributing
Feel free to contribute by providing feedback or suggesting improvements. You can open issues or submit pull requests.


Author
Kusumanjli
