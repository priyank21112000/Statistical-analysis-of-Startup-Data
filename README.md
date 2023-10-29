# Statistical-analysis-of-Startup-Data

This project applies statistical analysis techniques to predict the success or failure of startups based on industry trends, funding information, and company characteristics.

## Data

The dataset contains information on 923 startups and includes 48 features capturing relevant metrics like:

- Funding rounds 
- Total funding amount
- Investor relationships
- Milestones
- Location
- Industry type

The target variable is the 'status' of each startup - whether it was acquired, had an IPO, or closed down. 

## Analysis

The following statistical methods were used:

- Comparing samples - Z-test, T-test
- ANOVA
- Categorical data analysis - Chi-square test
- Linear regression
- Resampling methods - K-fold cross-validation
- Regularization methods

Key predictors identified:

- Age at first funding round
- Number of funding rounds  
- Investor relationships
- State and industry type
- Milestones achieved 

## Model

A logistic regression model was built using cross-validation to evaluate performance.

The model achieved an average accuracy of 71% across 10 folds.


## References

- The dataset is from Crunchbase.

## Contributing

Contributions to improve the analysis and model are welcome!
