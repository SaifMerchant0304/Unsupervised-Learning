### Unsupervised Learning

**Unsupervised Learning Project - Automobile Dataset:**

_Data Understanding & Exploration:_

* Read 'Car name.csv' and 'Car-Attributes.json' as DataFrames.
*  Merge both DataFrames into a single DataFrame.
* Print the 5-point summary of numerical features and derive insights.


_Data Preparation & Analysis:_

* Check and print feature-wise percentage of missing values, impute with appropriate approach.
* Handle duplicate values in the data.
* Visualize pairplots for all features and scatterplots for 'wt' vs. 'disp' and 'wt' vs. 'mpg', distinguishing by 'cyl'.
* Identify and handle unexpected values in features.
* Share insights from scatterplots.


_Clustering:_

* Apply K-Means clustering for 2 to 10 clusters.
* Plot visual for elbow point determination.
* Highlight possible elbow points.
* Train K-Means clustering model again on optimal number of clusters.
* Add new feature in DataFrame based on cluster labels.
* Plot visual and color datapoints based on clusters.
* Predict cluster for a new DataPoint.


**_Automobile Classification Project:_**

_Data Understanding & Cleaning:_

* Read 'vehicle.csv' and save as DataFrame.
* Handle missing values and visualize class distribution using a pie-chart.
* Handle duplicate rows in the data.


_Data Preparation:_

* Split data into feature set (X) and target variable (Y).
* Standardize the Data.


_Model Building:_

* Train a base Classification model using SVM and print metrics for train data.
* Apply PCA on the data with 10 components and visualize cumulative variance explained.
* Select minimum components with 90% or above variance explained and train SVM model.
* Print classification metrics for the model and share insights.


_Performance Improvement:_

* Train another SVM on PCA components, tuning parameters for better performance.
* Share best parameters observed and print classification metrics for the model.
* Discuss relative improvement in performance across all models and provide insights.


_Understanding PCA:_

* Explain pre-requisites and assumptions of PCA.
* Discuss advantages and limitations of PCA.


In these projects, the focus lies on understanding, preparing, analyzing data, performing clustering and classification tasks, and employing PCA for dimensionality reduction. Through various steps, missing values, duplicates, and outliers are addressed, models are trained, and insights are derived, leading to improved understanding and performance in the respective domains.
