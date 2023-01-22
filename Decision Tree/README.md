## Decision Tree

Decision tree is the very tranditional method but this is powerful. Decision trees are made in the form of trees with predictive classification models that represent patterns embedded in data as a combination of variables.(This is similart to 'Akinator' game) Separate the datas that consist of the two or more subset(split data so that it becomes uniform)
The top part is called root node and the bottom part is called terminal node.

When we want to predict the numerical data, it is called _Regression decision tree_, categorical data, it is called _Classification decision tree_.

Now i'm interested in the classification tree, so deal with the only classification tree.

![tree](https://user-images.githubusercontent.com/90513931/213912327-5bacba13-d918-43b3-9c34-615d38d1b813.png)

Loss function involve the _misclassification rate_, _cross entropy loss_, _gini index_.
It is important to decide the decision variable(j) and decision point(s). To decision this, define the 'inpurity', 'purity'. This is calculated by 'Information-Gain' that show the which variable has low entropy. If entropy is reduced, this is important variable.

Deicison Tree has the disadvantages. First this is sensitive to noisy data. Second model is easy to overfitting. This means that model have low bias, large variance. 

To address this, use the _Random Forest_ that using the many trees.

