# EDA on Boston House Price Dataset

This repository contains a comprehensive exploratory data analysis (EDA) of the Boston House Price dataset. The objective of this analysis is to uncover patterns, relationships, and insights within the dataset that can help in understanding the factors influencing house prices in Boston.

## Introduction

The Boston House Price dataset is a popular dataset for regression analysis. It includes various features such as crime rate, number of rooms, and distance to employment centers, which are used to predict the median value of owner-occupied homes. This analysis aims to perform a detailed EDA to visualize and understand these features and their relationships with house prices.

## Dataset

The dataset is loaded from the `statsmodels` library, specifically from the `MASS` package. It includes the following columns:

- **crim**: Per capita crime rate by town
- **zn**: Proportion of residential land zoned for lots over 25,000 sq. ft.
- **indus**: Proportion of non-retail business acres per town
- **chas**: Charles River dummy variable (1 if tract bounds river; 0 otherwise)
- **nox**: Nitrogen oxides concentration (parts per 10 million)
- **rm**: Average number of rooms per dwelling
- **age**: Proportion of owner-occupied units built prior to 1940
- **dis**: Weighted distances to five Boston employment centers
- **rad**: Index of accessibility to radial highways
- **tax**: Full-value property tax rate per $10,000
- **ptratio**: Pupil-teacher ratio by town
- **black**: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town
- **lstat**: Percentage of lower status of the population
- **medv**: Median value of owner-occupied homes in $1000s

## Analysis Steps

The Jupyter Notebook included in this repository performs the following steps:

1. **Import Libraries**: Import necessary Python libraries such as `numpy`, `pandas`, `matplotlib`, `seaborn`, and `statsmodels`.
2. **Load the Dataset**: Load the Boston Housing dataset using `statsmodels`.
3. **Initial Inspection**: Display the first few rows, dataset information, and summary statistics.
4. **Check for Missing Values**: Check for any missing values in the dataset.
5. **Data Visualization - Distribution of House Prices**: Plot the distribution of house prices.
6. **Feature Correlation**: Plot the correlation matrix to visualize relationships between features.
7. **Pairplot**: Generate pairplots to visualize relationships between multiple features.
8. **Relationship Analysis**:
   - **Rooms vs. Price**: Analyze the relationship between the number of rooms and house prices.
   - **LSTAT vs. Price**: Analyze the relationship between LSTAT (percentage of lower status of the population) and house prices.
9. **Outliers Detection**: Detect outliers in house prices using a boxplot.
10. **Save Your Analysis**: Save the processed data and analysis results to a CSV file.

## Conclusion

This analysis provides a thorough understanding of the factors influencing house prices in Boston. The insights derived from this EDA can be used to inform further predictive modeling and decision-making processes.

## How to Use

1. Clone this repository: `git clone https://github.com/prizbot/EDA-on-Boston-House-Price-Dataset.git`
2. Navigate to the repository directory: `cd EDA-on-Boston-House-Price-Dataset`
3. Open the Jupyter Notebook: `jupyter notebook EDA_on_Boston_house_price_dataset.ipynb`
4. Run the cells to perform the EDA.

## Contact

Feel free to reach out if you have any questions or suggestions:

- **LinkedIn**: [Priyadharshini NRS](https://www.linkedin.com/in/priyadharshininrs)
- **Email**: priyadharshininrs@gmail.com

## Fun Fact

✨ Did you know? The Boston Housing dataset is one of the oldest and most widely used datasets in machine learning and statistics, despite its ethical concerns that led to its removal from scikit-learn!

Thank you for exploring this analysis!
