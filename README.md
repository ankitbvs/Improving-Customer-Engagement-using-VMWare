# Improving-Customer-Engagement-using-VMWare

# Predicting Net Promoter Score(NPS) using Manipal Dataset

![alt text](vm.PNG)

### Table of contents
* [Introduction](#introduction)
* [Problem Statement](#problem-statement)
* [Data Source](#data-source)
* [Technologies](#technologies)
* [Type of Data](#type-of-data)
* [Data Pre-processing](#data-pre-processing)
* [Algorithms Implemented](#algorithms-implemented)
* [Steps Involved](#steps-involved)
* [Evaluation Metrics](#evaluation-metrics)
* [Results and Conclusion](#results-and-conclusion)

### Introduction
Analyzed customer data of 50K+ customers with 700+ variables to improve the conversion rate of visitors to customers. Improved the customer engagement using VMWare dataset.

### Problem Statement
* Improve Customer engagement using VMWare dataset

### Data Source
* The Dataset was released by IIM Bangalore.

### Technologies
* R Programming

### Type of Data
* The data set contains 50K+ records and 700+ variables
* Train : 70%
* Test  : 30%

### Data Pre-processing
* Handling missing values
* Dealing with Outliers
* Removing variables having zero variance

### Algorithms Implemented
* Random Forest
* XGBoost
* LASSO Regression
* Ridge Regression

### Steps Involved

* Find out which are the significant variables in the dataset and store them in a separate dataframe.
* Find out the TOP 200 important variables by running Random Forest
* Filter some more variables using XGBoost and LASSO.
* Finally with the final set of variable, run prediction models and obtain the results.
  
### Evaluation Metrics  
Accuracy 

### Results and Conclusion 

Below are some of the things which we have leant on account of our analysis - 

* Out of all classes, it is more likely that one would visit the website but no actions would be taken. But there is a fair class of people, who are possibly the potential customers, would visit the website and explore excluding download, seminar/webinar, Hands on Lab. And there are other class people who register the HOL without performing any actions on website. Hence it is important to capture the attention of those customers who fall under the target code -1 and ensure they are attended well over website with all the information they are seeking for.

* The main help that the marketing and sales department would get from this propensity to respond model is that the potential sales leads would be efficiently identified by the team and improved targeted personalized marketing would enhance customer’s website experience by increasing the website engagement of the customer which would also increase the brand value in the customer’s mind.

* The model developed would help the team predict the customers who would choose particular actions along with the order in which the digital action should be pushed to the identified target customers to increase engagement with the brand. This would lead them to retarget the potential buyers of a particular product/service offered by the firm. Due to the above, the productivity of the team and the sales of the brand would increase leading to higher profitability and market share.



