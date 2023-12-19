# IPL Match Prediction App

This Python script predicts the margin of victory in IPL matches using Support Vector Regression (SVR). The script includes data preprocessing, model training, and evaluation.

## Installation
Make sure you have Python and pip installed. Clone the repository and install the required packages:
```bash
git clone https://github.com/your-username/ipl-match-prediction.git
cd ipl-match-prediction
pip install -r requirements.txt
```

## Usage
Run the script using the following command:
```bash
python ipl_match_prediction.py
```
The script reads the IPL match data from the provided CSV file, preprocesses it, trains an SVR model, and evaluates its performance. Results, including metrics such as Mean Squared Error, R-squared, Mean Absolute Error, and Mean Absolute Percentage Error, are printed to the console. A scatter plot comparing actual vs predicted values is also displayed.

