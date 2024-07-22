# Sales-Prediction-Using-Multiple-Linear-Regression

**Description**:

This project focuses on predicting sales based on advertising expenditures across three media channels: TV, Radio, and Newspapers. By employing Multiple Linear Regression in Python, we aim to build a model that accurately forecasts sales, providing valuable insights for optimizing advertising strategies.

**Objectives and Goals**:

- Predict sales using advertising expenditure data.
- Analyze the impact of TV, Radio, and Newspaper advertising on sales.
- Build and evaluate a Multiple Linear Regression model.
- Provide actionable insights for improving advertising efficiency.

**Importance of Sales Prediction for Businesses**:

- Optimizing advertising budgets.
- Making informed decisions on resource allocation.
- Enhancing marketing strategies.
- Maximizing revenue potential by targeting effective advertising channels.

## Data Description

The dataset provided for this project includes four columns, each representing a different aspect of advertising expenditure and sales figures.

- `TV`: Advertising expenditure on TV
- `Radio`: Advertising expenditure on Radio
- `Newspaper`: Advertising expenditure on Newspapers
- `Sales`: Sales figures

## Data Preprocessing

- Checking for missing values and handling them if necessary.
- As the dataset were given by the organization, there is no need of cleaning the dataset.

## Exploratory Data Analysis (EDA)

Refer python code (EDA.py) provides a brief summary of the Dataset with visualizations.

## Model Building and Evaluation

Refer python code (Model.py) build, train and evaluate the model that fits the data and predict sales values.
Here is a simplified overview of the program:
1. **Load Data**: Read the CSV file into a Data Frame.
2. **Prepare Data**: Split the data into training and testing sets.
3. **Train Model**: Use Linear Regression to learn from the training data.
4. **Evaluate Model**: Print Mean Squared Error (MSE) and R-squared (R²) to check how well the model performs.
5. **Plot Results**: Show a scatter plot of actual vs. predicted sales.
6. **Predict Sales**: Allow the user to input advertising budgets and get a predicted sales value.


## Discussion

### Coefficients and their impacts

- **TV**: 0.05 - Small positive impact on sales and sales increases by 0.05 units through TV ads.
- **Radio**: 0.10 - Largest positive impact on sales and sales increased by 0.10 units through Radio ads.
- **Newspaper**: 0.00 - No significant impact on sales and no impact on sales.
- **Intercept**: 4.71 - Baseline sales i.e., when no money is spent on ads the base line sales is 4.71 units.

### Model’s Performance

**Accuracy**
The model can be evaluated using two key metrics: Mean Squared Error (MSE) and R-squared (R²).
- **MSE**: The low MSE value shows that our model’s predictions are very close to the actual sales values. This indicates that the model is reliable and performs well in predicting sales.
- **R²**: The R-squared value is 0.91. This means that 91% of the variability in sales is explained by our model. In other words, the model is highly effective at capturing the patterns in sales data.

## **Data-Driven Decisions:**

- **Increase Investment in Radio**: Based on the model’s findings, reallocating a larger portion of the advertising budget to Radio will likely maximize sales. This is where we see the highest impact from advertising spend.
- **Evaluate Other Channels**: While Radio is currently the most effective, continue to monitor and evaluate the performance of TV and Newspaper advertising. Consider exploring additional factors or external influences that could impact these channels.

## Business Impact
**1. Increased ROI (Return on Investment):**
- Increasing the budget for Radio advertising, as indicated by our model, is expected to enhance ROI by driving more sales for each dollar spent, optimizing marketing investments for better financial returns.

**2. Efficient Resource Allocation:**
- Shifting more of the advertising budget to Radio will maximize resource efficiency by focusing on the most impactful channel, ensuring that marketing funds generate the highest possible return on investment.

## Conclusion
Our analysis shows that Radio advertising has the most significant effect on driving sales compared to TV and Newspaper. This indicates that increasing investment in Radio advertising is likely to yield the highest return on sales.
