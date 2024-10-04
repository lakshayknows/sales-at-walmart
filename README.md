# Walmart Sales Prediction

## Overview
This project focuses on predicting Walmart sales using machine learning techniques. The dataset contains various features related to Walmart sales, which we analyze to build predictive models that can forecast sales performance.

## Table of Contents
- [Installation](#installation)
- [Data Description](#data-description)
- [Model Building](#model-building)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation
To run this project, you need to have Python and the following libraries installed:
- pandas
- numpy
- scikit-learn
- statsmodels
- matplotlib
- seaborn

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn statsmodels matplotlib seaborn
```

## Data Description
The dataset Walmart_Sales.csv contains the following columns:

The data contains the following columns:

1. `Store:` Store number
2. `Date:` Sales week start date
3. `Weekly_Sales:` Sales
4. `Holiday_Flag:` Mark on the presence or absence of a holiday
5. `Temperature:` Air temperature in the region
6. `Fuel_Price:` Fuel cost in the region
7. `CPI:` Consumer price index
8. `Unemployment:` Unemployment rate


## Model Building
The project involves building a Random Forest Regressor to predict weekly sales. The following steps are implemented:

1. Data loading and preprocessing.
2. Exploratory data analysis (EDA) to understand trends and patterns.
3. Splitting the dataset into training and testing sets and Kfolds.
4. Training the model and evaluating its performance using metrics such as R² and cross-validation scores.

## Results
1. Cross-validation R-squared scores: [0.95154174 0.95028379 0.95932361 0.95107528 0.95464539]
2. Mean R-squared score: 0.9534
3. Standard deviation of R-squared scores: 0.00332.
4. R-squared score on training and test data: 0.9602243639508954

Detailed insights and visualizations are provided in the Jupyter notebook.
   
## Contributing
Contributions are welcome! If you have suggestions for improvements or enhancements, feel free to create a pull request.

## License
This project is licensed under the Apache License - see the LICENSE file for details.

Acknowledgments
Thanks to Kaggle for providing the dataset.
Thanks to the open-source community for their libraries and tools that made this analysis possible.


