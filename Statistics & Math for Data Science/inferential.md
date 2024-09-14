# 2.  **Inferential statistics**
Inferential statistics is a subfield of statistics that focuses on drawing conclusions or making predictions about a larger group (population) through a smaller group (sample) of individuals based on some information collected from them. By applying different methods in statistics, it enables one to make assumptions regarding the main features of people’s lives like population average, percentage and relationship among variables using a limited set of observed values.
## 1.**Hypothesis Testing**
Hypothesis testing involves making decisions about a population parameter based on sample data. It generally consists of stating a null hypothesis, often denoted as H0, and an alternative hypothesis, often denoted as Ha, in addition to collecting sample data and then using statistical tests to see whether there is enough evidence to reject the null hypothesis in favor of the alternative hypothesis.
- Null Hypothesis(H0): This is a general statement or default position of two measured cases where nothing has happened. In other words, there is no relationship between them, or no relationship among groups. It means a basic assumption or made based on the problem knowledge.
- Alternative hypothesis (H1):The alternative hypothesis represents the alternative being tested in the hypothesis testing and is opposite to null hypothesis.

**Step to testing Hypothesis Testing**

- **Level of significance** : It is the amount of confidence that we want on accepting or rejecting the null hypothesis. While accepting the hypothesis, we can't gain 100% accuracy. Normally consider the significance level as 5%. Usually, α = 0.05 or 5% which states that with 95% confidence level, the output would be same for any kind of sample population.
- **p-value**: The probability of obtaining the observed/ extreme results, assuming that the null hypothesis H0 is true. If the p-value obtained is less than the significance level, then we reject the null hypothesis.
- **Test Statistic**: The numerical value computed from the sample data in testing a hypothesis, which is compared to the rejection region or critical values to decide whether to reject the null hypothesis.
- **Critical Value**: The value of a test statistic that a null hypothesis is rejected if the value of test statistic either greater than or less than.

- **Degree of Freedom**: The degree of freedom pertains to the variability or freedom one has in estimating a parameter. It is related to sample size and determines the shape of the distribution.

**type of Hypotheis Testing**
- **Single-tailed test**

    - **Left-Tailed or Left-Sided Test**: The alternative hypothesis offers the statement that the true value of the parameter is less than the null hypothesis.Example: <img src="https://i.upmath.me/svg/(H0%E2%80%8B%3A%0A%CE%BC%E2%89%A550)" alt="(H0​:
μ≥50)" /> and <img src="https://i.upmath.me/svg/(H1%3A%20%CE%BC%3C50)" alt="(H1: μ&lt;50)" />
    - **Right-Tailed (Right-Sided) Test**: This type of test represents that the alternative hypothesis asserts that the actual value of the parameter is greater than the value included in the null hypothesis. 
    Example: <img src="https://i.upmath.me/svg/(H0%20%3A%20%CE%BC%E2%89%A450)" alt="(H0 : μ≤50)" /> and <img src="https://i.upmath.me/svg/(H1%3A%CE%BC%3E50)" alt="(H1:μ&gt;50)" />
- **Two-Tailed Test**
A two-tailed test takes into account both the greater than and less than in direction against a given value. We use a two-tailed test when there isn't any explicit expectation in either direction and we want to find out any significant difference.
Example: H0: μ= 50 and H1: μ≠50

![Sample Image](./image/one%20side%20and%20two%20side%20tailed%20hypotheiss.jpeg)

**Test Statistic:**

- **Z-test**: Widely used in cases when the sample size is greater and the standard deviation of the population is known. Employed during the comparison between different samples or groups to draw inductive interference for populations. Emphasis on the probability of observing data given that some premises or hypotheses are valid. Provide a framework for assessing the evidence supporting as well as opposing a specific.

   <img src="https://i.upmath.me/svg/(Z%20%3D%20(x%20%E2%80%93%20%CE%BC)%20%2F%20(%CF%83%20%2F%20sqrt(n)))" alt="(Z = (x – μ) / (σ / sqrt(n)))" />

    Where

    Z is the test statistic

    x is the sample mean

    μ is the hypothesized population mean

    σ is the population standard deviation

    n is the sample 

