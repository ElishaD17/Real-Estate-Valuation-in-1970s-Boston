# Real-Estate-Valuation-in-1970s-Boston
Boston Housing Analysis: Understanding Property Features and Price Determinants
This analysis aims to understand the key features that determine housing prices and how different variables interact with each other to influence property values.

## Objectives

- Understand the distribution of housing prices and the features that influence them.
- Construct a predictive model using linear regression to estimate housing prices.
- Evaluate the performance of the model on test data and compare the results with original prices.
- Explore the potential of log transformation in enhancing the model's predictive capability.

## Technologies Used

- **Language**: Python
- **Libraries**: Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn

## Steps to Reproduce

1. **Set up your environment**:
   - Install Python and Jupyter Notebook or any preferred IDE.
   - Install the necessary libraries: Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn.
   
2. **Download the Boston Housing dataset**:
   - The dataset can be loaded directly from the Scikit-learn library or obtained from UCI Machine Learning Repository.
   
3. **Run the analysis**:
   - Load the dataset into a Pandas DataFrame.
   - Perform exploratory data analysis using visualization tools from Matplotlib and Seaborn.
   - Apply machine learning techniques using Scikit-learn to predict housing prices and understand feature importance.

## Results

-Features such as the average number of rooms (RM), crime rates (CRIM), pupil-teacher ratio (PTRATIO), and percentage of lower status population (LSTAT) play significant roles in determining housing prices.
-The constructed linear regression model achieved an R2 value of 0.67 on the test data, indicating that the model explains 67% of the variance in housing prices.
-Applying a log transformation to the target variable (price) improved the model's performance, with the 
R 2value increasing to 0.74.

## Conclusion

The Boston Housing analysis offers valuable insights into the features that significantly influence property values. The constructed predictive model can be a valuable tool for estimating housing prices in the Boston area based on a set of property features. Moreover, the improvement in model performance after log transformation suggests the potential non-linear relationship between some features and housing prices. It's essential for stakeholders to consider these relationships and the model's findings when making decisions related to property investment, selling, or buying in the Boston area.
