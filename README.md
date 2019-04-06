# Credit-Card-Fraud-Detection

![Apple-Card-physical-1280x720](https://user-images.githubusercontent.com/35174083/55663491-83fff980-57ec-11e9-8d30-eb529806c16d.jpg)

## Credit Card Fraud:
Recently Apple launched a credit card, in partnership with MasterCard and Goldman-Sachs, which has absolutely no numbers. But in reality the credit cards offered by various banks like Bank of America, Santander, American Express among others have various numbers for various reasons on them. These numbers make it vulnerable to fraudulent activities. This analysis is of most importance to every human who carries a credit card. This analysis is also important to organizations which provide credit cards. Additionally, this analysis caters to all those who work hard to earn money and pay the credit card bills.

## Data
### Fetching the data:
Tha dataset is available on kaggle as a part of a competition. The dataset can be downloaded here- https://www.kaggle.com/mlg-ulb/creditcardfraud

## Analysis Performed:

### Technique 1: Analysis using Machine Learning Techniques

### Objective
To predict the fradulent transactions using Machine Learning techniques.

### Approach
Using:
##### Supervised Machine Learning Techniques:
1. Logistic Regression
2. Classification Trees
3. Naive Bayes Classifier 
##### Unsupervised Machine Learning Techniques:
1. Local Outlier Factor (LOF)
2. Isolation Forest Algorithm
to correctly classify if a transaction is fraud or not.

### Steps
1. Read the dataset using Pandas.
2. Perform EDA on the dataframe and visualizations to extract information.
3. Deploy Machine Learning algorithms on the pre-processed dataset.
4. Plot the accuracy metrics for the classifier.

### Insight
#### Here are the images for model performance:

![image](https://user-images.githubusercontent.com/35174083/55663518-f1ac2580-57ec-11e9-8b45-4156862d341d.png)

![image](https://user-images.githubusercontent.com/35174083/55663527-17d1c580-57ed-11e9-97ef-a8351767ad53.png)

![image](https://user-images.githubusercontent.com/35174083/55663534-320ba380-57ed-11e9-808c-632f97aa6440.png)



### Conclusion
From the above plots we can determine the factors leading to fradulent transactions and we can also see the gradual increase in accuracy for the supervised learning models.

### Technique 2: Analysis using Deep Learning Techniques

#### Objective
To predict the fradulent transactions using Deep Learning techniques. Deep Learning techniques involve neural networks and it's different types. We will use these to obtain higher accuracies than Machine Learning approach.

#### Approach
Using:
##### Supervised Deep Learning Techniques:
1. Artificial Neural Network

##### Unsupervised Deep Learning Techniques:
1. Self Organizing Maps
to correctly classify if a transaction is fraud or not.

There is a hybrid Deep Learning model which is a combination of the Self Organizing maps and artificial neural network 

#### Steps
1. Read the dataset using Pandas.
2. Perform EDA on the dataframe and visualizations to extract information.
3. Deploy the Deep Learning algorithms on the pre-processed dataset.
4. Plot the accuracy metrics for the classifier.

#### Insight


#### Conclusion
From the above plots we can determine the factors leading to fradulent transactions and we can also see the gradual increase in accuracy for the supervised learning models.

