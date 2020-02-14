# SPARKIFY-CAPSTONE
# Description
Predict customer churn with PySpark for an imaginary digital music service called Sparkify. Sparkify has a free-tier and a premium subscription plan. Users can upgrade, downgrade or cancel their service at any time. Churn means downgradding from premium to free tier or cancelling the service. If we can predict users who will churn, the company can offer them discounts and incentives to entice them to stay.
# Installation
    This project uses the following software and Python libraries:

    Python

    Spark

    Pyspark

    pandas

    Matplotlib

    Seaborn

    You will also need to have software installed to run and execute a Jupyter Notebook.

  If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already   has the above packages and more included. And for Spark, you can do this using AWS or IBM Cloud.

# Project Motivation
This is udacity's capstone project, using spark to analyze user behavior data from music app Sparkify.

Sparkify is a music app, this dataset contains two months of sparkify user behavior log. The log contains some basic information about the user as well as information about a single action. A user can contain many entries. In the data, a part of the user is churned, through the cancellation of the account behavior can be distinguished.

# Files Description
Sprakify .ipynb Main file of the project, it demonstrates the process of using pyspark to explore the data and build the model.
# Result
According to the results of the model, it is the frequency of Thumbs Down that has the greatest impact. Churn users have more Thumbs Down. Naturally, users will leave if they are not satisfied.
The machine learning modeling has a success in predicting the customer's churn activity. That can help the application owners to improve the user lifetime. Despite the relatively good results of other selected machine learning models such as SVM and Decision Trees, the GBT algorithm is selected and tuned with hyperparameters. For a future work, the Random Forest algorithm can be adjusted with different settings to overcome the over-fitting.

# Possible Improvements for Current Model
1)Even if we have almost 80% accuracy in current model, there is still a chance to improve it by Working with more observations by increasing the dataset size.
2)Investigating the different parameter settings to have more accuracy.
3)Analyzing location information effect on the churned user since location can provide us a information about life style and give company owner a chance to provide location based promotions to keep the users.
4)Used environment can also provide a usefull information. If android users are more likely to churned, this means the application needs an improvement for that environment.

I post a blog about the detail, you can find it here https://medium.com/@adhadwal3/the-churn-using-pyspark-57047f431ba7.

# Licensing, Authors, Acknowledgements
Must give credit to Udacity for the project. You can't use this for you Udacity capstone project. Otherwise, feel free to use the code here as you would like!
