## Default of Credit Card Clients
### Helnaz Soltani            April 10th, 2020


### Objectives:
- To perform an EDA on the dataset in order to predict the default of the credit card payments.

### Dataset information:
- Number of Instances: 30000
- Number of Attributes: 24
- Attribute Characteristics: Object
- Area: Business
- Data Set Characteristics: Multivariate
- Associated Tasks: Classification
- Date Donated: 01/26/2106

### Data cleaning:
- 35 entries were duplicated, so I removed them.
- The columns name were not clear, so I rename them.
- The data types were not consistent, so I changed them. Changing the data tyeps from "object" to "int32" reduced the usage memory from 5.7MB to 3MB.
- No null value was observed.
- The columns "education" and "marital_status" had values out of the range of the documented values. Since they were at most 1% of the total dataset, I removed them.
- The columns "'pay_status_month" (month from Apr to Sep) were not reported consistently. So I reproduced them base on the data in other columns.
- "default_sum" is the column that I am going to use as a metric for the number of the defaults for each instance. Therefore, the unnccessary columns were removed.

### Exploratory data analysis:
- The higher the education, the more the credit line. education = 4 is not clear though.
- The sex attribute does not have any correlation with the credit limit.
- Married clients seem to have higher credit line. That makes sense as the credit_line attribute includes the individual consumer credit and his/her family (supplementary) credit.
- There is no significant correlation between age and the credit limit.
- The clients with no default have lower credit line for the lower range while they have higher credit line for the lower range.
- The female clients with no default are more than the male clients.
- The educated clients with no default are more than the clients with less education.
- The single clients with no default are more than the married ones.
- The age does not seem to be a contributor, as its distribution for both categories are close. The combination of age and other attributes may be an important driver though.

### Hypothesis testing:

### Explanatory data analysis:
