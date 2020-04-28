# ML Classifiers
The pre-processing steps are worth looking at, for the beginners. In the world full of data, Machine Learning has become a to-go field for the ones looking to start off their career. This project shows basic operations performed on the dataset which is widely known as pre-processing. Once the data is ready, 4 main classifier algorithms are applied to find out the **Jaccard similarity, F1-score and Accuracy** which are the few important parameters one should look at while analysing a model. 

## K-Nearest Neighbours:
KNN can be used for both classification and regression predictive problems. However, it is more widely used in classification problems in the industry. To evaluate any technique we generally look at 3 important aspects:
1. Ease to interpret output
2. Calculation time
3. Predictive Power

![image](https://user-images.githubusercontent.com/53932260/80448319-83775b00-8939-11ea-81f2-16118431bdde.png)

### Pros and Cons associated with KNN

#### Pros:

    1. No assumptions about data — useful, for example, for nonlinear data
    2. Simple algorithm — to explain and understand/interpret
    3. High accuracy (relatively) — it is pretty high but not competitive in comparison to better supervised learning models
    Versatile — useful for classification or regression

#### Cons:

    1. Computationally expensive — because the algorithm stores all of the training data
    2. High memory requirement
    3. Stores all (or almost all) of the training data
    4. Prediction stage might be slow (with big N)
    5. Sensitive to irrelevant features and the scale of the data
        
## Support Vector Machine:
SVM is a supervised machine learning algorithm which can be used for classification or regression problems. It uses a technique called the kernel trick to transform your data and then based on these transformations it finds an optimal boundary between the possible outputs.

![image](https://user-images.githubusercontent.com/53932260/80448622-845cbc80-893a-11ea-9849-21ebe7a485c6.png)

### Pros and Cons associated with SVM

   #### Pros:
        1. It works really well with a clear margin of separation
        2. It is effective in high dimensional spaces.
        3. It is effective in cases where the number of dimensions is greater than the number of samples.
        4. It uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.
   #### Cons:
        1. It doesn’t perform well when we have large data set because the required training time is higher
        2. It also doesn’t perform very well, when the data set has more noise i.e. target classes are overlapping
        3. SVM doesn’t directly provide probability estimates, these are calculated using an expensive five-fold cross-validation. It is included in the related SVC method of Python scikit-learn library.

## Logistic Regression:
Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression (or logit regression) is estimating the parameters of a logistic model (a form of binary regression).

![image](https://user-images.githubusercontent.com/53932260/80448988-9428d080-893b-11ea-90b9-3d8ef9d657e4.png)

### Pros and Cons associated with LR

#### Pros:

    1. Logistic Regression performs well when the dataset is linearly separable.
    2. Logistic regression is less prone to over-fitting but it can overfit in high dimensional datasets. You should consider Regularization (L1 and L2) techniques to avoid over-fitting in these scenarios.
    3. Logistic Regression not only gives a measure of how relevant a predictor (coefficient size) is, but also its direction of association (positive or negative).
    4. Logistic regression is easier to implement, interpret and very efficient to train. 

#### Cons:

    1. Main limitation of Logistic Regression is the assumption of linearity between the dependent variable and the independent variables. In the real world, the data is rarely linearly separable. Most of the time data would be a jumbled mess.
    2. If the number of observations are lesser than the number of features, Logistic Regression should not be used, otherwise it may lead to overfit.
    3. Logistic Regression can only be used to predict discrete functions. Therefore, the dependent variable of Logistic Regression is restricted to the discrete number set. This restriction itself is problematic, as it is prohibitive to the prediction of continuous data.

## Decision Trees:
Decision Tree Classifier is a simple and widely used classification technique. It applies a straitforward idea to solve the classification problem. Decision Tree Classifier poses a series of carefully crafted questions about the attributes of the test record. Each time time it receive an answer, a follow-up question is asked until a conclusion about the calss label of the record is reached.

![image](https://user-images.githubusercontent.com/53932260/80449573-1cf43c00-893d-11ea-95fe-ed0cef017b9e.png)

### Pros and Cons associated with DT

#### Pros:

    1. Compared to other algorithms decision trees requires less effort for data preparation during pre-processing.
    2. A decision tree does not require normalization of data.
    3. A decision tree does not require scaling of data as well.
    4. Missing values in the data also does NOT affect the process of building decision tree to any considerable extent.
    5. A Decision trees model is very intuitive and easy to explain to technical teams as well as stakeholders.

#### Cons:

    1. A small change in the data can cause a large change in the structure of the decision tree causing instability.
    2. For a Decision tree sometimes calculation can go far more complex compared to other algorithms.
    3. Decision tree often involves higher time to train the model.
    4. Decision tree training is relatively expensive as complexity and time taken is more.
    5. Decision Tree algorithm is inadequate for applying regression and predicting continuous values.
    
# Thank you!