- **T-Test**: A test applied for finding a significant difference between the means of two groups. It is a test most often used when data is normally distributed and the population variances are unknown. T-test is one of the test procedures in hypothesis testing in which it tests whether a difference between two groups really exists, or is it because of chance.

<img src="https://i.upmath.me/svg/(t%20%3D%20%5Cfrac%7B%5Cbar%7BX%7D%20-%20%5Cmu%7D%7B%5Cfrac%7Bs%7D%7B%5Csqrt%7Bn%7D%7D%7D)" alt="(t = \frac{\bar{X} - \mu}{\frac{s}{\sqrt{n}}})" />


- **Chi-square test**: The Chi-square test is a statistic utilized in an attempt to prove the existence of any significant relationship between two nominal measures. It has a very broad application in testing whether two variables are independent and the differences between observed frequencies in a contingency table and frequencies that would be expected under independence.

**P-value**

P-Value Interpretation

- **P-value > 0.05**: The result is not statistically significant, so do not reject the null hypothesis.
  
- **P-value < 0.05**: The result is statistically significant. Generally, reject the null hypothesis in favor of the alternative hypothesis.

- **P-value < 0.01**: The result is highly statistically significant, thus reject the null hypothesis in favor of the alternative hypothesis.

**Type I & Type II Errors** 

**Type 1 Error (α-error)**

A type 1 error, also called an α-error, happens when a true null hypothesis is rejected. In other words, this means that there is a statistically significant difference or relationship found by the test when the reality is that there is no real difference or relationship.

**Type 2 Error (β-error)**

A Type 2 error, which occurs when a false null hypothesis is not rejected, is also called the β-error. This relates to the failure of a test in finding a difference or relationship that is statistically significant when, actually, there is a real difference or relationship.

![](./image/type-1-and-2-errors.webp)


## 2.**Regression**
Regression is a statistical analysis used for determining the relationship between two or more variables. It involves modeling the relationship between a dependent variable, known as the outcome variable, and one or more independent variables, also known as predictor variables.

**Important Concepts in Regression Analysis**

- **Dependent Variable (y)**: This is the variable of interest that you want to predict or explain.
- **Independent Variable(s) x**: The variable used to predict the dependent variable.
- **Regression Coefficient:** It is the change in the dependent variable, which occurs for one unit of variation in the independent variable.
- **Intercept (α):** The value of the dependent variable when the independent variable is zero.
- **Coefficient of Determination (R squared):** Describes what percentage of the variation in the dependent variable is determined (or explained) by the independent variables.\

**Types of Regression Analysis** 

1. **Simple Linear regression:** Simple linear regression is a type of regression that is used when a single independent variable predicts a dependent variable.

   <img src="https://i.upmath.me/svg/(%20Y%20%3D%20a%20%2B%20bX)" alt="( Y = a + bX)" />
where,
<img src="https://i.upmath.me/svg/(Y)" alt="(Y)" /> is the dependent variable.
<img src="https://i.upmath.me/svg/(X)" alt="(X)" /> is the independent variable.
<img src="https://i.upmath.me/svg/(a)" alt="(a)" /> is the intercept, which marks the value of <img src="https://i.upmath.me/svg/(Y)" alt="(Y)" /> when <img src="https://i.upmath.me/svg/(X)" alt="(X)" /> = 0.
b is the slope showing the change in <img src="https://i.upmath.me/svg/(Y)" alt="(Y)" /> given a one-unit change in <img src="https://i.upmath.me/svg/(X)" alt="(X)" />.

