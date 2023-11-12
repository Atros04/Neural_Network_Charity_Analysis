# Neural Network Charity Analysis
## Overview

We are looking to better predict if a company will be successful if they are sponsored by us at Alphabet Soup. We will take into account the type of application they filed, their affiliation, classification, and income among other variables. From there, we will create a model looking to predict if us funding them will make their venture suceed.

## Results
To process our data, we needed to consider the variables that we collected on the company that filed an application with us. These variables included: application type, thir targeted sector of business, government classification, use for hte funding, organization type, income bracket, and amount requested. We were using this data to better predict if the money was used successfully. We then ignored the variables like name and EIN.

To better fit the rule of thumb, we went with 100 neurons on the first layer and 35 on the second. For one of our other models, we added a third layer that used 13 neurons. These counts felt appropriate based on the many categorial variables that we had to sort through and turn into numbers. Through testing different activations and data binning, we were not able to achieve a model that was better than 75% accurate where most of our models fell in line with the 72-73% accuracy that the original model presented.

![Origin](https://github.com/Atros04/Neural_Network_Charity_Analysis/blob/main/Resources/Model%201.PNG)

Our attempts to get a better accurate model ended with the same results.
![Model 1](https://github.com/Atros04/Neural_Network_Charity_Analysis/blob/main/Resources/Opt_Model%201.PNG)
![Model 2](https://github.com/Atros04/Neural_Network_Charity_Analysis/blob/main/Resources/Opt_Model%202.PNG)
![Model 3](https://github.com/Atros04/Neural_Network_Charity_Analysis/blob/main/Resources/Opt_Model%203.PNG)

## Summary
The good thing with neural networks is we can make many variable changes in an effort to better generalize our model for the data. However, we would need to consider when we could use a different machine learning algorithm to better predict this information. In this, I would recommend us looking at SMV or Random Forest algorithims to see if we can better accurately predict the data with less loss. These models would look at our binary "yes" or "No" answers and potentiall give us a better prediction based on the input variables we have.
