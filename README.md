# Mlops-USHospital
 A notebook for data validation, anomaly detection, and schema management using TensorFlow Data Validation (TFDV).
Data Validation with TensorFlow Data Validation (TFDV)

This repository contains a Jupyter Notebook for performing comprehensive data validation using TensorFlow Data Validation (TFDV). The notebook is part of an assignment that utilizes the Diabetes 130-US hospitals dataset from the UCI Machine Learning Repository to demonstrate data validation techniques.

Overview

TFDV is an open-source library designed to assist in understanding, validating, and monitoring machine learning (ML) datasets. This notebook leverages TFDV to:

Generate and visualize dataset statistics.

Infer schemas that define expected data properties.

Detect and address anomalies in datasets.

Compare training, evaluation, and serving datasets for consistency.

Identify and address data drift and skew.

Features

The notebook includes the following tasks:

1. Setup and Imports

Loads necessary libraries such as tensorflow, tensorflow_data_validation, and pandas.

2. Load the Dataset

Uses the Diabetes 130-US hospitals dataset, representing 10 years (1999-2008) of clinical care data from 130 US hospitals.

Provides over 50 features describing patient demographics, health outcomes, and treatment data.

3. Generate and Visualize Training Data Statistics

Generates summary statistics for the training dataset.

Visualizes key metrics such as feature distributions and correlations.

4. Infer a Data Schema

Infers a schema from the training data to define expected types, ranges, and constraints for each feature.

5. Detect and Fix Anomalies

Compares training and evaluation datasets to detect inconsistencies.

Identifies anomalies such as missing values, out-of-range data, or mismatched feature types.

Modifies the schema to address these issues.

6. Schema Environments

Examines schema environments to validate serving datasets.

Checks for anomalies specific to production environments.

7. Check for Data Drift and Skew

Identifies significant drift or skew between training, evaluation, and serving datasets.

Provides visualizations to pinpoint affected features.

8. Display Statistics for Data Slices

Generates and visualizes statistics for specific data slices (e.g., subsets of patients based on demographic or medical conditions).

9. Freeze the Schema

Finalizes and saves the schema for future use, ensuring consistency during production.

Dataset

The dataset used in this notebook is the Diabetes 130-US hospitals dataset, which includes:

Over 50 features related to patient demographics, clinical outcomes, and hospital treatments.

Data from 130 US hospitals spanning 10 years (1999-2008).


Outputs

Statistics visualization: Graphs and tables summarizing dataset properties.

Schema files: Inferred schemas defining dataset constraints.

Anomaly reports: Detected anomalies and resolutions.

License

This project is for educational purposes only and adheres to the licensing terms of the UCI Machine Learning Repository for the Diabetes 130-US hospitals dataset.

Author

Kasra Rasinoujehdehi

For questions or feedback, please contact.

