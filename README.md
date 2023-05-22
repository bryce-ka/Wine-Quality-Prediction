# Wine Quality Prediction

This repository contains the code and corresponding research paper for predicting the quality of wines using machine learning techniques. The research paper provides an in-depth analysis of the dataset and presents the findings of various models.

## Dataset
The datasets used for this project are the *Red Wine Quality Dataset*, which consists of various chemical properties of red wines along with their quality ratings. The dataset is available in the file `winequality-red.csv` and the *White Wine Quality Dataset*, which consists of various chemical properties of white wines along with their quality ratings. The dataset is available in the file `winequality-white.csv` which is loaded and processed in the code.

## Code
The code is written in Python and is available in the Jupyter Notebook format (`wine_preds.ipynb`). The following packages are imported:

- `pandas` for data manipulation and analysis
- `numpy` for mathematical operations
- `matplotlib.pyplot` for data visualization
- `seaborn` for creating statistical graphics
- `sklearn` for machine learning algorithms and evaluation metrics

The code is divided into multiple sections, each addressing different aspects of the analysis and modeling process. Here are some key sections:

### Data Loading and Preprocessing
The code begins with loading the dataset and performing initial preprocessing steps. It includes importing necessary libraries, reading the CSV file, and separating the input features (`red_x`) and the target variable (`red_y`).

### Exploratory Data Analysis
This section includes data visualization using the `seaborn` library. A histogram plot is created to visualize the distribution of wine quality ratings for the red wines dataset.

### Model Training and Evaluation
The code then proceeds to train and evaluate machine learning models. Two models are trained and evaluated: Linear Regression and Ridge Regression. The code utilizes techniques such as k-fold cross-validation and train-test splitting for model evaluation.

### Results and Error Analysis
The code outputs the evaluation results for each model, including the mean squared error (MSE). The predicted values are compared with the actual values, and the error is calculated.

## Research Paper
The research paper (`Predicting_the_Quality_of_Wine.pdf`) provides detailed information about the dataset, methodology, experimental setup, and analysis results. It discusses the performance of different models, presents error analysis, and provides insights into the prediction of wine quality.

Please refer to the Jupyter Notebook and the research paper for a comprehensive understanding of the analysis and findings.

Feel free to explore the code and research paper to gain insights into predicting the quality of red wines using machine learning techniques. If you have any questions or feedback, please don't hesitate to reach out.

Happy analyzing and modeling!
