# Neural Network Charity Analysis
## Overview

We ar elooking to better predict if a company will be successful if they are sponsored by us at Alphabet Soup. We will take into account the type of application they filed, their affiliation, classification, and income among other variables. From there, we will create a model looking to predict if us funding them will make their venture suceed.

## Results
To process our data, we needed to consider the variables that we collected on the company that filed an application with us. These variables included: application type, thir targeted sector of business, government classification, use for hte funding, organization type, income bracket, and amount requested. We were using this data to better predict if the money was used successfully. We then ignored the variables like name and EIN.

To better fit the rule of thumb, we went with 100 neurons on the first layer and 35 on the second. For one of our other models, we added a third layer that used 13 neurons. These counts felt appropriate based on the many categorial variables that we had to sort through and turn into numbers. Through testing different activations and data binning, we were not able to achieve a model that was better than 75% accurate where most of our models fell in line with the 72-73% accuracy that the original model presented.
