Gas Detection System for Anti-Personnel Mine Detection

Project Overview

This project explores the use of gas detection sensors to assist in identifying anti-personnel mines by detecting chemical vapors, such as those associated with explosives. The system leverages machine learning to analyze sensor data, providing a safer and more efficient alternative to traditional demining methods. The sensor used in this project is the MQ2, known for its ability to detect a variety of gases.

Dataset and Data Recording

File Format: Data is stored in CSV format. Each entry includes:

Timestamp

Gas concentration levels

Label indicating the presence or absence of simulated landmine vapors

Data Recording Methodology:

Test Site: Data was collected in a room under ambient air conditions during midday.

Simulated Landmine: A lighter was placed within a 1-square-meter test area to emulate a landmine.

Sensor Placement: The MQ2 sensor was positioned at a fixed height to capture gas concentrations over the defined area.

Data Augmentation: Random oversampling was used to balance the dataset and ensure robust model training.

Machine Learning Model

Algorithm: Logistic Regression

Data Balancing: Random oversampling was applied to address class imbalance.

Classification Report

Metric

Class 0 (No Vapors)

Class 1 (Vapors)

Overall

Precision

0.61

0.60

0.60

Recall

0.66

0.55

0.60

F1-Score

0.63

0.57

0.60

Support

103

97

200

Accuracy: 60%

Macro Average: 60%

Weighted Average: 60%

Confusion Matrix

The confusion matrix for the Logistic Regression model is as follows:

Predicted \ Actual

0 (No Vapors)

1 (Vapors)

0 (No Vapors)

68

35

1 (Vapors)

44

53

This indicates moderate performance with room for improvement in false-negative reduction for class 1.

Key Insights

Gas sensors, combined with machine learning, can significantly enhance demining operations by providing a non-invasive detection method.

The MQ2 sensor proved effective for capturing gas concentrations relevant to simulated landmine detection.

Data balancing and augmentation techniques are essential for improving model robustness and accuracy.
