# Diabetes Prediction Project

## Overview
This project aims to predict the likelihood of diabetes in individuals using machine learning techniques. The dataset used for this analysis is the Pima Indians Diabetes Database, which contains various health-related features such as glucose levels, blood pressure, and age.

## Exploratory Data Analysis
- The dataset contains 768 entries and 9 columns.
- Data preprocessing was performed, including handling missing values and checking for duplicates.
- Various data visualizations, including bar plots, box plots, pair plots, heatmaps, and histograms, were created to gain insights into the dataset.

## Model Training and Evaluation
- A Random Forest Classifier was chosen as the machine learning model.
- Features were normalized using Min-Max scaling.
- The dataset was split into training and testing sets.
- The model achieved an accuracy of 74.03% on the test dataset.
- A confusion matrix was generated to evaluate the model's performance.

## Repository Structure
- `pima-indians-diabetes.csv`: The dataset used for analysis.
- `diabetes_prediction.ipynb`: Jupyter Notebook containing the code for data analysis and model training.
- `README.md`: This README file providing an overview of the project.

## Dependencies
- Python 3.x
- Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn

## Usage
1. Clone the repository to your local machine.
2. Open and run the `diabetes_prediction.ipynb` Jupyter Notebook to reproduce the analysis and model training.
3. Modify the code and hyperparameters as needed for your specific use case.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to explore the Jupyter Notebook for a more detailed analysis of the dataset and model implementation.
