# KNN Classification in sklearn
1. Read the iris dataset from the following URL:
https://raw.githubusercontent.com/adityanemade/data-science/master/datasets/iris.csv
and assign it to a Pandas DataFrame
2. Split the dataset into testing and training sets with the following parameters:
**test_size=0.4, random_state=6**
3. Instantiate a KNN object with K=3, train it on the training set and test it on the testing set.
Then, calculate the accuracy of your prediction
4. Repeat part (3) for K=1, K=5, K=7, K=11, K=15, K=27, K=59 (you can simply use a “for loop,”
and save the final accuracy results in a list). Does the accuracy always get better by
increasing the value K?
5. Now, suppose that we would like to make prediction based on only **ONE single feature**.
To find the best single feature, we have to try every feature individually. In other word,
we have to repeat part (3) with K=3, four times (each time using only one of the 4
features), and compute the accuracy each time. Then, check the accuracies.
Which individual feature provide the best accuracy (the best feature)? Which one is the
second best feature? (**Note**: you have to train, test, and evaluate your model 4 times,
each time on a dataset including only one of the features, and save the final accuracy
results in a list).
6. Now, we want to repeat part (5), this time using **two features**, you have to train, test, and evaluate your model for 6 different cases:
    - (1st and 2nd features)
    - (1st and 3rd features)
    - (1st and 4th features)
    - (2nd and 3rd features)
    - (2nd and 4th features)
    - (3rd and 4th features)
  Which **“feature pair”** provides the best accuracy?
7. **Big Question**: Does the “best feature pair” from part (6) contain of both “first best feature”
and “second best feature” from part (5)? In other word, can we conclude that the “best
two features” for classification are the first best feature along with the second best feature
together?
8. Optional Question: Justify your answer for part (7)! If yes, why? If no, why not?
