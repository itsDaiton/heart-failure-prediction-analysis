# Heart Failure Prediction Analysis
Binary classification task where the goal is to predict whether patient had a heart disease event or not based on 11 clinical features.

## Description
In this analysis, our goal was to predict heart disease events on patients using a dedicated dataset of 918 observations with 11 clinical features and 1 target binary variable. Firsty, we introduced and explained the dataset and tried to understand the domain we were working with. Then we performed an exploratory data analysis, where we visualized all features to get a better understanding of the attributes. We found all kinds of interesting facts about the data, which we then used later in the analysis. Next, we carried out preprocessing of our dataset using the pandas library. We had to recode several attributes and deal with outliers and missing/nonsensical data. We also scaled (normalized) the data, so it would be easier to use them in different models. After that, we trained two machine learning models, logistic regression and decision trees on our data. To ensure better results, we also used hyperparameter tunning methods. Lastly, we used these trained models and evaluated their performance on our test set using different evaluation metrics.

Our best model achieved a performance of **90%**, so it is safe to say that our analysis was successful, and we can confidently predict heart disease events for about 90% of the patients. Obviously for real world application, this number would need to be even higher, as there is a massive risk by wrongly diagnosing a human being, especially in something like heart diseases. We assume that training a deep neural network would net even better results for this particular task.

## Built With
* numpy
* pandas
* matplotlib
* seaborn
* scikit-learn

## Authors
* David Poslušný
* Jiří Dragoun