2. **multiple regression:** In multiple regression, the linear regression is extended to include more than one independent variable to predict the dependent variable. It takes the form 
    
    <img src="https://i.upmath.me/svg/(Y%20%3D%20a%20%2B%20b%E2%82%81X%E2%82%81%20%2B%20b%E2%82%82X%E2%82%82%20%2B.%20%2B%20b%E2%82%99X%E2%82%99)" alt="(Y = a + b₁X₁ + b₂X₂ +. + bₙXₙ)" />
    where,
    <img src="https://i.upmath.me/svg/(Y)" alt="(Y)" /> = dependent variable,
    <img src="https://i.upmath.me/svg/((X%E2%82%81)%2C%20(X%E2%82%82)%2C%20.%2C%20(X%E2%82%99))" alt="((X₁), (X₂), ., (Xₙ))" /> = independent variables,
    <img src="https://i.upmath.me/svg/(a)" alt="(a)" /> = intercept, and
    <img src="https://i.upmath.me/svg/(b%E2%82%81%2C%20b%E2%82%82%2C%20.%2C%20b%E2%82%99)" alt="(b₁, b₂, ., bₙ)" /> = independent variable coefficients.
3. **Non-Linear Regression :** Non-Linear Regression is a statistical technique used to model relationships where the connection between independent variable <img src="https://i.upmath.me/svg/(s)" alt="(s)" /> and the dependent variable is not linear. This approach is necessary when a linear model does not adequately describe the data.
- **Polynomial Regression**
Polynomial Regression uses a polynomial equation to model the relationship between the variables.

    **Formula:**
    <img src="https://i.upmath.me/svg/(y%20%3D%20%CE%B2%E2%82%80%20%2B%20%CE%B2%E2%82%81x%20%2B%20%CE%B2%E2%82%82x%C2%B2%20%2B%20...%20%2B%20%CE%B2%E2%82%99x%E2%81%BF%20%2B%20%CF%B5)" alt="(y = β₀ + β₁x + β₂x² + ... + βₙxⁿ + ϵ)" />

<img src="https://i.upmath.me/svg/(y)" alt="(y)" /> : Dependent variable

<img src="https://i.upmath.me/svg/(x)" alt="(x)" /> : Independent variable

<img src="https://i.upmath.me/svg/(%CE%B2%E2%82%80%2C%20%CE%B2%E2%82%81%2C%20...%2C%20%CE%B2%E2%82%99)" alt="(β₀, β₁, ..., βₙ)" />: Coefficients

<img src="https://i.upmath.me/svg/(n)" alt="(n)" />: Degree of the polynomial

(ϵ): Error term
- **Logarithmic Regression**
Logarithmic Regression uses a logarithmic equation to model the relationship, applying the natural logarithm to the independent variable.

    **Formula:**
    <img src="https://i.upmath.me/svg/(y%3D%CE%B20%2B%CE%B21ln(x)%2B%CF%B5)" alt="(y=β0+β1ln(x)+ϵ)" />

<img src="https://i.upmath.me/svg/(ln(x))" alt="(ln(x))" /> : Natural logarithm of the independent variable x

<img src="https://i.upmath.me/svg/(%CE%B2%E2%82%80)" alt="(β₀)" /> : Intercept

<img src="https://i.upmath.me/svg/(%CE%B2%E2%82%81)" alt="(β₁)" /> : Coefficient for the logarithmic term

<img src="https://i.upmath.me/svg/(%CF%B5)" alt="(ϵ)" /> : Error term
- **Exponential Regression**
Exponential Regression models the relationship using an exponential function, capturing growth or decay.

    **Formula:**
    <img src="https://i.upmath.me/svg/(y%3D%CE%B20%E2%88%97e(%CE%B21%E2%88%97x)%2B%CF%B5)" alt="(y=β0∗e(β1∗x)+ϵ)" />

<img src="https://i.upmath.me/svg/(e)" alt="(e)" />: Euler's number (approximately 2.718)

<img src="https://i.upmath.me/svg/(%CE%B2%E2%82%80)" alt="(β₀)" /> : Coefficient

<img src="https://i.upmath.me/svg/(%CE%B2%E2%82%81)" alt="(β₁)" /> : Rate of growth or decay

