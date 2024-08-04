# credit-risk-classification

This code describe the used of logistic regression model to identify bad loans or highrisk loan vs good loans or Healthy loans. See below summary of the model and answer to so of the keys questions.

Question 1) An overview of the analysis: Explain the purpose of this analysis.

We have used a logistics regression model which is a classification model to identify good loans vs bad loans in a peer to peer lending platform.

Question 2) The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.

Accuracy which is important factor as it identified TP + FP / TP+FP + TN + FN 14924+ 476= 15400 or 15400/15508=99.30% ~ 99% This showcase the model is Accurate which signifies it accurately identified both good loans which were actually good and bad load which are actually bad.

Next is Precision which 0.86 or 86 % for bad loans or 1. This is not a good number as it means a lot of bad loans were classified as False negative or bad loans were not acuuratley identfied as bad loans. Precision for classification as o or good loans is almost 100% meaning almost all of the good loans were accurately identified.

Here Precision for bad loans is not good, which negatively impact the business of peer lending business. As the impact of not able to accurately identifying bad loads are high and could impact the bottom line directly, and lead to capital loss to the business of lending money.

F1-score and recall score are pretty which signifies the model overall is pretty accurate, and helpful

Question 3: A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

Overall the model is pretty good to be used in this case to accurately identify good loans. Although the bad loans could not be accuratly identified it could be affected by large sample size of good loans which is inheritent in such models, but other the model has scored well in most other parameters.