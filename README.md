# Exploratory_Data_Analysis-Project
Description:
Use external Python packages to retrieve and analyze valuable information from a supermarket retail chain dataset.
Key steps displayed  include:

1. Initial Data Exploration
2. Univariate Analysis
3. Bivariate Analysis
4. Dealing With Duplicate Rows and Missing Values
5. Correlation Analysis




Implementation




For Initial Data Exploration:

- Use Pandas to read the data, get a brief glimpse of the first few rows, and calculate some quick summary statistics of the numeric columns.




For Univariate Analysis:

- Conduct univariate analysis on both continuous and categorical variables.

- First plot the distribution of customer ratings with Seaborn and also overlay the mean, 25th, and 75th percentile quantiles calculated using NumPy.

- Then use Pandas' .hist() method to plot the distribution for all numeric variables.

- Using Seaborn's .countplot() method, we see the frequency distribution of 'Branch' and 'Payment' which are categorical variables.




For Bivariate Analysis:

- Conduct bivariate analysis on both continuous and categorical variables.

- Use Seaborn to plot scatterplots and regression plots to identify the relationship between customer rating and gross income.

- Additionally, use Seaborn to plot a boxplot to check the difference in aggregate sales figures between the three branches of supermarkets, and to compare sales patterns between men and women.

- Plot a time series graph to check for trends in gross income over a period of three months.




For Dealing With Duplicate Rows and Missing Values:

- Calculate the number of duplicate rows and delete them using Pandas.

- Replace missing values by means of their respective columns.

- Explore the dataset using Pandas Profiler to see how we can automate a lot of exploratory data analysis given certain conditions are met.




For Correlation Analysis:

- Conduct correlation analysis on the numeric variables in our dataset.

- Use Numpy to calculate the correlation between two numeric variables.

- Use pandas to calculate a correlation matrix to show all pairwise correlations of numeric variables.

- Use Seaborn to plot the calculated correlation matrix as a heatmap that is easily interpretable.
