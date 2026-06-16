# Adult Income Prediction using Machine Learning

Hi, my name is Jeevan Jijo. This project is a machine learning project focused on predicting whether a person earns more than 50K per year based on different personal and employment-related features.

The main aim of this project was to work with tabular data, clean and prepare the dataset, train different machine learning models, and compare their performance using proper evaluation metrics.

## Project Overview

This project uses the Adult Income dataset, which contains information such as age, education, occupation, marital status, working hours, and other features. The target is to predict whether a person’s income is above or below 50K per year.

The project helped me understand the full machine learning workflow, from data preprocessing and exploratory data analysis to model training, evaluation, comparison, and feature importance analysis.

## Features

* Data loading and exploration
* Data cleaning and preprocessing
* Handling categorical and numerical features
* Feature encoding and scaling
* Exploratory data analysis
* Training multiple machine learning models
* Model evaluation using classification metrics
* ROC-AUC comparison
* Feature importance analysis
* Artificial Neural Network implementation
* Basic unsupervised clustering using K-Means

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest
* Gradient Boosting
* Artificial Neural Network
* K-Means Clustering

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* PyTorch
* Jupyter Notebook
* Git and GitHub

## Project Structure

```text
adult-income-prediction/
│
├── adult_income_prediction.ipynb
├── README.md
└── requirements.txt
```

## How to Run the Project

1. Clone the repository.

```bash
git clone https://github.com/G112727/adult-income-prediction.git
```

2. Open the project folder.

```bash
cd adult-income-prediction
```

3. Create and activate a virtual environment.

```bash
python -m venv venv
venv\Scripts\activate
```

For macOS or Linux:

```bash
source venv/bin/activate
```

4. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn torch jupyter
```

5. Open Jupyter Notebook.

```bash
jupyter notebook
```

6. Open the notebook file.

```text
adult_income_prediction.ipynb
```

7. Run the notebook cells in order.

## Dataset

This project uses the Adult Income dataset. The dataset is commonly used for binary classification problems where the aim is to predict whether a person earns more than 50K per year.

The dataset includes features such as:

* Age
* Work class
* Education
* Occupation
* Marital status
* Relationship
* Race
* Gender
* Capital gain
* Capital loss
* Hours worked per week
* Native country
* Income category

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC score
* Confusion matrix

These metrics helped compare the models and understand how well each one performed.

## Results

The traditional machine learning models performed well on the dataset, with Gradient Boosting giving one of the strongest overall results. The Artificial Neural Network also performed well and showed how deep learning can be applied to structured tabular data.

Overall, the project showed that proper preprocessing, feature encoding, and model comparison are very important when working with real-world tabular datasets.

## What I Learned

This project helped me improve my understanding of supervised machine learning and tabular data classification. I learned how to prepare data, handle different feature types, train multiple models, and compare their performance using different evaluation metrics.

It also helped me understand how feature importance can be used to explain model predictions and how neural networks can be compared with traditional machine learning models.



## Author

Jeevan Jijo

Computer Science graduate interested in artificial intelligence, machine learning, cloud computing, cybersecurity, and building practical real-world projects.
