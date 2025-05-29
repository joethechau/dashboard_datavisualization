<h2>* My Project *</h2>
***My Project In Details***

**2: World Happiness Ranking Report – R**

*Analyzed global happiness data for 156 countries using the 2019 World Happiness Report*

* Explored relationships between happiness score and predictors (GDP, family, life expectancy, trust) using correlation and regression
* Ranked countries and regions by average happiness score; visualized results using bar plots and pie charts
* Assessed distribution and normality using histograms, boxplots, Shapiro-Wilk test, skewness, and kurtosis
* Conducted hypothesis testing (ANOVA, t-test) to evaluate score differences across regions and over time
* Created a regional summary dashboard including Coefficient of Variation (COV) to measure score variability
* Extracted and analyzed Singapore’s happiness ranking and contributing factors for in-depth comparison

**3: Sales Transactions Data Analysis | R, Excel**

*Analyzed customer transactions data using R to explore regional sales patterns, identify outliers, compare product performance, and test statistical hypotheses.*

* Analyzed daily sales data to understand customer profiles by region and payment method
* Conducted descriptive and inferential statistics on sales amount, including skewness, kurtosis, and outlier detection
* Tested normality (Shapiro-Wilk), performed t-tests and ANOVA to compare Books vs DVDs and across regions
* Assessed correlation between DVD sales and time of day; found no significant relationship (p > 0.05)
* Computed confidence and prediction intervals for DVD sales to inform pricing and forecast future transactions
* Evaluated business hypotheses on product performance to support data-driven retail strategies

**4: Human Capital Index Hypothesis Testing**

*Analyzed World Bank data to show that log-transformed GDP per capita significantly predicts Human Capital Index with strong model fit (Adj. R² = 0.744, p < 2e-16).*

* Analyzed World Bank dataset (258 countries, 2016/17) focusing on Human Capital Index predictors.
* Applied log transformation to GDP per capita (PPP) for better linear relationship and highlighted Singapore’s data point.
* Fitted linear regression model showing log(GDP) significantly predicts Human Capital Index (p < 2e-16).
* Model explains approximately 74% of variation (Adjusted R² = 0.744), indicating strong fit.
* Rejected null hypothesis: log(GDP) slope ≠ 0, confirming it as a significant predictor.

**5: Diamond Information: Plotting and Data Transformation**

*Log-transforming diamond price and carat improved regression assumptions and model fit.*

* Fitted multivariate regression with price predicted by carat, cut, clarity, and color; Residuals vs. Fitted plot showed patterns indicating assumption violations.
* Normal Q-Q plot revealed deviations from normality of residuals, questioning regression assumptions.
* Scatter plot matrix indicated some non-linear relationships among variables.
* Log-transformation of price and carat improved Residuals vs. Fitted plot by reducing heteroscedasticity and enhancing linearity.
* Normal Q-Q plot after transformation showed residuals closer to normal distribution, indicating better model validity.


**6: Housing Price Prediction Using Multiple Linear Regression**

*Built and validated a Boston house price model with 73.4% R² and significant predictors.*

* Developed a multiple linear regression model to predict house prices in Boston, MA using features: bedrooms, lot size, and square footage
* Interpreted model coefficients to evaluate the impact of each predictor on price
* Conducted residual and QQ plot analysis to assess model assumptions and normality
* Performed Shapiro-Wilk test and ANOVA to test for normality and overall model significance
* Calculated confidence intervals and conducted hypothesis testing on predictors
* Used the model to make predictions and evaluate pricing fairness for individual properties
* Demonstrated strong model fit with R² = 73.4% and significant F-statistic (p < 0.05)


**7: U.S. College Application Classification | Logistic Regression, R**

*Classified U.S. colleges by application volume using logistic regression in R, achieving 95% accuracy and identifying key predictors like top 10% enrollment and room & board costs.*

* Built logistic regression model to classify colleges receiving ≥10,000 applications based on features like Top10perc, Grad Rate, and Room & Board
* Created binary target variable and converted categorical predictor (Private) to factor with proper reference level
* Interpreted model coefficients and odds ratios; found private status significantly decreases odds of high application volume (p < 0.001)
* Predicted probabilities and classified outcomes using 0.35 threshold; evaluated performance with confusion matrix
* Achieved 95% overall accuracy with high specificity (98%) but moderate sensitivity (38%) due to class imbalance
* Highlighted false negative impact and suggested model refinement for improved positive class recall

