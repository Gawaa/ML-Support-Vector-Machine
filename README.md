# ML-Support-Vector-Machine

A Support Vector Machine (SVM) is a discriminative classifier formally defined by a separating hyperplane. In other words, given labeled training data (supervised learning), the algorithm outputs an optimal hyperplane which categorizes new examples. It does this by minimizing the margin between the data points near the hyperplane.

# Kernels

Polynomial features are possibly computationally expensive and may slow down runtime with large datasets. Rather than adding more polynomial features, add "landmarks" against which you test the proximity of other datapoints. Each member of the training set is a landmark. A kernel is the "similarity function" that measures how close an input is to a certain marker.

# Large Margin Classifier

An SVM will find the line (or hyperplane in the more general case) that splits the data with the largest margin. While outliers may sway the line to one direction, a small enough C value will enforce regularization. This new regularizing works the same with 1/\lambda, as seen in linear and logistic regression, but here we modify the cost component.
