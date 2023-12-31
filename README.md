# Top 10 Machine Learning Algorithms(2023)

# SUPERVISED:

## 1. Linear regression
   
- Linear regression is a supervised learning algorithm used for predicting and forecasting values that fall within a continuous range, such as sales numbers or housing prices.
- It is a technique derived from statistics and is commonly used to establish a relationship between an
input variable (X) and an output variable (Y) that can be represented by a straight line.
- In simple terms, linear regression takes a set of data points with known input and output
values and finds the line that best fits those points. This line, known as the "regression line,"
serves as a predictive model. By using this line, we can estimate or predict the output value (Y) for a given input value (X).
- Linear regression is primarily used for predictive modeling rather than categorization.
- It is useful when we want to understand how changes in the input variable affect the output variable.
- By analyzing the slope and intercept of the regression line, we can gain insights into the relationship between the variables and make predictions based on this understanding.

## 2. Logistic Regression

- Logistic regression, also known as "logit regression," is a supervised learning algorithm primarily used for binary classification tasks. 
- It is commonly employed when we want to determine whether an input belongs to one class or another, such as deciding whether an image is a cat or not a cat. 

- Logistic regression predicts the probability that an input can be categorized into a single primary class. 
- However, in practice, it is commonly used to group outputs into two categories: the primary class and not the primary class. 
- To accomplish this, logistic regression creates a threshold or boundary for binary classification. 
- For example, any output value between 0 and 0.49 might be classified as one group, while values between 0.50 and 1.00 would be classified as the other group. 

- Consequently, logistic regression is typically used for binary categorization rather than predictive modeling. 
- It enables us to assign input data to one of two classes based on the probability estimate and a defined threshold. 
- This makes logistic regression a powerful tool for tasks such as image recognition, spam email detection, or medical diagnosis where we need to categorize data into distinct classes.

## 3. Naive Bayes

- Naive Bayes is a set of supervised learning algorithms used to create predictive models for binary or multi-classification tasks.
- It is based on Bayes' Theorem and operates on conditional probabilities, which estimate the likelihood of a
classification based on the combined factors while assuming independence between them.

- Let's consider a program that identifies plants using a Naive Bayes algorithm. 
The algorithm takes into account specific factors such as perceived size, color, and shape to categorize images of plants. 
Although each of these factors is considered independently, the algorithm combines them to assess the probability of an object being a particular plant.

- Naive Bayes leverages the assumption of independence among the factors, which simplifies the calculations and allows the algorithm to work efficiently with large datasets. 
- It is particularly well-suited for tasks like document classification, email spam filtering, sentiment analysis, 
and many other applications where the factors can be considered separately but still contribute to the overall classification.

## 4. Decision Tree

- A decision tree is a supervised learning algorithm used for classification and predictive modeling tasks.
- It resembles a flowchart, starting with a root node that asks a specific question about the data.
- Based on the answer, the data is directed down different branches to subsequent internal nodes, which ask further questions and guide the data to subsequent branches.
- This process continues until the data reaches an end node, also known as a leaf node, where no further branching occurs.

- Decision tree algorithms are popular in machine learning because they can handle complex datasets with ease and simplicity. 
- The algorithm's structure makes it straightforward to understand and interpret the decision-making process. 
- By asking a sequence of questions and following the corresponding branches, decision trees enable us to classify or predict outcomes based on the data's characteristics.

- This simplicity and interpretability make decision trees valuable for various applications in machine learning, especially when dealing with complex datasets.

## 5. Random Forest

- A random forest algorithm is an ensemble of decision trees used for classification and predictive modeling.
- Instead of relying on a single decision tree, a random forest combines the predictions from multiple decision trees to make more accurate predictions.

- In a random forest, numerous decision tree algorithms (sometimes hundreds or even thousands) are individually trained using different random samples from the training dataset. 
- This sampling method is called "bagging." Each decision tree is trained independently on its respective random sample.

- Once trained, the random forest takes the same data and feeds it into each decision tree. Each tree produces a prediction, and the random forest tallies the results.
- The most common prediction among all the decision trees is then selected as the final prediction for the dataset.

## 6. K-nearest neighbor (KNN)

