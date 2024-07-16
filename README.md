# Nearest Centroid Classifier for the Iris Dataset

This project involves implementing a nearest centroid classifier in Google Colab, using the Iris dataset as the basis for evaluation. The classifier works by assigning each data point to the class of the nearest centroid, calculated using Euclidean distance.

## Implementation Steps

### Data Preparation
The Iris dataset was divided into training and testing sets to evaluate the classifier's performance. Data normalization was applied before training and classification to ensure that all features contribute equally to the distance calculations.
### Manual Distance Calculation

The Euclidean distance was used for determining the nearest centroid. The distance calculation was implemented manually, leveraging only the NumPy library for array operations.
### Training and Classification

The classifier was trained on the training set, computing the centroid for each class. Classification was performed by assigning each test data point to the class of the nearest centroid.
### Performance Measurement

Accuracy was measured on both the training and testing sets. Results were compared to assess the classifier's effectiveness and generalization capability.
## Conclusion

The project demonstrates the implementation of a nearest centroid classifier from scratch, including manual calculation of Euclidean distances. The performance of the classifier was evaluated on both training and testing sets, providing insights into its accuracy and generalization capabilities. This project showcases a simple yet effective approach to classification using centroids, emphasizing the importance of data normalization and careful implementation of distance metrics.
