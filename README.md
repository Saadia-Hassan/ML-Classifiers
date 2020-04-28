# ML Classifiers
The pre-processing steps are worth looking at, for the beginners. In the world full of data, Machine Learning has become a to-go field for the ones looking to start off their career. This project shows basic operations performed on the dataset which is widely known as pre-processing. Once the data is ready, 4 main classifier algorithms are applied to find out the **Jaccard similarity, F1-score and Accuracy** which are the few important parameters one should look at while analysing a model. 

## K-Nearest Neighbours:
KNN can be used for both classification and regression predictive problems. However, it is more widely used in classification problems in the industry. To evaluate any technique we generally look at 3 important aspects:
1. Ease to interpret output
2. Calculation time
3. Predictive Power

![image](https://user-images.githubusercontent.com/53932260/80448319-83775b00-8939-11ea-81f2-16118431bdde.png)

### We can implement a KNN model by following the below steps:

    1. Load the data
    2. Initialise the value of k
    3. For getting the predicted class, iterate from 1 to total number of training data points
    4. Calculate the distance between test data and each row of training data. Here we will use Euclidean distance as our distance metric since it’s the most popular method. The other metrics that can be used are Chebyshev, cosine, etc.
    5. Sort the calculated distances in ascending order based on distance values
    6. Get top k rows from the sorted array
    7. Get the most frequent class of these rows
    8. Return the predicted class
        
## Support Vector Machines:
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