- K-nearest neighbor (KNN) is a supervised learning algorithm commonly used for classification and predictive modeling tasks.
- The name "K-nearest neighbor" reflects the algorithm's approach of classifying an output based on its proximity to other data points on a graph. 

- Let's say we have a dataset with labeled points, some marked as blue and others as red. When we want to classify a new data point, KNN looks at its nearest neighbors in the graph.
- The "K" in KNN refers to the number of nearest neighbors considered. For example, if K is set to 5, the algorithm looks at the 5 closest points to the new data point.

- Based on the majority of the labels among the K nearest neighbors, the algorithm assigns a classification to the new data point. 
- For instance, if most of the nearest neighbors are blue points, the algorithm classifies the new point as belonging to the blue group.

- Additionally, KNN can also be used for prediction tasks. Instead of assigning a class label,
KNN can estimate the value of an unknown data point based on the average or median of its K nearest neighbors.

- Random forests address a common issue called "overfitting" that can occur with individual decision trees. 
- Overfitting happens when a decision tree becomes too closely aligned with its training data, making it less accurate when presented with new data.

## 7. Support Vector Machine (SVM)

- A support vector machine (SVM) is a supervised learning algorithm commonly used for classification and predictive modeling tasks.
- SVM algorithms are popular because they are reliable and can work well even with a small amount of data.
- SVM algorithms work by creating a decision boundary called a "hyperplane." In two-dimensional space, this hyperplane is like a line that separates two sets of labeled data. 

- The goal of SVM is to find the best possible decision boundary by maximizing the margin between the two sets of labeled data. 
- It looks for the widest gap or space between the classes. Any new data point that falls on either side of this decision boundary is classified based on the labels in the training dataset.

- It's important to note that hyperplanes can take on different shapes when plotted in three-dimensional space, allowing SVM to handle more complex patterns and relationships in the data.

# UNSUPERVISED:

## 8. K-means

- K-means is an unsupervised learning algorithm commonly used for clustering and pattern recognition tasks.
- It aims to group data points based on their proximity to one another. Similar to K-nearest neighbor (KNN),
- K-means utilizes the concept of proximity to identify patterns or clusters in the data.

- Each of the clusters is defined by a centroid, a real or imaginary center point for the cluster. 
- K-means is useful on large data sets, especially for clustering, though it can falter when handling outliers.

- K-means is particularly useful for large datasets and can provide insights into the inherent structure of the data by grouping similar points together. 
- It has applications in various fields such as customer segmentation, image compression, and anomaly detection.



## 9. Apriori

- Apriori is an unsupervised learning algorithm used for predictive modeling, particularly in the field of association rule mining. 

- The Apriori algorithm was initially proposed in the early 1990s as a way to discover association rules between item sets. 
- It is commonly used in pattern recognition and prediction tasks, such as understanding a consumer's likelihood of purchasing one product after buying another.

- The Apriori algorithm works by examining transactional data stored in a relational database.
- It identifies frequent itemsets, which are combinations of items that often occur together in transactions.
- These itemsets are then used to generate association rules. For example, if customers frequently buy product A and product B together,
  an association rule can be generated to suggest that purchasing A increases the likelihood of buying B.

- By applying the Apriori algorithm, analysts can uncover valuable insights from transactional data,
  enabling them to make predictions or recommendations based on observed patterns of itemset associations.

## Gradient Boosting

- Gradient boosting algorithms employ an ensemble method, which means they create a series of "weak" models that are iteratively improved upon to form a strong predictive model.
- The iterative process gradually reduces the errors made by the models, leading to the generation of an optimal and accurate final model.

- The algorithm starts with a simple, naive model that may make basic assumptions, such as classifying data based on whether it is above or below the mean. 
- This initial model serves as a starting point.

- In each iteration, the algorithm builds a new model that focuses on correcting the mistakes made by the previous models. 
- It identifies the patterns or relationships that the previous models struggled to capture and incorporates them into the new model.

- Gradient boosting is effective in handling complex problems and large datasets. It can capture intricate patterns and dependencies that may be missed by a single model. 
- By combining the predictions from multiple models, gradient boosting produces a powerful predictive model.


