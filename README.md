## Dataset
The dataset comprises
of 3-axial linear acceleration and 3-axial angular velocity
measured at a constant rate of 50Hz using the embedded
accelerometer and gyroscope of an attached device. After
noise reduction and signal processing on the raw inertial
data, the time signals are sampled in a sliding window of
2.56 seconds, with a 50% overlap. Moreover, standard
measures like mean, median, standard deviation etc. are
also calculated.
Source: UCI Machine Learning Repository (http://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions#) 

## Data Description:
Samples:  10929 ;
Features:  561 ( Physical quantities like jerk, energy etc) ;
Classes:   12 {Walking, Walking_upstairs,  Walking_Downstairs, Sitting, Standing, Laying, Stand_to_Sit, Sit_to_Stand, Sit_to_Lie, Lie_to_Sit, Stand_to_Lie, Lie_to_Stand   }

## Models Trained:
Gaussian Naive Bayes,
Random Forest classifier,
Extra-trees classifier,
Multi-layer perceptron (with ReLU activation),
Logistic Regression,
C-Support Vector Classifier

## Results
The highest accuracy was obtained with the SVM ( with PCA ) : 98.26%

## Instructions
1. Navigate to the colab notebook and use the given data to run the code
