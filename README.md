# Google-Cloud-Server-Project

Fraud Detection Project

Class: CIS 415 - Arizona State University

Summary

This project focused on utilizing Google Cloud Platform (GCP) and PySpark to build and compare machine learning models, specifically Logistic Regression and Random Forest, for accurately detecting and predicting cases of fraud in large datasets.

In-Depth Description

For this project, I created two datasets, big_fraud_detection_dataset and small_fraud_detection_dataset, generated using ChatGPT. Due to its size, the large dataset is not included in this repository.

The workflow involved the following steps:

	1. Setting Up GCP: I utilized code provided by my professor to connect to GCP’s Cloud Storage, where the datasets were stored. I modified the code to integrate with my specific buckets and ensured PySpark worked correctly in Google Colab before transitioning to GCP Dataproc Jupyter.
 
	2.Data Issues and Resolution: While converting the dataset into Spark, I encountered issues where rows were not displaying properly. Initially suspecting a formatting issue, I discovered missing values in the dataset—despite specifying that there should be none during dataset creation. I resolved this by dropping rows with missing data, which enabled successful PySpark conversion.
 
	3.	Model Building: I processed the data using a text prompt with specific parameters and implemented two machine learning models: Logistic Regression and Random Forest. I compared their performance to determine which better predicted fraud cases.
 
	4.	Scaling Up: After validating the workflow on the smaller dataset, I set up GCP Dataproc to process the larger dataset using the same code.

This project enhanced my understanding of GCP tools, PySpark, and machine learning workflows, showcasing my ability to troubleshoot and adapt to challenges in a cloud-based environment.