<img src="https://i.upmath.me/svg/(%CF%B5)" alt="(ϵ)" /> : Error term.

4. **Logistic Regression**

Logistic Regression is a type of regression analysis used for binary outcome variables (e.g., 0/1, yes/no). It is commonly used in situations where the dependent variable is a binary outcome
Logistic Regression uses a logistic function to model the probability of the dependent variable being in one of the two categories. The logistic function is an S-shaped curve that maps the input values to probabilities between 0 and 1.

**Logistic Function:** The core of logistic regression is the logistic function (also known as the sigmoid function), which maps any real-valued number into the range of 0 to 1. The formula for the logistic function is:

<img src="https://i.upmath.me/svg/(%5Csigma(z)%20%3D%20%5Cfrac%7B1%7D%7B1%20%2B%20e%5E%7B-z%7D%7D)" alt="(\sigma(z) = \frac{1}{1 + e^{-z}})" />

Where:
- <img src="https://i.upmath.me/svg/(%20%5Csigma(z)%20)" alt="( \sigma(z) )" /> is the value of the logistic function for input <img src="https://i.upmath.me/svg/(%20z%20)" alt="( z )" />.
- <img src="https://i.upmath.me/svg/(%20z%20)" alt="( z )" /> is a real-valued number, typically a linear combination of predictor variables.
- <img src="https://i.upmath.me/svg/(%20e%20)" alt="( e )" /> is the base of the natural logarithm (approximately equal to 2.71828).



**Key Concepts**

**Odds Ratio**

The **odds ratio** measures the change in the odds of the dependent variable being in one of the two categories for a one-unit change in the independent variable. It is a measure of association between an exposure and an outcome. 

- **Interpretation**: An odds ratio greater than 1 indicates that as the independent variable increases, the odds of the dependent variable being in the "success" category increase. An odds ratio less than 1 indicates a decrease in the odds.

**Logit**

The **logit** is the logarithm of the odds ratio and is used to model the relationship between the independent variable(s) and the dependent variable. It is expressed as:

<img src="https://i.upmath.me/svg/(%5Ctext%7Blogit%7D(p)%20%3D%20%5Clog%5Cleft(%5Cfrac%7Bp%7D%7B1%20-%20p%7D%5Cright))" alt="(\text{logit}(p) = \log\left(\frac{p}{1 - p}\right))" />

Where:
- <img src="https://i.upmath.me/svg/(%20p%20)" alt="( p )" /> is the probability of the dependent variable being in the "success" category.
- <img src="https://i.upmath.me/svg/(%20%5Cfrac%7Bp%7D%7B1%20-%20p%7D%20)" alt="( \frac{p}{1 - p} )" /> represents the odds of the dependent variable being in the "success" category.
- <img src="https://i.upmath.me/svg/(%20%5Clog%20)" alt="( \log )" /> denotes the natural logarithm.

5. **Poisson Regression**

**Overview**

Poisson regression is a type of regression analysis used for count data, such as the number of accidents or events occurring in a fixed interval of time or space. It is suitable for modeling count data when the dependent variable represents the number of times an event occurs.

Poisson regression uses a Poisson distribution to model the count data. The Poisson distribution is a discrete distribution that describes the probability of a given number of events occurring within a fixed interval.

**Key Concepts**

**Lambda (λ)** represents the average rate of events occurring in a fixed interval of time or space. It is the parameter of the Poisson distribution and indicates the expected number of events per interval.

- **Interpretation**: A higher lambda value indicates a higher average rate of events.

**Exposure** refers to the amount of time or space over which the events occur. In Poisson regression, exposure is often used to adjust the count data to account for varying lengths of observation time or different areas of space.

- **Adjustment**: The model adjusts the count data based on the exposure to ensure accurate estimates of the event rates.

**Poisson Regression Model**

The Poisson regression model can be expressed as:

