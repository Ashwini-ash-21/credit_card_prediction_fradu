# credit_card_prediction_fradu
**source file: creditcard.csv**
**Problem Statement**
A credit card is one of the most used financial products to make online purchases and payments. Though the Credit cards can be a convenient way to manage your finances, they can also be risky. Credit card fraud is the unauthorized use of someone else's credit card or credit card information to make purchases or withdraw cash. It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase. The dataset contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions. We have to build a classification model to predict whether a transaction is fraudulent or not.
**null hypothesis: the transaction is not fraud, alternative hypothesis :  the transaction is fraud**
unable to explain columns from V1 to V28.other two columns are time and amound.
target column is named as class.number of catergories in this column is 2(0 & 1).
**project mainly focuesd on**
1. checked weather data is balanced
2. checked weather there are any null values available in the dataset.
3. checked the Class variable.
4. auto correlation between variables using heat map.
5. converted x data as a array.
6. Model training.
7. Model accuracy during train & test appears.
model is having high precision for 0 & 1 ,its indicates the model is well robust enough to classify correctly that the transaction is fradulent or not.once doubtfull transaction occured.

