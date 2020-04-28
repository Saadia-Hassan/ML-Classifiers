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



