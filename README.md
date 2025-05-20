# Blockchain-Anomaly-Detection

This project focuses on identifying malicious transactions in blockchain networks using machine learning techniques. Leveraging Bitcoin transaction data (30M+ entries), the goal is to detect anomalies such as fraudulent activities by analyzing transactional patterns.

Key Features:
Algorithms: Implemented K-means (baseline), Histogram-Based Outlier Detection (HBOS), Clustering-Based Local Outlier Factor (CBLOF), and Isolation Forest for anomaly detection.

Tools: Utilized Python’s PyOD library for outlier detection and SMOTE to address class imbalance (only 108 malicious samples).

Metrics: Evaluated models using accuracy, precision, recall, F1-score, and computational efficiency.
