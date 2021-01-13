---
layout: default
title: chapters
---

### 1 : A Taxonomy of Problems

Data science is about using the machinery of statistics and computer science to solve real-world problems. In the clinical domain, that means incorporating methods from epidemiology, biostatistics, computer science, and machine learning with insights gained from the clinical research literature and the practical experiences of physicians, nurses, hospital administrators, operational teams, and biomedical researchers.

#### NOTES                
#### AUDIO 
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch1.pdf)


----------
### 2 : The Basics of Classification

Classification is a form of supervised learning in which our goal is to learn a mapping between some features, x, and an output, y. In classification, the output, y, is a category. In binary classification (by far the most common), there are only two categories: yes or no, usually represented as “0” (no) or “1” (yes). In multi-class classification, there are more than two categories. To learn an appropriate mapping, we feed training data to a learning algorithm. Different algorithms learn different types of mappings.

#### NOTES                
#### AUDIO     
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch2.pdf)

----------------

### 3 : The Basics of Regression

Classification is a form of supervised learning in which the outcome is a category. Regression is another form of supervised learning in which the outcome is a numeric value. For example, it may be a lab value, physical characteristic (height, weight, etc.), or numeric measurement (e.g. oxygen saturation).

#### NOTES                
#### AUDIO   
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch3.pdf)

----------------

### 4 : Probability Distributions

Many of the methods we will examine in these workshops depend on basic concepts from probability theory. For example, linear and logistic regression are members of a class of supervised learning algorithms called generalized linear models (see Chapter ??) which make assumptions about the type of probability distribution followed by the outcome variable. Decision trees use a concept called entropy (see Chapter 7), whose mathematical formulation depends on the probability distribution underlying the outcome. Many hypothesis tests (see Chapter 6) likewise rely on probabilistic assumptions about the data. Probability is everywhere. The following sections review some key probability concepts – in an extremely hand-wavey and non-rigorous way – and the properties of some of the most common probability distributions you will encounter in machine learning and statistics.

#### NOTES                
#### AUDIO   
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch4.pdf)

----------------

### 5 : The Basics of Maximum Likelihood Estimation

Beneath our discussions of classification, regression, and probability distributions in Chapters 2, 3, and 4 lies the tricky problem of model fitting. We’ve seen what classification and regression models look like, but we still haven’t addressed how to fit these models using training data. Linear and logistic regression models are fit using a technique called maximum likelihood (ML) estimation, in which the model parameters are adjusted to maximize the joint probability of the observed data, or likelihood, given the model.

#### NOTES                
#### AUDIO  
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch5.pdf)

----------------

### 6 : Introduction to Hypothesis Testing

Hypothesis testing is a central idea underpinning much of the analysis in the clinical and biomedical research literature. There are multiple approaches to hypothesis testing, but the most common is null hypothesis testing, which was developed by the statistician R.A. Fisher. In null hypothesis testing, one creates a model of how the data should look under default conditions and then quantifies the observed data’s deviation from that model using a test statistic. If the test statistic is large enough, it means there is evidence that the default position is incorrect. The statisticians Jerzy Neyman and Karl Pearson developed a different approach to hypothesis testing based on the idea of model comparison. In their approach, one sets up different models and then quantifies each model’s fit to the data; the hypothesis test is used to see whether one model’s fit to the data is significantly better than another’s. We see the Neyman-Pearson philosophy reflected in techniques such as power calculations and likelihood ratio tests.

#### NOTES                
#### AUDIO  
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch6.pdf)











### 6 : Generalized Linear Models*

Generalized linear models (GLMs) are a class of supervised learning models that form a convenient bridge between machine learning and traditional statistics. The basic idea behind a GLM is that your outcome variable (a.k.a. response variable, see Chapter 2), y, follows a probability distribution. The expected value, or mean, of that distribution is related to the values of the predictors (a.k.a. covariates; see Chapters 2 and 3), x1, . . . , xp in a model- specific way.

#### NOTES                
#### AUDIO  
#### CHAPTER GUIDE

----------------

### 7 : Fitting and Interpreting GLMs

Generalized linear models (Chapter 6) are just one way to approach super- vised learning. However, they are by far the most common approach in the clinical research literature. Linear and logistic regression are established, stan- dard methods for clinical data analysis in contexts where you want to relate the effects of one or more predictors to an outcome that is a number or a class (e.g. yes/no). Because of this, it is important to know how to interpret these models – e.g., what the coefficients, standard errors, and model diagnostics mean – and how to fit them using software.

#### NOTES                
#### AUDIO  
#### CHAPTER GUIDE

----------------

### 8 : Hypothesis Testing

Hypothesis testing is the central idea underpinning most of the analysis you’ll find in the clinical and biomedical research literature . There are multiple types of hypothesis testing, but the most common type is null hypothesis testing, most of the theory of which originated from the statistician R.A. Fisher. In null hypothesis testing, you create a model of how your data should look under default conditions, and then you look to see whether your data deviate appreciably from the model. You quantify your data’s deviation from the model by calculating a test statistic. One can view this type of hypothesis testing as a form of anomaly detection.

#### NOTES                
#### AUDIO  
#### CHAPTER GUIDE

----------------

### 9 : Decision Trees

Decision trees were developed as an alternative to neural networks in the 1970s. They can be used either for classification or regression. There are several algorithms for fitting decision trees, all of which are heuristic, because the general problem of learning an optimal decision tree for a dataset is NP- complete. All algorithms for tree learning are greedy and are not guaranteed to give the optimal solution.

#### NOTES                
#### AUDIO  
#### CHAPTER GUIDE

----------------

### 10 : The Bias-Variance Tradeoff

In classification, model complexity (i.e. the effective number of parameters the model must fit) is typically related to the intricacy and complexity of the decision boundary; the more parameters in the model, the more complex the boundary.

#### NOTES                
#### AUDIO  

----------------

### 11 : Feature Engineering and Feature Selection

The methods we’ve studied in Chapters 2 and 3, as well as all other supervised (and unsupervised) machine learning algorithms, all depend on the concept of a feature. A feature is some aspect of each training example that the model designer believes will influence its relationship to the outcome, or that captures some aspect of the data in a way that is relevant to the problem he/she is trying to solve. Before any algorithm can be applied, therefore, it is necessary to decide how to represent the data: which features to include and how to extract them from the raw data. This task is called feature engineering. In most cases, the model designer will also want to incorporate some form of feature selection: a process that automatically or semi-automatically decides which features are most relevant to the model and discards the others.

#### NOTES                
#### AUDIO  

----------------

### 12 : Lasso, Ridge, and Elastic Net


#### NOTES                
#### AUDIO  

----------------

### 13 : Random Forests


#### NOTES                
#### AUDIO  

----------------

### 14 : Boosting


#### NOTES                
#### AUDIO  

----------------

### 15 : Missing Data


#### NOTES                
#### AUDIO  

