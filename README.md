**Starbucks Capstone Project**

**Overview**
The data explored in this dataset contains simulated data that mimics customer behaviour on the Starbucks rewards mobile app. Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks.
This project aims to explore and get an understanding of determine which demographic groups respond best to which offer type in order for the right offers to be campaigned to the right groups of people. This is to ensure that customers are receiving relevant offers that will keep the engaged.

**Blog post link**
https://medium.com/@thande.tm/more-stars-for-starbucks-d148af4e8b29

**Installation**

To run the code, you need the Anaconda distribution of Python. The code is compatible with Python 3.x versions and you should be able to run it. You would need to install the following libraries using pip install:

pip install -r requirements.txt
The requirements.txt file includes:

pandas
numpy
scikit-learn
matplotlib
seaborn

**Usage**

To use this project, follow these steps:

Clone the repository to your local machine.
Install the required libraries as mentioned in the Installation section.
Open the Jupyter Notebook Starbucks_Capstone_notebook.ipynb to explore the data analysis and visualizations.
Use the portfolio.json, profile.json and transcription.json files for analysis

**Project Motivation**

The intention of this project was to give recommendations and key insights on customer preferences and behaviours for better campaigning to improve offer take ups and engagements


**Key Findings**
Young Adults (ages 18–25) appear to prefer BOGO offers as they are looking more for deals that will give them more value for money. The idea of buying more for less is quite appealing for this group of individuals. They prefer to engage on their mobile phones and prefer social channels. This is something to consider when looking into reaching out and engaging with this group of individuals. This is based on the proportion of customers in the analysis.
The middle-aged adults (ages 26–45) are likely to respond quite positively to discounted offers, particularly in cases where there is high expenditure. What they look for typically isn't quantity but more on getting less on exactly what they want. They seem to prefer to engage with web and email channels. This is based on the proportion of customers in the analysis.
The older Adults (ages 46+) potentially could prefer to be more informed, and BOGO offers by virtue of emails to engage with them. This is based on the proportion of customers in the analysis.
Based on the machine learning model, strong predictors include the offer types themselves and the channel through which the offers are presented. This has a massive effect on the outcome of the effect.

**Improvements and Recommendations**
1. Feature Engineering: Added interaction features and temporal features to capture more information.

2. Data Preprocessing: Scaled and standardized numerical features to improve model performance

**File Descriptions**
Starbucks_Capstone_notebook.ipynb: The Jupyter Notebook has data analysis, visualisations in code form using Python (in pandas)
README.txt: The file has information pertaining to the synopsis of the project, files, how to navigate the components in the project and other relevant piece of useful information.
portfolio.json, profile.json and transcription.json: The files contain respondent data regarding their demographics, occupation, income and other related data. You are not able to infer anyone's personal identity from the file.

**Licensing, Authors, Acknowledgements**

Starbucks - Wikipedia

Udacity nanodegree data set

https://www.geeksforgeeks.org/read-json-file-using-python/
