# Conversion-of-Website-visitors

Challenge Description

We have data about users who hit our site: whether they converted or not as well as some of
their characteristics such as their country, the marketing channel, their age, whether they are
repeat users and the number of pages visited during that session (as a proxy for site
activity/time spent on site).
Your project is to:
  Predict conversion rate
  Come up with recommendations for the product team and the marketing team to improve conversion rate

Below is my approach to build a machine learning model. It is easy to follow and a good start for new-commers in big data area.

EDA
  Create visualization of conversion rate by entry points, key word search, actions.
  Understand data nature and factors related to conversion rate
  Data cleaning
  Aggregate data
  Deal with data missing and wrong data type

Modeling
  The idea is that using neural network's performance as baseline for logistic's performance. If logistic's performance is equal to nn's, I would select logistic model. If it is not, try to train logistic model to match nn's performance by adding interactions. Then if logistic's performance is still lower than nn's, I would choose nn.
Model evaluation
  
Metrics: AUC, gain chart and confusion matrix
Interpretation and application
