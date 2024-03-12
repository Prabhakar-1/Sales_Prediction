# Sales Prediction using Logistic Regression

This repository contains code for a project that predicts sales from customer data using logistic regression. It was developed with Python, leveraging libraries like Pandas, scikit-learn, and Matplotlib for data manipulation, model development, and visualization.




  
## Overview of the Project

- **Data Loading**: The project begins with loading the dataset (salary.csv) using Pandas.

- **Data Preprocessing**: Several preprocessing steps are performed, including mapping salary data to binary values, segregating the dataset into input (X) and output (Y) variables, and splitting the data into training and testing sets.

- **Feature Scaling**: Feature scaling is applied to ensure all features contribute equally to the result. StandardScaler from scikit-learn is used for this purpose.

- **Model Development**: Logistic regression is chosen as the predictive model. The notebook includes code for finding the optimal K-value for K-Nearest Neighbors (K-NN) through an iterative process and then training the logistic regression model.

- **Prediction and Evaluation**: Predictions are made for new customer data, and the model's accuracy is evaluated using a confusion matrix.

## Usage

1. Clone the repository: `<gh repo clone Prabhakar-1/Sales_Prediction>`
2. Open the google colab file (`sales_predict.ipynb`) using  Google Colab.
3. Run the code cells sequentially to load the dataset, preprocess the data, train the model, make predictions, and evaluate the model's performance.

## Requirements

- Python 3
- Pandas
- NumPy
- scikit-learn
- Matplotlib

## Contributing

If you find any issues, have improvements, or want to add new simulations, feel free to open an issue or create a pull request. Contributions are welcome!

## License
You are free to use, modify, and distribute the files for both commercial and non-commercial purposes.


