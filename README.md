# Insurance Cost Prediction Model

This repository contains a Jupyter Notebook for building and training a machine learning model to predict insurance costs based on demographic and health-related features. The project demonstrates the use of RandomForestRegressor and GridSearchCV to optimize model performance.

## Project Overview

The goal of this project is to create a model that accurately predicts insurance costs using features such as:
- Age
- Sex
- BMI (Body Mass Index)
- Number of children
- Smoking status
- Region

## Files

- `project1.ipynb`: The main Jupyter Notebook containing all the code for data preprocessing, model training, and predictions.

## Model Description

- **Algorithm Used**: Random Forest Regressor
- **Optimization**: GridSearchCV is used to fine-tune the hyperparameters for better model accuracy.
- **Features**: Age, sex, BMI, number of children, smoking status, and region.

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/insurance-cost-prediction.git
   ```
2. Navigate to the project directory:
   ```
   cd insurance-cost-prediction
   ```
3. Install the necessary dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```
   jupyter notebook project1.ipynb
   ```

## Key Results

The trained model can predict the insurance cost for a new customer with an example prediction provided in the notebook.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.
