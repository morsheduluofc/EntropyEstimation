# Entropy Estimation of DAC Profiles
This program estimate the entropy of Behavioral Authentication (BA) System profiles. A BA profile consists of a set of n d-dimensional vectors where each component of the vector is a feature value capturing specific behavioral property of the user. Due to the variations in users' behavior and accuracy of measuring systems, all vectors in a profile are not identical and have some variability.

## Entropy estimator
We used the python package "entropy_estimators" to estimate entropy of the profile. It has a method "continuous.get_h()" that uses k nearest neighbor based approach to estimate the entropy. The link of the python package: https://github.com/paulbrodersen/entropy_estimators

## Experiment settings:
- Every profile X has n, d dimentional vectors
- We used k=11 as the value of k of k nearest neighbor based approach
- We used Eucliden norm to measure distance between two vectors

