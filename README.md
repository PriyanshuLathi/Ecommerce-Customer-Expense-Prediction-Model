# Ecommerce Customer Expense Prediction Model

This project focuses on predicting the yearly amount spent by customers in an ecommerce setting using a linear regression model. The dataset includes various customer-related features, and the model is designed to provide accurate spending predictions. Performance metrics such as MAE, MSE, RMSE, and R² score are used to assess the model's effectiveness.

## Dataset Description

The dataset used in this project contains information on ecommerce customers, including features such as average session length, time spent on the app, time on the website, and membership duration. Each record corresponds to a customer, with the target variable being their yearly amount spent. The dataset is prepared to ensure suitability for linear regression analysis.

## Methodology

The following steps were followed to build and evaluate the model:

1. **Data Loading and Preprocessing**: 
   - The dataset was loaded using Pandas.
   - Exploratory Data Analysis (EDA) was performed to understand data distributions and relationships.

2. **Feature Selection**:
   - Numerical features were selected for analysis.
   - A heatmap of correlations was used to identify features significantly impacting the target variable.

3. **Model Training**: 
   - The linear regression model was trained using the Scikit-learn library.
   - The data was split into training and testing sets to validate the model's performance.

4. **Model Evaluation**:
   - The model was evaluated using various metrics:
     - **Mean Absolute Error (MAE)**: 7.743
     - **Mean Squared Error (MSE)**: 93.833
     - **Root Mean Squared Error (RMSE)**: 2.783
     - **R² Score**: 0.9855

These metrics provide insights into the model's performance, with the R² score of 0.9855 demonstrating the model's effectiveness in predicting customer spending.

## Accuracy and Model Performance

The linear regression model provides accuracy 98%, as indicated by the R² score of 0.9855. The extremely low error values (MAE, MSE, RMSE) confirm the model's precision, and the R² score indicates a strong predictive performance.

## Further Scope

Although the current model performs well, there are areas for further exploration and improvement:

- **Feature Engineering**: Creating additional features could help capture more complex relationships between customer behavior and spending.
- **Model Generalization**: Testing the model on different customer datasets can help assess its generalizability.
- **Advanced Models**: Exploring more complex models, such as decision trees or neural networks, could uncover any non-linear relationships in the data.
- **Real-World Applications**: Deploying the model as an API or integrating it into an ecommerce platform could showcase its practical use.

## Dependencies

The following libraries are required to run this project:

- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

## Installation

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/PriyanshuLathi/Ecommerce-Customer-Expense-Prediction-Model.git
    ```

2. Install the required Python dependencies:

    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Ecommerce-Customer-Expense-Prediction-Model/blob/main/LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors
- Priyanshu Lathi