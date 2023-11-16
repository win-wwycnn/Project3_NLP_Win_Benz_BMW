# Project3_NLP_Win_Benz_BMW

# Problem Statement

“A car trading agency company in England having two main premium-class cars which are Mercedes-Benz and BMW. In a day, the customer service team have inbox emails over a thousand from senders throughout the U.K. During the expansion of branches in this year, the number of the inbox email is increasing, so the head of customer service asks Data Science team to create model in order to distinguish the email by vehicle brands and send to the incharing section directly. As company-email gathering seems confidential, so the data science team started to do web-scraping from Reddit to initiate model creation instead at first.”


# Data dictionary

|Feature|Type|Description|Dataset|
|---|---|---|---|
title|string|Title name of posts|'BMW' and 'Benz'|
text|string|Text content of posts|'BMW' and 'Benz'|
class|int|Class label which classified by sub-reddit|'BMW' and 'Benz'|
post|string|Concatination of Title and Text |'BMW' and 'Benz'|
post_length|int|The number of words in a post ( Title + Text )|'BMW' and 'Benz'|


# Summary and Recomendation

The Data Science team recommended Model 2 : Random Forest with GridSearchCV to customer service team which has an accuracy 88% on unseen data set. If the head of customer service accept with this model, the customer service team need to verify for the other 12% of the incoming emails.
