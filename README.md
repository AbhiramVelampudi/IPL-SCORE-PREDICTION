# IPL Score Prediction

This repository contains a Jupyter Notebook for predicting the score in an IPL (Indian Premier League) cricket match using a neural network model. The notebook processes the data, trains a model, and provides a widget-based interface for making predictions based on user input.

## Dataset

The dataset used in this project is assumed to be `ipl_data.csv`, which contains various features related to IPL matches. The relevant columns used in the notebook include:
- `venue`
- `bat_team`
- `bowl_team`
- `batsman`
- `bowler`
- `total` (target variable)

## Installation

To run this notebook, you need to have the following Python libraries installed:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- keras
- tensorflow
- ipywidgets

You can install these packages using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn keras tensorflow ipywidgets
```


                            <<Usage>>

Load Data: The dataset ipl_data.csv is loaded into a pandas DataFrame.
Preprocess Data:
Unnecessary columns are dropped.
Categorical features are label encoded.
Split Data: The data is split into training and testing sets.
Scale Data: Features are scaled using MinMaxScaler.
Build Model: A neural network model is defined using Keras.
Train Model: The model is trained on the training data.
Evaluate Model: Model performance is evaluated using mean absolute error.
Prediction Interface: An interactive widget-based interface is provided for making predictions.

                        <<Interactive Prediction>>

The notebook includes an interactive widget-based interface where users can select:

Venue
Batting Team
Bowling Team
Striker
Bowler
Upon clicking the "Predict Score" button, the model predicts the score based on the selected inputs.
