Classification is one of the most important task of Machine Learning. Main task of machine learning is data analysis. For study purpose various algorithm available for classification like decision tree, Navie Bayes, Back propagation, Neural Network, Artificial Neural, Multi-layer perception, Multi class classification, Support vector Machine, k-nearest neighbor etc. In this paper we introduce Three algorithms from them (Decision Tree, Support vector Machine, Apriori algorithm). Study purpose we take iris.arff dataset. Implement this all algorithm in iris dataset and compare between them. Weka is inbuilt tools for machine learning. So we used WEKA for implementation.
Decision tree: It is a predictive model which maps observations about an item to conclusions about the item's target value.(ID3,C4.5)
Support vector Machine: A promising new method for the classification of both linear and nonlinear data. In a nutshell, a support vector machine (SVM) is an algorithm that works as follows. It uses a nonlinear mapping to transform the original training data into a higher dimension. Within this new dimension, it searches for the linear optimal separating hyper plane.
Apriori algorithm: The Apriori Algorithm is an influential algorithm for mining frequent item-sets for boolean association rules. Apriori uses a "bottom up" approach, where frequent subsets are extended one item at a time.
We used “iris.arff” dataset the basic information of iris is given below.

Relevant Information: This is perhaps the best known database to be found in the pattern recognition literature - 
Predicted attribute: class of iris plant. This is an exceedingly simple domain. 
Number of Instances: 150 (50 in each of three classes) 
Number of Attributes: 4 numeric, predictive attributes and the class Attribute Information: 
1. Sepal length in cm    
 2. Sepal width in cm    
 3. Petal length in cm       
 4. Petal width in cm        
 5. Class: Iris Setosa , Iris Versicolour, Iris Virginica

Comparison between decession tree and SVM:
Error List	                  Decision tree	SVM
Kapa statistic	0.94	0.94
Mean absolute error	0.035	0.2311
Root mean squared error	0.1586	0.288
Relative absolute error	7.8705%	52%
Root relative squared error	33.6353%	61.101%
Total number of instance 	150	150
