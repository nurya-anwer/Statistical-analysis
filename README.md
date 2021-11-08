# Statistical-analysis

1) Give a brief definition of p-values and type 1, and type 2 errors
In statistical hypothesis testing: 
The P value is the probability of finding the observed, or more extreme, 
results when the null hypothesis (H0) of a study question is true – the definition of ‘extreme’ depends on how the hypothesis is being tested. 
type I error is the mistaken rejection of the null hypothesis.
type II error is the mistaken acceptance of the null hypothesis.

2) Explain the bias/variance tradeoff
In statistics, the bias–variance tradeoff is the property of a model that 
the variance of the parameter estimated across samples can be reduced by increasing the bias in the estimated parameters. 

3) Explain the complexity/interpretibility tradeoff¶

Model complexity is concerned about how complicated a problem that 
a deep model can express and how nonlinear and complex the function of a model with given parameters can be. 
In machine learning, data mining and deep learning, model complexity is always an important fundamental problem.
A complex model exhibiting high variance may improve in performance if trained on more data samples. 
Learning curves, which show how model performance changes with the number of training samples, are a useful tool for studying the trade-off between bias and variance. 
Machine learning model fairness and interpretability are critical for data scientists, researchers and developers to explain their models and understand the value and accuracy of their findings. 
Interpretability is also important to debug machine learning models and make informed decisions about how to improve them.

4) Define and explain the differences in predicting continuous and categorical labeled data

Categorical variables contain a finite number of categories or distinct groups. 
Categorical data might not have a logical order. For example, categorical predictors include gender, material type, and payment method.

Continuous variables are numeric variables that have an infinite number of values between any two values. 
A continuous variable can be numeric or date/time. 
For example, the length of a part or the date and time a payment is received. 
Treating a predictor as a continuous variable implies that a simple linear or polynomial function can adequately describe the relationship between the response and the predictor.
When you treat a predictor as a categorical variable, a distinct response value is fit to each level of the variable without regard to the order of the predictor levels.
Use this information, in addition to the purpose of your analysis to decide what is best for your situation.

5) Give a definition and explain the purpose of splitting data into a test and training set, and the purpose of cross-validation
The goal is to produce a trained (fitted) model that generalizes well to new, unknown data. 
The fitted model is evaluated using “new” examples from the held-out datasets (validation and test datasets) to estimate the model's accuracy in classifying new data. 
Cross-Validation is a statistical method of evaluating and comparing learning algorithms by dividing data into two segments:
one used to learn or train a model and the other used to validate the model.

6) Explain the "curse of dimensionality": How does this affect a classification task such as random forests or support vector machines?

Curse of Dimensionality refers to a set of problems that arise when working with high-dimensional data. 
The dimension of a dataset corresponds to the number of attributes/features that exist in a dataset. 
A dataset with a large number of attributes, generally of the order of a hundred or more, is referred to as high dimensional data. 
Some of the difficulties that come with high dimensional data manifest during analyzing or visualizing the data to identify patterns, and some manifest while training machine learning models. 

The curse of dimensionality makes the problem of searching through a space much more difficult, and effects the majority of algorithms that "learn" through partitioning their vector space. 
The higher the dimensionality of our optimization problem the more data we need to fill the space that we are optimizing over.
Random Forests use a collection of decision trees to make their predictions. 
But instead of using all the features of your problem, individual trees only use a subset of the features. 
This minimizes the space that each tree is optimizing over and can help combat the problem of the curse of dimensionality.
