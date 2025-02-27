# knn-breast-cancer-wisconsin.data
In machine learning, k Nearest Neighbors (kNN) is one of the simplest algorithms. It is a non-parametric algorithm used for both classification and regression problems. “Non-parametric” means that the algorithm does not require any assumptions about the distribution of the data.

In both **classification** and **regression** tasks, the input consists of the k nearest data points in the feature space. The output will depend on whether kNN is used for classification or regression:

**With classification** , the result will be the class label that is the majority of the k nearest points.

**With regression** , the result is the average (or median) of the neighboring points.

- In kNN classification, the output is the **class label** of the data point. The data point is **classified** based on the class label that is the majority among its neighbors. Specifically, the data point will be assigned to the class that appears most frequently among the k nearest points.

Typically, k is a small positive integer. If k = 1, then the data point will be assigned directly to the class of the only nearest point.

- In kNN regression, the output is a **numeric value** representing the attribute of the object. This value is calculated by **averaging** the values ​​of the k nearest neighbors.

kNN is a form of **instance-based learning** or **lazy learning**. This means that there is no need for **pre-training** before making predictions. All training data will be used directly in the testing phase, making **training** faster but testing slower and more resource-consuming (time and memory).

In kNN, neighboring points are taken from a data set with known attribute **labels or values**, which can be considered as the training set. Although there is no explicit training step, in both classification and regression, the kNN algorithm can assign **weights** to neighboring points. Closer points will have a greater influence on the result than farther points.
