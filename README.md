**Online News Popularity Prediction**


This work will help online news companies to predict news popularity before publication ,the news popularity are often indicated by the amount 
of reads, likes or shares. For the web news stake holders, it’s very valuable if the recognition of the news articles are often accurately 
predicted before the publication. Thus, it's  interesting and meaningful to use the machine learning techniques to predict the recognition 
of online news articles.In our project, the dataset including 39,643 news articles from  website Mashable, we attempt to find the simplest 
classification learning algorithm to accurately predict if a news story will become popular or not before publication. 

*List of Predictive Attributes of Dataset:*


![image](https://user-images.githubusercontent.com/42567661/151770954-4c1f4ae2-07db-42aa-8b7b-5994d6311d43.png)


For each instance of the dataset, it has 61 attributes which includes 1 target attribute (number of 
shares), 2 non-predictive features (URL of the article and Days between the article publication and the dataset 
acquisition) and 58 predictive features.


**Graphs and Visualizations**

Popular/unpopular news over different days of a week


![image](https://user-images.githubusercontent.com/42567661/151769005-d7af1388-a208-4036-9807-2f15fa1dadbc.png)


Popular/unpopular news over different article category


![image](https://user-images.githubusercontent.com/42567661/151769178-f550f7f5-7441-45bb-b800-b0f6548e59e5.png)

Before algorithm implementation, for each algorithm, I also randomly split dataset with its own selected features into 
training set (90%) and testing set (10%). The logistic regression, RF and Adaboost are implemented by the 
sklearn function LogisticRegression(), RandomForestClassifier() and AdaBoostClassifier(), respectively.

Performance of three classifiers under default parameter settings:


![image](https://user-images.githubusercontent.com/42567661/151769493-922b5e66-d736-4314-b083-8284a0214d87.png)


**Final Model Result and Accuracy Scores**

Tested the model with training/testing set ratio 0.15

![image](https://user-images.githubusercontent.com/42567661/151769602-1d06b7bf-18fb-4ced-a4d5-4d6796f7d680.png)


I came to conclusion after comparing the results obtained from all the three classifiers used that Random forest 
algorithm proves to be the most accurate amongst all giving  us an accuracy rate of 67%.

**Dataset Link** : https://archive.ics.uci.edu/ml/datasets/Online+News+





