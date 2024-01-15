**House Prices Prediction Project**

This project focuses on predicting house prices using a dataset named 'HousePrices.csv'. The dataset contains information about various features related to houses, such as the type of alley, basement conditions, garage details, and many more.

**Libraries Used** :

NumPy
Pandas
Matplotlib
Seaborn
Statsmodels
Scikit-learn

**Steps Performed**:

**1) Data Preprocessing**:

Handled null values in the dataset using various strategies for different features.
Addressed duplicates in the data.

**2) Exploratory Data Analysis (EDA)**:

Explored the distribution of categorical features using count plots and pie charts.
Analyzed the relationships between numerical features using pair plots and box plots.

**3) Correlation Analysis**:

Examined the correlation between numerical features using a correlation matrix.
Identified and dropped features with high correlation to avoid multicollinearity issues.

**4) Outlier Treatment**:

Detected outliers in numerical features and applied appropriate treatment to limit extreme values.

**5)Target Variable Transformation**:

Checked the normality of the target variable.
Applied a logarithmic transformation to make the target variable more normally distributed.

**6)Encoding Categorical Columns**:

Converted categorical columns into numerical format using one-hot encoding.

**7)Feature Selection**:

Utilized statistical tests (T-test) to identify statistically significant features.

**8)Model Building**:

Split the dataset into training and testing sets.
Built a Linear Regression model and evaluated its performance.
Conducted cross-validation to assess model robustness.

**9)OLS Model and Feature Elimination**:

Employed Ordinary Least Squares (OLS) regression to analyze the impact of each feature on the target variable.
Eliminated features with high p-values to improve model accuracy.

**10)Final Model and Evaluation**:

Built a refined Linear Regression model with selected features.
Evaluated the final model's performance using various metrics, including Mean Absolute Error, Mean Squared Error, and R-squared.

**11)Conclusion**:

Summarized the findings and highlighted the improvements made in the final model compared to the initial one.

**Note**

The project code is divided into sections for clarity, and comments are provided throughout the code to explain each step. The README serves as a guide to understand the workflow and decisions made during the project.
