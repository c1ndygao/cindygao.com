---
layout: default
title: chapters
---

Welcome to "Modern Clinical Data Science", a pilot course and discussion group for data-science-interested physicians and colleagues in the Dept. of Medicine at Mount Sinai. These notes are designed to introduce key data science concepts little by little, in small pieces. Each chapter contains notes and a slide presentation of key concepts (chapter guide). All presentations take less than 15 minutes.

### 1 : A Taxonomy of Problems

What is data science? We go through 14 examples of project ideas from real students, including physicians and operational/population health team members, and see how they reflect different types of questions. Key terms: supervised vs. unsupervised learning, classification vs. regression, time-to-event outcome, observational study vs. experiment.

#### [NOTES](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch1.pdf)            
#### AUDIO 
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch1-guide.pdf)


----------
### 2 : The Basics of Classification

We investigate three different ways of solving classification problems: logistic regression, K-nearest neighbors (KNN), and decision trees. Using a simple ER readmissions example, we visualize the decision boundaries produced by each of these algorithms and discuss their advantages and disadvantages. Key terms: training and test data, feature, feature space, extrapolation, decision boundary, hyperparameter.

#### [NOTES](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch2.pdf)                
#### AUDIO     
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch2-guide.pdf)

----------------

### 3 : The Basics of Regression

We see how regression differs from classification and look at three regression algorithms that parallel the classification algorithms from Chapter 2. We visualize the regression problem using the same features as in Chapter 2 but a different outcome: the level of a "disease recurrence" biomarker. We see how the same machinery of linear models, KNN, and decision trees can be applied in a regression context.

#### [NOTES](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch3.pdf)                
#### AUDIO   
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch3-guide.pdf)

----------------

### 4 : Probability Distributions

We examine core concepts from probability through examples from several important probability distributions: the Gaussian (normal) distribution, Bernoulli distribution, binomial, Poisson, geometric, and exponential. We briefly discuss the chi-squared, T, and F distributions, which will be revisited later in Chapter 6 (Introduction to Hypothesis Testing). These ideas are important for understanding linear and logistic regression models, other probabilistic models, and most hypothesis tests.

#### [NOTES](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch4.pdf)                
#### AUDIO   
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch4-guide.pdf)

----------------

### 5 : The Basics of Maximum Likelihood Estimation

Although it's usually thought of as an advanced topic, maximum likelihood estimation is key to understanding how many types of models are fit using software. Here we discuss the core ideas behind maximum likelihood estimation through simple examples, using the same distributions we saw in Chapter 4. Key terms: likelihood, log-likelihood, optimization.

#### [NOTES](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch5.pdf)                
#### AUDIO  
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch5-guide.pdf)

----------------

### 6 : Introduction to Hypothesis Testing

We examine the most common type of hypothesis testing, null hypothesis testing, through three examples: the Z test, Pearson's chi-squared test, and [several forms of] the T-test. By seeing how different questions can be answered using the same formalism, we think through the meaning of terms like null hypothesis, null distribution, test statistic, and significance level. We address p-values only briefly and do not touch on confidence intervals; those will be covered in later chapters.

#### [NOTES](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch6.pdf)              
#### AUDIO  
#### [CHAPTER GUIDE](https://github.com/blpercha/mcds-notes/blob/main/pdf/ch6-guide.pdf)




----------
# below is old draft need to be replaced





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

