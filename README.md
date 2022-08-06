# Neural_Network_Charity_Analysis
Module 19
Selection of Reputable Charities for Alphabet Soup

INTRODUCTION
Purpose of Exercise
The purpose of this exercise is to use various criteria to suggest the most reputable charities for Alphabet Soup to engage while avoiding charities that are risky.

RESULTS
-The variable considered to be the target for this model is IS_SUCCESSFUL.
-The variables that are considered to be features for this model are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT. 
-The variables that are not targets or features and should be removed from the input data are EIN, NAME, USE_CASE, or ORGANIZATION.

-There are 2 layers, the first layer had 80 neurons, the second layer had 25 neurons, and 3 activation functions for the nueral network model because this combination was what generated the most acurrate score.
-I was able to achieve the target model performance because I surpassed the accuracy target of 0.75. This model produces an accuracy of 0.9992.
-The step I took to try and increase model performance was to add layers. I noticed the first layer was the best option.

SUMMARY

Overall, I recommend on using model as its accuracy is high at 0.9992.  It eliminates non-impactful data such as EIN, NAME, USE_CASE, and ORGANIZATION from the features leaving only the most critical features to determine the target IS_SUCCESSFUL indicating where charities are not risky and will utilize the money effectively.