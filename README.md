<h1> My Project </h1>

<h3>2: World Happiness Ranking Report – R</h3>

<p><strong>Analyzed global happiness data for 156 countries using the 2019 World Happiness Report</strong></p>

<ul>
  <li>Explored relationships between happiness score and predictors (GDP, family, life expectancy, trust) using correlation and regression</li>
  <li>Ranked countries and regions by average happiness score; visualized results using bar plots and pie charts</li>
  <li>Assessed distribution and normality using histograms, boxplots, Shapiro-Wilk test, skewness, and kurtosis</li>
  <li>Conducted hypothesis testing (ANOVA, t-test) to evaluate score differences across regions and over time</li>
  <li>Created a regional summary dashboard including Coefficient of Variation (COV) to measure score variability</li>
  <li>Extracted and analyzed Singapore’s happiness ranking and contributing factors for in-depth comparison</li>
</ul>

<h3>3: Sales Transactions Data Analysis | R, Excel</h3>

<p><strong>Analyzed customer transactions data using R to explore regional sales patterns, identify outliers, compare product performance, and test statistical hypotheses.</strong></p>

<ul>
  <li>Analyzed daily sales data to understand customer profiles by region and payment method</li>
  <li>Conducted descriptive and inferential statistics on sales amount, including skewness, kurtosis, and outlier detection</li>
  <li>Tested normality (Shapiro-Wilk), performed t-tests and ANOVA to compare Books vs DVDs and across regions</li>
  <li>Assessed correlation between DVD sales and time of day; found no significant relationship (p &gt; 0.05)</li>
  <li>Computed confidence and prediction intervals for DVD sales to inform pricing and forecast future transactions</li>
  <li>Evaluated business hypotheses on product performance to support data-driven retail strategies</li>
</ul>

<h3>4: Human Capital Index Hypothesis Testing</h3>

<p><strong>Analyzed World Bank data to show that log-transformed GDP per capita significantly predicts Human Capital Index with strong model fit (Adj. R² = 0.744, p &lt; 2e-16).</strong></p>

<ul>
  <li>Analyzed World Bank dataset (258 countries, 2016/17) focusing on Human Capital Index predictors.</li>
  <li>Applied log transformation to GDP per capita (PPP) for better linear relationship and highlighted Singapore’s data point.</li>
  <li>Fitted linear regression model showing log(GDP) significantly predicts Human Capital Index (p &lt; 2e-16).</li>
  <li>Model explains approximately 74% of variation (Adjusted R² = 0.744), indicating strong fit.</li>
  <li>Rejected null hypothesis: log(GDP) slope ≠ 0, confirming it as a significant predictor.</li>
</ul>

<h3>5: Diamond Information: Plotting and Data Transformation</h3>

<p><strong>Log-transforming diamond price and carat improved regression assumptions and model fit.</strong></p>

<ul>
  <li>Fitted multivariate regression with price predicted by carat, cut, clarity, and color; Residuals vs. Fitted plot showed patterns indicating assumption violations.</li>
  <li>Normal Q-Q plot revealed deviations from normality of residuals, questioning regression assumptions.</li>
  <li>Scatter plot matrix indicated some non-linear relationships among variables.</li>
  <li>Log-transformation of price and carat improved Residuals vs. Fitted plot by reducing heteroscedasticity and enhancing linearity.</li>
  <li>Normal Q-Q plot after transformation showed residuals closer to normal distribution, indicating better model validity.</li>
</ul>

<h3>6: Housing Price Prediction Using Multiple Linear Regression</h3>

<p><strong>Built and validated a Boston house price model with 73.4% R² and significant predictors.</strong></p>

<ul>
  <li>Developed a multiple linear regression model to predict house prices in Boston, MA using features: bedrooms, lot size, and square footage</li>
  <li>Interpreted model coefficients to evaluate the impact of each predictor on price</li>
  <li>Conducted residual and QQ plot analysis to assess model assumptions and normality</li>
  <li>Performed Shapiro-Wilk test and ANOVA to test for normality and overall model significance</li>
  <li>Calculated confidence intervals and conducted hypothesis testing on predictors</li>
  <li>Used the model to make predictions and evaluate pricing fairness for individual properties</li>
  <li>Demonstrated strong model fit with R² = 73.4% and significant F-statistic (p &lt; 0.05)</li>
</ul>

<h3>7: U.S. College Application Classification | Logistic Regression, R</h3>

<p><strong>Classified U.S. colleges by application volume using logistic regression in R, achieving 95% accuracy and identifying key predictors like top 10% enrollment and room &amp; board costs.</strong></p>

<ul>
  <li>Built logistic regression model to classify colleges receiving ≥10,000 applications based on features like Top10perc, Grad Rate, and Room &amp; Board</li>
  <li>Created binary target variable and converted categorical predictor (Private) to factor with proper reference level</li>
  <li>Interpreted model coefficients and odds ratios; found private status significantly decreases odds of high application volume (p &lt; 0.001)</li>
  <li>Predicted probabilities and classified outcomes using 0.35 threshold; evaluated performance with confusion matrix</li>
  <li>Achieved 95% overall accuracy with high specificity (98%) but moderate sensitivity (38%) due to class imbalance</li>
  <li>Highlighted false negative impact and suggested model refinement for improved positive class recall</li>
</ul>

