# FISP3
Repository Summary:

In the telecommunications business churn rate refers to "the percentage of service subscribers who discontinue their subscriptions within a given time period."<sup>1</sup> 

This project sought to determine primary contributors to churn based on the given dataset found on Kaggle at https://www.kaggle.com/becksddf/churn-in-telecoms-dataset.

After cleaning the dataset and building a model using the XGBoost classification algorithm the primary contributors to telecommunications churn appeared to be the amount of time spent on the phone and the number of phone calls made to customer service. As time spent on the phone became higher the probability of churn went up. Also when the number of customer service calls passed four the probability for churn became high.

There is a positive linear relationship between time spent on the phone and charge; therefore an exploration into nonlinear payment plans (such as higher upfront costs and cost caps at a higher end) might prove to reduce churn. Alternatively discounts for heavy time-users or long term customers might also be effective strategies. 

The model points to customer service calls of four or more indicating a high probability of churn. Although there is note enough information in this dataset to say why this is true, it is a useful starting point; from here the company can investigate the customer service protocols and interactions by collecting data for future analysis into root causes. 


Repository Contents:

The entire model from preprocessing to final analysis is included in the file "ChurnModel.ipynb"

The Non-technical presentation can be found in the file "TeleChurnPresentation.pptx" and is in powerpoint format

Tree.png contains the XGBoost tree from the ChurnModel.ipynb file, and the TreeTable.xlsx file contains a table with the probability data from the tree ending leaves

A project writeup can be found at "https://steve699777341.wordpress.com/2020/09/22/module-3-final-project-supervised-churn-model/"

Questions and comments on the model can be sent to stevenchamp11@yahoo.com.

1. Frankenfield, Jake. (25-05-2020). Churn Rate. Retrieved from https://www.investopedia.com/terms/c/churnrate.asp
