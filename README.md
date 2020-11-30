## AMEX_2020_Competition

Data downloaded from the Competition portal. Uploaded in the repository
# **PROBLEM STATEMENT**
XZVEE is a multinational financial services company and operates one of the largest credit card businesses in the United States. It uses multiple channels of acquiring new customers with a higher inclination towards digital channels.

* Face to Face
* Direct Mail
* Email
* Affiliate Marketing
* Content Marketing
* Paid Search
* Referral Marketing
* Referral marketing or Member Get Member as it is called, is one of the most growing yet efficient channel which capitalizes on the current loyal customer base. The existing card holders refer their friends and family and in turn get reward points if the referral gets approved for a credit card.

In order to increase customer referral penetration , XZVEE runs special offer on the channel- customers get bonus reward points for every successful referral they make. XZVEE is planning to launch a special offer campaign- Golden Ticket in December for which they are working on identifying the target set of customers who can be offered a higher incentive to participate in the program and refer their friends.

The customer base for XZVEE is large and hence identifying the right target segment for the campaign is imperative to its success.

You have been given the opportunity to work on this problem and help them identify the best customers that should be targeted for this campaign.

Apart from data about customer attributes and XZVEE spend, you will also have access to their digital activity levels, credit bureau variables and and their financial metrics.

**Problem Statement**
You have to provide a profitable flag against each Customer ID: a value of 0 or 1

**Assume:**

* Flag 0 means higher incentive should not be given
* Flag 1 means higher incentive should be given as it is profitable
* State any other assumptions in your final submission

**Data for Analysis**\
Following files can be downloaded for your analysis.

1. Training_dataset.csv: This dataset contains all the variables along with the profitable flag for the customers [ Find it here](../main/Training_Data.csv)
2. Evaluation_dataset.csv: This data has applicant level data along with all the variables in the training dataset. The actual profitable flag is not present in this data.[ Find it here](../main/Evaluation_Data.csv)
3. Data_Dictionary.csv: This sheet will give you the description of all the variables contained in the 2 datasets above.  [ Find it here](../main/Data_Dictionary.csv)

# **Three types of classification approaches were considered:**
1)  Gradient Boosting classifier with oversampling
2)  Random Forest classifier with oversampling
3)  ANN based binary classifier with oversampling

Find the approach in the .ipynb file [here](../main/Amex_2020_Analyze_This_competition.ipynb)\
Find a sample submission file [here](../main/Sample_Submission.csv)\
Final submission made to the competition can be found [here](../main/submission_xgb.csv)
