Download Link: https://assignmentchef.com/product/solved-stat235-lab-5-simple-linear-regression
<br>
In this assignment, you will use linear regression features available in Excel to examine the relationship between the thrust of a jet turbine engine and three predictor variables: fuel flow rate, exhaust temperature, and ambient temperature. In particular, you will develop simple regression models that adequately approximate the thrust as a function of each of the three predictor variables, and allow for the questions of interest to be investigated. Moreover, you will apply appropriate diagnostic tools in Excel to verify the regression model assumptions.

<strong> </strong>The Thrust of a Jet Turbine Engine

Jet engines are used for high-speed flight within the atmosphere. They are extremely reliable and provide lots of thrust for their weight. A jet engine goes through the same sort of process as a piston engine, except that combustion occurs continuously, rather than once, during each four-step cycle.

In the lab assignment, you will use simple linear regression to make predictions about thrust of a jet turbine engine using one of the three predictor variables: fuel flow rate, exhaust temperature, and ambient temperature. Which of the variables is the most important predictor of thrust? How reliable are predictions about thrust using a regression model based on one of the three predictors? You will answer the questions with Excel.

The data are available in the Excel file <em>lab5.xls</em> located at <a href="http://www.stat.ualberta.ca/statslabs/index.htm">http://www.stat.ualberta.ca/statslabs/index.htm</a> (click <em>Stat 235</em> link, and <em>Data </em>for <em>Lab 5</em>). The data are not to be printed in your submission.

The following is a description of the four variables in the data file:

Variable Name                   Description of Variable

thrust                                     Thrust of a jet turbine engine,

rate                          Fuel flow rate, extemp                       Exhaust temperature, ambtemp                 Ambient temperature at time of test.

<ol>

 <li>First examine the relationship between the response variable (thrust) and each of of the three predictor variables with scatterplots.</li>

</ol>

<ul>

 <li>Obtain a scatterplot of thrust versus each of the three predictors. The format of each of the three scatterplots should be consistent with the format used in <em>Lab 1 Instructions</em> (no lines or grids, axes rescaled to display only the observed values, title, names of the axes).  Paste the three scatterplots into your report.</li>

 <li>Comment briefly on the relationship between thrust and each of the three predictors. In particular, comment on the overall shape (line, curve), direction (positive, negative), and strength (size of the scatter and its inclination) of the relationship. Which of the three predictor variables seems to be the best predictor of thrust?</li>

</ul>

<ol start="2">

 <li>Examining the array of all possible pairwise correlation coefficients is another way to understand the relationships among variables. Use the <em>Correlation</em> tool in the <em>Data Analysis</em> menu to obtain the correlation matrix for the four variables<em>.</em></li>

</ol>

<ul>

 <li>Paste the correlation matrix into your report. Make sure that the matrix contains the names of all variables.</li>

 <li>Identify the regressor variables (predictors) having the largest and smallest absolute values of correlation with the response variable (thrust). Do the signs and magnitudes of the correlation coefficient between thrust and each predictor confirm your conclusions you have reached in Question 1? Explain briefly.</li>

</ul>

<ol start="3">

 <li>Define a simple linear regression model with thrust as the response variable and fuel flow rate as the predictor variable.  State the model assumptions.</li>

 <li>Perform a simple linear regression analysis using thrust as the response variable and fuel flow rate as the predictor variable using the <em>Regression </em> Then use the computer output to answer the following questions:</li>

</ol>

<ul>

 <li>What is the estimated regression equation? Are there any influential observations in the sense that removing them would change the fitted line? Are there any outliers (large residuals)?</li>

 <li>What is the value of <em>s</em>, the estimate of the model standard deviation ()?</li>

 <li>at percent of the variation in thrust is explained by fuel flow rate? What other possible predictor variables may explain the remaining variation?</li>

 <li>Is linear regression on fuel flow rate of any value in explaining thrust? In particular, state the</li>

</ul>

null and alternative hypotheses in terms of the population slope of the regression line, obtain the value of the test statistic, specify the distribution of the test statistic under the null hypothesis, and obtain the <em>p</em>-value of the test. What do you conclude?

<ul>

 <li>Use the output to obtain a 95% confidence interval for the mean change in thrust as fuel flow rate increases by 1 unit.</li>

 <li>Use the regression model to predict the mean thrust when fuel flow rate is 30,250 (case 1). What is the value of the residual in this case?</li>

 <li>Obtain and paste the plot of residuals against fuel flow rate. Describe the pattern of the residuals. Do the residuals appear to be randomly scattered about a horizontal line at zero? Does the assumption of normality for the residuals seem appropriate? Paste the plot into your report and provide explanations.</li>

</ul>

<ol start="5">

 <li>Perform a simple linear regression analysis using thrust as the response variable and exhaust temperature as the predictor variable. Use the computer output to repeat parts (a) – (d) and (g) of Question 4 with exhaust temperature instead of fuel flow rate as the predictor variable. You may copy the appropriate statistics from the output to answer the questions. However, in your answer to part (g), you should include the residual plot.</li>

 <li>Compare the results of the regressions performed in Questions 4 and 5. In particular, construct a table with <em>R</em><sup>2</sup> values, the estimates of the standard deviation (<em>s</em>), the values of the <em>t</em>-statistic, and the <em>p</em>-values for each model. Which of the two models do you think is better (more reliable) at predicting thrust? Explain briefly.</li>

</ol>


