# Data-Preprocessing

There are a lot of preprocessing methods but we will mainly focus on the following methodologies:

(1) Encoding the Data - It is needed whenever we have categorical values. Encoding will assign one unique number to particular entities. Most of the time categorial values are in label form. So the computer will not consider them as features because the computer works with numbers.

(2) Normalization - It is a scaling technique in which values are shifted and rescaled so that they end up ranging between 0 and 1. It is also known as Min-Max scaling.

(3) Standardization - It is another scaling technique where the values are centered around the mean with a unit standard deviation. This means that the mean of the attribute becomes zero and the resultant distribution has a unit standard deviation.

(4) Imputing the Missing Values - Missing values can be handled by deleting the rows or columns having null values. If columns have more than half of the rows as null then the entire column can be dropped. The rows which are having one or more columns values as null can also be dropped.

(5) Discretization - It is the process through which we can transform continuous variables, models or functions into a discrete form. We do this by creating a set of contiguous intervals (or bins) that go across the range of our desired variable/model/function.

You Can Apply this Methods on other dataset also.

I used the data from [this site.](https://www.kaggle.com/anandhuh/latest-covid19-data-of-asian-countries)

I used Scikit Library for Preprocessing.
