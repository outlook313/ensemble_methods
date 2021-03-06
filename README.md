# ensemble_methods
Bagging and Boosting -Random Forest and AdaBoost
![ensemble](https://user-images.githubusercontent.com/89722385/143453031-5c9b01ab-13dc-4c6e-942e-2859bb1d01d3.jpeg)
<br>
<b>Bagging:</b><br>
Decision trees are trained for one specific task or dataset and cannot be transferred to
another similar problem. Nevertheless, several decision trees can be combined in order
to create bigger models and learn how to generalize. These are called random forests.
The name forest refers to an ensemble of many decision tree algorithms, following the
<b>bagging</b> method, which states that the combination of several algorithms achieves the
best result overall. The appearance of the word "random" refers to the randomness of
the algorithm when selecting the features to take into account to split a node.
<br>
<b>Boosting:</b><br>
AdaBoost puts together weak learners in order to form a strong learner. The name
AdaBoost stands for adaptive boosting, which means that this strategy would weigh
differently at each point in time. Those examples that are incorrectly classified in a
single iteration, get a higher weight than the next iteration, and vice versa.
