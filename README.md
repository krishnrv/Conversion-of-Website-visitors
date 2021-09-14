# Conversion-of-Website-visitors

Challenge Description

We have data about users who hit our site: whether they converted or not as well as some of
their characteristics such as their country, the marketing channel, their age, whether they are
repeat users and the number of pages visited during that session (as a proxy for site
activity/time spent on site).
# country : user country based on the IP address
#age : user age. Self-reported at sign-in step
#new_user : whether the user created the account during this session or had already an
#account and simply came back to the site
#source : marketing channel source
#Ads: came to the site by clicking on an advertisement
#Seo: came to the site by clicking on search results
#Direct: came to the site by directly typing the URL on the browser
#total_pages_visited: number of total pages visited during the session. This is a proxy for
#time spent on site and engagement during the session.
#converted: this is our label. 1 means they converted within the session, 0 means they left without buying anything. 
#The company goal is to increase conversion rate: # conversions / total sessions.

Our project is to:
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
  
Metrics: AUCand confusion matrix
Interpretation and application