<img src="https://i.upmath.me/svg/(%5Clog(%5Clambda)%20%3D%20%5Cbeta_0%20%2B%20%5Cbeta_1X_1%20%2B%20%5Cbeta_2X_2%20%2B%20%5Ccdots%20%2B%20%5Cbeta_nX_n)" alt="(\log(\lambda) = \beta_0 + \beta_1X_1 + \beta_2X_2 + \cdots + \beta_nX_n)" />

Where:
- <img src="https://i.upmath.me/svg/(%20%5Clambda%20)" alt="( \lambda )" /> is the expected count of events.
- <img src="https://i.upmath.me/svg/(%20%5Cbeta_0%20)" alt="( \beta_0 )" /> is the intercept.
- <img src="https://i.upmath.me/svg/(%20%5Cbeta_1%2C%20%5Cbeta_2%2C%20%5Cldots%2C%20%5Cbeta_n%20)" alt="( \beta_1, \beta_2, \ldots, \beta_n )" /> are the coefficients for the predictor variables <img src="https://i.upmath.me/svg/(%20X_1%2C%20X_2%2C%20%5Cldots%2C%20X_n%20)" alt="( X_1, X_2, \ldots, X_n )" />.

## **Confidence Intervals**
A confidence interval is a range of values within which the true population parameter is likely to lie. It provides a statistical tool to estimate the population parameter with a certain level of confidence, incorporating a margin of error.


**Sample Statistic**

The **sample statistic** is a characteristic of the sample, such as the sample mean or sample proportion. It is used as an estimate of the population parameter.

**Standard Error**
The standard error is a measure of the variability or dispersion of the sample statistic. It quantifies how much the sample statistic is expected to fluctuate from one sample to another.

- **Calculation**: For the sample mean, the standard error is calculated as:
  <img src="https://i.upmath.me/svg/(%5Ctext%7BSE%7D%20%3D%20%5Cfrac%7B%5Csigma%7D%7B%5Csqrt%7Bn%7D%7D)" alt="(\text{SE} = \frac{\sigma}{\sqrt{n}})" />
  where <img src="https://i.upmath.me/svg/(%20%5Csigma%20)" alt="( \sigma )" /> is the population standard deviation and <img src="https://i.upmath.me/svg/(%20n%20)" alt="( n )" /> is the sample size.

**Margin of Error**

The margin of error is the maximum amount by which the sample statistic may differ from the true population parameter. It is determined based on the standard error and the desired confidence level.

- **Calculation**: The margin of error (ME) is calculated as:
  <img src="https://i.upmath.me/svg/(%5Ctext%7BME%7D%20%3D%20%5Ctext%7BCritical%20Value%7D%20%5Ctimes%20%5Ctext%7BStandard%20Error%7D)" alt="(\text{ME} = \text{Critical Value} \times \text{Standard Error})" />
  
where the Critical Value depends on the confidence level (e.g., 1.96 for a 95% confidence level).

**Confidence Level**

The confidence level is the probability that the confidence interval contains the true population parameter. It reflects how certain we are that the interval covers the true parameter.

- **Common Levels**: 90%, 95%, and 99%.
- **Interpretation**: A 95% confidence level means that if we were to take many samples and construct confidence intervals for each, approximately 95% of those intervals would contain the true population parameter.

**Confidence Interval Formula**

For a mean, the confidence interval is calculated as:

<img src="https://i.upmath.me/svg/(%5Ctext%7BCI%7D%20%3D%20%5Cbar%7Bx%7D%20%5Cpm%20(%5Ctext%7BCritical%20Value%7D%20%5Ctimes%20%5Ctext%7BSE%7D))" alt="(\text{CI} = \bar{x} \pm (\text{Critical Value} \times \text{SE}))" />

Where:
- <img src="https://i.upmath.me/svg/(%20%5Cbar%7Bx%7D%20)" alt="( \bar{x} )" />  is the sample mean.
- **Critical Value** is based on the chosen confidence level (e.g., 1.96 for 95% confidence).
- **SE** is the standard error of the mean.

