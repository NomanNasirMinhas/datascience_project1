# Analyzing Pakistan’s Economic and Social Indicators
Data Science is giving us deep insights into different fields helping us to make better decisions in business, governance, economic and social domains. Moreover, making predictions using machine learning models help us to forecast and evaluate our future steps. In this article, we will use World Development Index Dataset to analyze Pakistan’s Social and Economic Indicators and will develop a model using sikit-learn to predict Pakistan’s GDP based on different indicators. Provided dataset contains data about 1429 Indicator’s from 1960 to 2019. We will try to answer following questions
1. How Military Expenditures of Pakistan have increased as compared to increased in GDP of Pakistan.
2. Does increase in population of Pakistan has any impact on its Inflation Rate.
3. Whether Pakistan has been able to control his government expenditures.
4. Develop a model to predict GDP of Pakistan.


- We will use CRISP-DM (Cross Industry Standard Process for Data Mining) which involves following steps.
1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment
- After finalizing our Questions, we have to transform and clean our data in a form so that we could answer our questions. 

### Libraries Used
We have used following Libraries in this project
- Numpy
- Pandas
- Matplotlib
- SKLearn

### Files In The Repository
Following is the description of files in repository
- pak_wdi.csv = CSV Data about Indicators of Pakistan from WDI
- Pakistan - World Development Index.ipynb = Notebook containing all pyhton code of project
- README.md = Readme file of the project

## Summary of Results
- Answer 1- We found that Military expenditures of Pakistan have increased very slightly when compared to increased in GDP as they show a very linear behavior.
- Answer 2- From the graph we can conclude that there is not significant relationship between Population and Inflation of Pakistan. This is because the graph is very uneven. If there was a relation between these two, then the graph should have shown relatively linear behavior
- Answer - 3: From the graph we can conclude Expenditures of Pakistan's Government have been greater than GDP of Pakistan for most of the time. Hence, we can conclude that Pakistan have always mismanaged its Budget.
- Model: When tested our model to predict GDPs of Pakistan over last years against real GDPs, we were able to get predictions shown in notebook execution.

- We have seen that data science helps us a lot to easily conclude results based on historical data and make predictions for future. Although this model may still be improved for better predictions, it still helps a lot to make better calculated predictions. 

## Credits/Acknowledgments
Data used in this project is provided by World Development Index.