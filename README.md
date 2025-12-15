# Air Traffic Anomaly Detection

## Overview
This project implements an unsupervised anomaly detection system to identify abnormal aircraft behavior using real flight data. The model learns normal flight patterns and flags statistically rare events that may indicate safety risks.

## Key Concepts
- Unsupervised Learning
- Anomaly Detection
- Multivariate Gaussian Distribution
- Feature Engineering
- TensorFlow Probability

## Dataset
Flight movement data containing aircraft position, speed, and altitude.
Dataset source: Kaggle (Aircraft data – Nov–Dec 2022)

## Features Used
- Speed (mph)
- Altitude
- Vertical rate (change in altitude)
- Trajectory change (change in latitude and longitude)

## Methodology
1. Perform basic EDA to understand data distribution.
2. Engineer simple flight dynamics features.
3. Model normal flight behavior using a Multivariate Gaussian distribution.
4. Identify anomalies using a probability threshold (ε).
5. Visualize detected anomalies on the flight path.

## Results
- The model successfully identifies rare and abnormal flight behaviors.
- Anomalies appear as outliers in probability distribution and spatial plots.

## Technologies Used
- Python
- Pandas, NumPy
- TensorFlow
- TensorFlow Probability
- Matplotlib

## Key Takeaway
This project demonstrates how unsupervised learning can be applied to safety-critical systems when labeled data is unavailable.

