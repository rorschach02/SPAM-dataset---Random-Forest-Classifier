# SPAM E-mail : Random Forest Classifier

## Dataset: 
### Description:
A data set collected at Hewlett-Packard Labs, that classifies 4601 e-mails as spam or non-spam. In addition to this class label there are 57 variables indicating the frequency of certain words and characters in the e-mail.

### Format:
A data frame with 4601 observations and 58 variables.

The first 48 variables contain the frequency of the variable name (e.g., business) in the e-mail. If the variable name starts with num (e.g., num650) the it indicates the frequency of the corresponding number (e.g., 650). The variables 49-54 indicate the frequency of the characters ‘;’, ‘(’, ‘[’, ‘!’, ‘\$’, and ‘\#’. The variables 55-57 contain the average, longest and total run-length of capital letters. Variable 58 indicates the type of the mail and is either "nonspam" or "spam", i.e. unsolicited commercial e-mail.

## Libraries:
-- ISLR <br/>
-- corrplot <br/>
-- MASS <br/>
-- klaR <br/>
-- leaps <br/>
-- lattice <br/>
-- ggplot2 <br/>
-- corrplot <br/>
-- car <br/>
-- caret <br/>
-- class <br/>
-- rpart <br/>
-- randomForest <br/>

## Fitting series of random forest against different values of m:

![diff_m_values](https://user-images.githubusercontent.com/46763031/148016326-98191097-cbb5-4c49-95d7-b7e2f94e5f72.png)

## Plotting OOB Error:

![OOB error rate plot](https://user-images.githubusercontent.com/46763031/148016349-89c96e02-f85c-4822-be5a-21e647137b16.png)

## Plotting Test Error:

![test error graph](https://user-images.githubusercontent.com/46763031/148016376-f5dfa48f-cb85-4cf5-afb0-3d9743541f8a.png)





