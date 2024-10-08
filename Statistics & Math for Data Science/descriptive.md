# 1.  **Descriptive Statistics**

Descriptive statistics involves summarizing and describing the basic
features of a dataset. The main goal of descriptive statistics is to
present an overall picture of data through measures of central tendency,
variability, and distribution. It uses data to provide a description of
the population through numerical calculations, graphs, or tables.
Descriptive statistics offers a concise summary of data in visual and
numerical forms.

Types of Descriptive Statistics:

## **Measures of Central Tendency** 

Measures of Central Tendency are statistical tools that help us
understand the typical value of a dataset. There are three main measures
of central tendency

1.**Mean :**

The mean is another term used to refer to average. mean is simply
computed by summing all the values in a dataset and dividing the total
sum by the number of values in the data set.

<img src="https://i.upmath.me/svg/(Mean%20%3D%20%E2%88%91x%2Fn)" alt="(Mean = ∑x/n)" />

**Example:** If we have the dataset {2, 4, 6, 8, 10}, the mean would be
(2 + 4 + 6 + 8 + 10) / 5 = 30 / 5 = 6

2.**Median :**

The median is the middle value when data are arranged in ascending or
descending order. If the number of values is even, the median is taken
to be the average of the two values in the middle.

**If n is Even:**
<img src="https://i.upmath.me/svg/(Median%20%3D%20%5C%5B(n%2F2)th%C2%A0term%20%2B%20(n%2F2%20%2B%201th%C2%A0term%5C%5D%2F2))" alt="(Median = \[(n/2)th term + (n/2 + 1th term\]/2))" />

**If n is Odd:** 

<img src="https://i.upmath.me/svg/(Median%20%3D%20(n%20%2B%201)%2F2)" alt="(Median = (n + 1)/2)" />

Example: If we have the set of numbers {1, 3, 5, 7, 9}, its median would
be 5 because it is the middle number. If the set is {1, 2, 3, 4, 5, 6},
then the median would fall on (3 + 4) / 2 = 3.5.

3.**Mode :**

It is the value that is most constantly arrived at in the sample set.
The actual value that comes out repeatedly most of the time in the
central set is called the mode.

**Mode=occurs most frequently**

Example : {2, 3, 4, 2, 4, 6, 4, 7, 7, 4, 2, 4}

4 is the most frequently occurring term in this dataset. Thus, mode is
4.


## **Measure of Variability**

Measures of Variability, also known as measures of dispersion, describe
the spread of data in a sample or population. These statistical tools
help us explore and quantify the variation within a dataset.
Understanding this variability is crucial, as it provides important
insights into the characteristics of the data at hand.

1.**Range of Data :**

The simplest measure of variability, range is calculated simply as the
difference between the largest and smallest values in a dataset.

**Range = Maximum value - Minimum value**

**Example:** If we have the dataset {2, 4, 6, 8, 10}, the range would be
10 - 2 = 8.

2.**Variance :**

Variance determines how much individual data varies from its mean finding out the expected difference of
deviation from the actual value. Hence, variance depends on the standard
deviation of a given data set.The larger the value of variance, the data
is more scattered from its mean and if the value of variance is low or
minimum, then it is less scattered from the mean. Hence, it is called a
measure of the spread of data from mean.

The formula for population variance is 

**σ2 = ∑i=1(xi − μ)2/N**
- σ2: The symbol for population variance, read as \"sigma squared\" 
- N: The size of the population 
- μ: The population mean

The formula for sample variance is 
<img src="https://i.upmath.me/svg/(%CF%832%C2%A0%3D%20%E2%88%91%20(x%20%E2%88%92%20x%CC%85)2%C2%A0%2F%20n%20%E2%88%92%201)" alt="(σ2 = ∑ (x − x̅)2 / n − 1)" />

Where: n is the sample size

**Example:** If we have the dataset {2, 4, 6, 8, 10} with a mean of 6,
the variance would be <img src="https://i.upmath.me/svg/(%5B(2-6)%C2%B2%20%2B%20(4-6)%C2%B2%20%2B%20(6-6)%C2%B2%20%2B%20(8-6)%C2%B2%20%2B%20(10-6)%C2%B2%5D%20%2F%0A(5%20-%201)%20)" alt="([(2-6)² + (4-6)² + (6-6)² + (8-6)² + (10-6)²] /
(5 - 1) )" /> = <img src="https://i.upmath.me/svg/(16%20%2F%204)" alt="(16 / 4)" /> = <img src="https://i.upmath.me/svg/4" alt="4" />

3.**Standard Deviation :**

Standard deviation is a statistical measure that indicates the amount of
variation or dispersion of some set of values. In other words, it\'s
that measure which tells how spread out values are from its mean value.
The standard deviation is the square root of variance; an average of
squared differences from the mean.

The standard deviation is the measure of indicating dispersion in a
dataset relative to its mean

**σ = √\[(Σ(xi - μ)²) / (n - 1)\]**

Where:

-   σ = standard deviation

-   xi = each value in the dataset

-   μ = mean of the dataset

-   n = number of values in the dataset

## **Measures of Shape**

Measures of Shape are an important aspect of descriptive statistics, as
they help us understand the distribution of a dataset.

1.  **Skewness :**

