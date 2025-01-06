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



Gas sensors, combined with machine learning, can significantly enhance demining operations by providing a non-invasive detection method.

The MQ2 sensor proved effective for capturing gas concentrations relevant to simulated landmine detection.

Data balancing and augmentation techniques are essential for improving model robustness and accuracy.
