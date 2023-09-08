


# Player Draft Prediction using Random Forest Classifier

This project focuses on predicting whether a player will be drafted based on various features using a Random Forest classifier. The dataset consists of player statistics and corresponding draft status. The goal is to build a predictive model to assist in player drafting decisions.

## Dataset

The training and testing datasets are available as train.csv and test.csv available in the main branch. 

The `drafted` column in the dataset indicates whether a player was drafted (1 for drafted, 0 for not drafted).

# basnet_aibarna-24585717-best_model.py

This code file "basnet_aibarna-24585717-best_model.py" is part of the Advanced Machine Learning Applications assignment (AT1) for the course. It contains the implementation of a machine learning model for a specific task. If you are interested in other experiments performed for this task go to notebooks folder.


## Introduction
This code file is developed for a machine learning task. It includes data loading, exploratory data analysis (EDA), data preprocessing, feature selection, and model building. The goal is to train and evaluate a predictive model using the provided dataset.

## Getting Started
To use this code file, you should have Python and the necessary libraries installed on your system. You can install the required libraries using the following command:


```bash
pip install -r requirements.txt


## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/aibarna96/adv_mla_at1.git
   cd adv_mla_at1/src/models
   ```

2. Install the required Python packages. It is recommended to set up a virtual environment before installing dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook or Python script to train the model and make predictions:
   ```bash
   jupyter notebook basnet_aibarna-24585717-best_model.ipynb
   # or
   python basnet_aibarna-24585717-best_model.py
   ```

4. The predictions for the test dataset will be saved in the `out.zip` file.

## Model Evaluation

The Random Forest classifier is used to predict player drafting status. The model's performance is evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC score. The Receiver Operating Characteristic (ROC) curve is also plotted to visualize the trade-off between true positive rate and false positive rate.

## Contributing

Contributions to this project are welcome! If you have any improvements or suggestions, feel free to create issues or pull requests.