##  **Correlation**

Correlation One process for establishing the relationships between two variables. You learned one way to get a general idea about whether or not two variables are related, is to plot them on a "scatter plot". While there are many measures of association for variables which are measured at the ordinal or higher level of measurement, correlation is the most commonly used approach.


Correlation applies to ordinal, interval, and ratio variables but is not suitable for nominal variables.

The **Correlation Coefficient**, often represented as r, is a statistical measure that quantifies the strength and direction of the linear relationship between two variables. It takes values between -1 and 1

r=1 indicates a perfect positive correlation, meaning as one variable increases, the other also increases in a perfectly linear manner.

r=−1 indicates a perfect negative correlation, meaning as one variable increases, the other decreases in a perfectly linear manner.

r=0 indicates no linear relationship between the variables.

**KEY POINTS:**
**Positive correlation:** As one variable increases, the other tends to increase.

**Negative correlation:** As one variable increases, the other tends to decrease.

**Magnitude:** The closer r is to 1 or -1, the stronger the relationship; the closer r is to 0, the weaker the relationship.

The formula for Pearson's correlation coefficient is:

<img src="https://i.upmath.me/svg/(r%20%3D%20%5Cfrac%7Bn(%5Csum%20xy)%20-%20(%5Csum%20x)(%5Csum%20y)%7D%7B%5Csqrt%7B%5Bn%20%5Csum%20x%5E2%20-%20(%5Csum%20x)%5E2%5D%5Bn%20%5Csum%20y%5E2%20-%20(%5Csum%20y)%5E2%5D%7D%7D)" alt="(r = \frac{n(\sum xy) - (\sum x)(\sum y)}{\sqrt{[n \sum x^2 - (\sum x)^2][n \sum y^2 - (\sum y)^2]}})" />

Where:
- <img src="https://i.upmath.me/svg/(%20n%20)" alt="( n )" /> is the number of data points.
- <img src="https://i.upmath.me/svg/(%20x%20)" alt="( x )" /> and <img src="https://i.upmath.me/svg/(%20y%20)" alt="( y )" /> are the two variables being compared.
- <img src="https://i.upmath.me/svg/(%20sum%20xy%20)" alt="( sum xy )" /> is the sum of the product of paired values.
- <img src="https://i.upmath.me/svg/(%20sum%20x%20)" alt="( sum x )" /> is the sum of the <img src="https://i.upmath.me/svg/(%20x%20)" alt="( x )" /> -values.
- <img src="https://i.upmath.me/svg/(%20sum%20y%20)" alt="( sum y )" /> is the sum of the <img src="https://i.upmath.me/svg/(%20y%20)" alt="( y )" /> -values.
- <img src="https://i.upmath.me/svg/(%20sum%20x%5E2%20)" alt="( sum x^2 )" /> is the sum of squared <img src="https://i.upmath.me/svg/(%20x%20)" alt="( x )" /> -values.
- <img src="https://i.upmath.me/svg/(%20sum%20y%5E2%20)" alt="( sum y^2 )" /> is the sum of squared <img src="https://i.upmath.me/svg/(%20y%20)" alt="( y )" /> -values.

The strength of the correlation is classified as follows:

- **Strong Correlation**: <img src="https://i.upmath.me/svg/(%20%7Cr%7C%20%3E%200.7%20)" alt="( |r| &gt; 0.7 )" />
  - Indicates a strong linear relationship between the variables.
- **Moderate Correlation**: <img src="https://i.upmath.me/svg/(%200.3%20%3C%20%7Cr%7C%20%5Cleq%200.7%20)" alt="( 0.3 &lt; |r| \leq 0.7 )" />
  - Indicates a moderate linear relationship between the variables.
- **Weak Correlation**: <img src="https://i.upmath.me/svg/(%20%7Cr%7C%20%5Cleq%200.3%20)" alt="( |r| \leq 0.3 )" />
  - Indicates a weak linear relationship between the variables.


