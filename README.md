# Default of Credit Card Clients
## Helnaz Soltani
###April 10th, 2020


### Objectives:
- To perform an EDA on the dataset in order to predict the default of the credit card clients.

### Dataset information:
- Number of Instances: 30000
- Number of Attributes: 24
- Attribute Characteristics: Object
- Area: Business
- Data Set Characteristics: Multivariate
- Associated Tasks: Classification
- Date Donated: 01/26/2106

### Data cleaning:
- Duplicated entries
- Inconvenient columns name
- Incorrect datatype
- Undocumented labels for some of the features
- Inconsistent values for some of the columns

### Feature engineering:
- Credit utilization
- Number of defaults in the previous 5 months

### Exploratory data analysis:
- The clients with no default have lower credit limit for the lower range while they have higher credit limit for the higher range.
- The female clients with no default are more than the male clients.
- The educated clients with no default are more than the clients with less education.
- The single clients with no default are more than the married ones.
- The age does not seem to be a contributor, as its distribution for both categories are close. The combination of age and other attributes may be an important feature though.

### Hypothesis testing:
Hypothesis testings have been performed to determine if there is statistically significant difference between the default means for the following features:
- Sex (male vs. female)
- Marital Status (married vs. single)
- Education (educated vs. non-educated)
- Age (below and above a certain age)

### Bayesian testing:
Bayesian testing have been performed for different groups.