Skewness is the measure of asymmetry in the distribution of a dataset.
It indicates the way in which the data deviates from the mean value. A
perfectly symmetrical distribution has skewness equal to zero. Positive
skewness means that the distortion is toward the right; it means that it
contains more extreme values on the right side of the distribution
curve. By definition, a left-skewed distribution will have a negative
value of skewness because most of the extreme values are falling to the
left.

![Skewness](https://raw.githubusercontent.com/AIDataFoundation/Before-ML/main/Statistics%20%26%20Math%20for%20Data%20Science/image/Skewness_1.webp)


-   Positive Skewness: Data is said to be skewed to the right-that is,
    extreme values are to the right of the distribution. The level of
    skew is always \> 0.

-   Negative Skewness: When extreme values fall to the left of the
    distribution, data is said to be left-skewed. It is always \<0.

-   Zero Skewness: Distribution is perfectly symmetrical, and the level
    of skew is zero.

Skewness can be interpreted as follows:

-   A skewness of 0 indicates perfect symmetry.

-   A skewness between -1 and 1 indicates moderate skewness.

-   A skewness greater than 1 or less than -1 indicates high skewness

**Skewness = (Σ(xi - μ)\^3) / (n \* σ\^3)**

Where:

-   xi is each individual data point

-   μ is the mean of the dataset

-   n is the number of data points

-   σ is the standard deviation of the dataset

2.  **Kurtosis :**

Kurtosis is the \"tailedness\" of a distribution. It is a descriptor of
the distribution of data in the tails of the distribution. High kurtosis
indicates that the data has heavy tails, meaning that there is a larger
portion of data points in the tail. Low kurtosis means light tails,
indicating fewer extreme values are in the tail of the data.

![kurtosisi](https://raw.githubusercontent.com/AIDataFoundation/Before-ML/main/Statistics%20%26%20Math%20for%20Data%20Science/image/Kurtosis1.webp)

-   Platykurtic: This distribution has light tails, with fewer extreme
    values in the tails of the distribution.

-   Mesokurtic: A mesokurtic distribution has normal tails, with a
    moderate number of extreme values.

-   Interpretation of Kurtosis

Following is how one interprets the kurtosis:

-   A kurtosis of 3 states that the distribution is normal.

-   A kurtosis above 3 indicates leptokurtosis or heavy tails.

-   A kurtosis below 3 indicates platykurtosis or light tails.

**Kurtosis = (Σ(xi - μ)\^4) / (n \* σ\^4)**

Where:

-   xi is each individual data point

-   μ is the mean of the dataset

-   n is the number of data points

-   σ is the standard deviation of the dataset

## **Measures of position**

The position measures refer to the statistical measures used in
describing the position or location that a value occupies in a dataset.
These measures are employed to specify the relative position of a value
within a dataset and find their common application in combination with
measures of central tendency and variability.

1.  **Percentiles :**

Percentiles are measures of position that divide a data set into 100
equal parts. Hence, each percentile represents the percentage of the
data below a certain value. Percentiles are useful to describe the
distribution of the data and occurrence of outliers.

-   25th Percentile or (Q1): Below this value, lies 25% of the data.

-   50th Percentile (Q2) or Median: The value below which 50% of the data
    falls.

-   75th Percentile (Q3): The value below which 75% of the data falls.

<img src="https://i.upmath.me/svg/(P%20%3D%20(n%20%5C*%20(k%2F100))%20%2B%20(1%2F2))" alt="(P = (n \* (k/100)) + (1/2))" />

Where:

-   P = percentile value

-   n = number of observations in the dataset

-   k = percentile rank

2.  **Quartile :**

Quartiles divide the entire set into four equal parts. So, there are
three quartiles, first, second and third represented by Q1, Q2 and Q3,
respectively. Q2 is nothing but the median, since it indicates the
position of the item in the list and thus, is a positional average. In
order to find quartiles of a group of data, we have to arrange the data
in ascending order.

<img src="https://i.upmath.me/svg/(Q1%C2%A0%3D%20%5C%5B(n%2B1)%2F4%5C%5Dth%20item)" alt="(Q1 = \[(n+1)/4\]th item)" />

<img src="https://i.upmath.me/svg/(Q2%C2%A0%3D%20%5C%5B(n%2B1)%2F2%5C%5Dth%20item)" alt="(Q2 = \[(n+1)/2\]th item)" />

<img src="https://i.upmath.me/svg/(Q3%C2%A0%3D%20%5C%5B3(n%2B1)%2F4%5C%5Dth%20item)" alt="(Q3 = \[3(n+1)/4\]th item)" />

**Interquartile Range :**

It is the difference between the upper and lower quartile of a given
data set and sometimes may be referred to as midspread. The
interquartile range is a measure of statistical dispersion and is the
difference between the upper and lower quartiles. It is also a measure
of variation in which one divides a data set into quartiles. If Q1 is
the first quartile and Q3 is the third quartile, then formula IQR is
given by;

<img src="https://i.upmath.me/svg/(IQR%20%3D%20Q3%20--%20Q1)" alt="(IQR = Q3 -- Q1)" />

3. **Deciles**

- Deciles are percentiles that divide data into ten equal parts.
- Successive deciles are each 10% increment of the data. 
- For example, the first decile, D1 would be the lowest 10% in the dataset, while the tenth
decile, D10 represents the top 10% percentage.