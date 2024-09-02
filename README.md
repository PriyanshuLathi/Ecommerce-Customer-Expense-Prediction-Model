# Ecommerce Customer Expenditure Prediction Model

This project focuses on predicting the yearly amount spent by customers in an ecommerce setting using linear regression, ridge regression, and lasso regression models. The dataset includes various customer-related features, and the models are designed to predict customer expenditure with high accuracy.

## Dataset Description

The dataset contains features such as time spent on the website, time spent on mobile applications, length of membership, and other relevant variables that influence customer spending. The target variable is the yearly amount spent by customers. Data preprocessing steps, including feature selection and scaling, were applied to ensure the data's suitability for regression analysis.

## Methodology

The following steps were followed to build and evaluate the models:

1. **Data Loading and Preprocessing**: The dataset was loaded using Pandas. Unnecessary columns were dropped, and categorical variables were encoded where necessary.

2. **Feature Selection**: Relevant features were selected based on their impact on the target variable. This process involved analyzing feature importance and correlations.

3. **Model Training**: Three models were trained using Scikit-learn:
   - **Linear Regression**
   - **Ridge Regression**: Ridge regularization was applied with hyperparameter tuning using GridSearchCV.
   - **Lasso Regression**: Lasso was used to evaluate feature importance and model performance.

4. **Model Evaluation**: The models were evaluated using the following metrics:
   - **Mean Absolute Error (MAE)**
   - **Mean Squared Error (MSE)**
   - **Root Mean Squared Error (RMSE)**
   - **R² Score**

   Below are the evaluation metrics for each model on the test set:

   | Model               | RMSE          | R² Score     |
   |---------------------|---------------|--------------|
   | Linear Regression   | 2.783         | 0.9855       |
   | Ridge Regression    | 10.538        | 0.9819       |
   | Lasso Regression    | 10.539        | 0.9819       |

## Accuracy and Model Performance

The linear regression model achieves an **R² score of 98.55%**, indicating high accuracy in predicting yearly customer expenditure. Ridge and Lasso regressions, with R² scores of 98.19%, also perform well, showcasing the benefits of regularization in handling multicollinearity and enhancing model stability. The lower RMSE value for Linear Regression (2.783) compared to Ridge (10.538) and Lasso (10.539) further confirms that the Linear Regression model provides the most precise predictions among the tested approaches.

## Further Scope

To enhance the models, future improvements could include:

- **Feature Engineering**: Creating new features to capture complex relationships.
- **Advanced Models**: Exploring more complex algorithms like decision trees or ensemble methods.
- **Deployment**: Deploying the model as an API or integrating it into ecommerce platforms for real-time predictions.

## Dependencies

The following libraries are required to run this project:

- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/PriyanshuLathi/Ecommerce-Customer-Expense-Prediction-Model.git
    ```

2. Install the required dependencies:

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

## License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Ecommerce-Customer-Expense-Prediction-Model/blob/main/LICENSE) file for details.

## Contact

For questions or feedback:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors

- Priyanshu Lathi