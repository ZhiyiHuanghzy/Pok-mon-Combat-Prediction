# Pok-mon-Combat-Prediction
DS502_Final_Project. 



**1.Data Overview**

This Pokémon combat dataset is public and shared on Kaggle: https://www.kaggle.com/terminus7/Pokémon-challenge.

***1.1Distribution Overview***

![1.1.png](image/1.1.png)



***1.2 Characteristics***

![1.2.png](image/1.2.png)





**2.Feature Engineering**

***2.1Design Training Entries***

![2.1.png](image/2.1.png)


***2.2Design the Equation***

![2.2.png](image/2.2.png)





**3.Models**
***Logistic Regression***

![lr1.png](image/lr1.png)

![lr2.png](image/lr2.png)



***Naive Bayes***

![nb1.png](image/nb1.png)

![nb2.png](image/nb2.png)





***Support Vector Machine***

![svm1.png](image/svm1.png)

![svm2.png](image/svm2.png)





***Decision Tree***

![dt1.png](image/dt1.png)

![dt2.png](image/dt2.png)





***KNN***

![knn1.png](image/knn1.png)

![knn2.png](image/knn2.png)

![knn3.png](image/knn3.png)






***Random Forest***

![rf1.png](image/rf1.png)

![rf2.png](image/rf2.png)




**4.Summary**

***4.1Results Summary***

![sum1.png](image/sum1.png)

![sum2.png](image/sum2.png)



***4.2Results Analysis***

a. The dataset contains both discrete data and continuous data. Tree-typed algorithms are particularly good at processing such mixed formats. (Random Forest, AdaBoost, and Decision Tree are all tree-like algorithms)

b. The random forest based on Bagging and AdaBoost based on the Boosting method can well realize parallelization in the training process. They have the power to handle a large data set with higher dimensionality.

c. Random Forest is easier to implement than AdaBoost because AdaBoost needs to do more work on feature engineering to get good performance. AdaBoost may work better when the data is clean, while Random Forest is more applicable when the data complex.



