# AllThingsML
Self Guide to Machine Learning

## Machine Learning
A lot of definitions can be found online, the one I like best is computers learning to improve with experience(data).

## Types of Machine Learning
1. Supervised Learning: A dependent variable is predicted based on a set of independent variables by generating a function to map inputs to outputs. Examples: Random Forest, kNN, Logistic Regression
2. Unsupervised Learning: Forms groups (also known as clusters) of data, no target or outcome variables. Examples: k-means algorithm
3. Semi-supervised Learning: Training data includes some desired outputs (labeled data) and a larger amount of unlabeled data.
4. Reinforcement Learning: The algorithm trains to make some specific decisions, using trial and error.


## Regression Predictive Modeling
Regression consists of algorithms predicting a continuous outcome variable (also known as dependent variable) based on one or multiple predictor variables (also known as independent variables).
Any time we need to predict a *continuous numerical value*, we use regression algorithms. Examples: Linear Regression, Neural Networks, Random Forests

### Linear Regression
Linear Regression is a *linear* relationship between a dependent and an independent variable, represented by the linear equation:
```sh
y = ax + b
```
where x is the independent variable and y the dependent variable



## Classification Predictive Modeling 
Classification consists of algorithms predicting a discrete output variable(s) (labels/categories) so the mapping function predicts the labels for any given test observation. Examples: kNN, K-means clustering, Logistic Regression, Random Forests

### Logistic Regression
Classification problems that have two possible outcomes, uses the logistic function to output a value between 0 and 1.

![equation](http://www.sciweavers.org/tex2img.php?eq=logisitic%28x%29%20%3D%20%5Cfrac%7B1%7D%7B1%2B%20exp%5E%7B-x%7D%20%7D%20&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)


## Random Forests 
A supervised learning algorithm, random forests can be used for classification or regression problems. Essentially, a random forest is an ensemble of decision trees.
A random forest adds additional randomness to the model, by searching for the best feature among a random subset of features while splitting a node; giving a wider diversity to the model.
Also, a random forest is able to evaluate feature importance on the prediction, by looking at how each tree node used by that feature reduces impurity across all the decision trees in the forest.  

## Some Terms Used in ML World
### Hyperparameter Tuning: Used to define the model architecture,
