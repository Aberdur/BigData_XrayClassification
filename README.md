# BigData_XrayClassification

This code develops machine learning models using Apache Spark to classify X-Ray images from a Pediatric Chest X-Ray Image dataset. The primary goal is to accurately predict Pneumonia in patients. To achieve this, the models are built utilizing the advanced pyspark interfaces combined with BigDL, which is a platform designed for creating scalable deep learning applications.

## Dataset
The dataset used in this project was obtained from the Kaggle competition "Chest X-Ray Images (Pneumonia)". This dataset consists of chest X-ray images from patients with and without pneumonia.

## CNN with TensorFlow
In this project, a CNN was implemented using TensorFlow to classify chest X-ray images into two categories: "with pneumonia" and "without pneumonia". Several convolutional and pooling layers were used, followed by fully connected layers for classification.

## BigDL
In addition to TensorFlow, the implementation of a CNN using BigDL was explored. BigDL is a distributed deep learning library for Apache Spark. BigDL enables training deep learning models on large distributed datasets using the power of Spark.

## Comparison of Results
The results obtained by both approaches were compared in terms of accuracy, training time, and overall performance in classifying chest X-ray images.

## Usage Instructions
Download the dataset from the provided link and extract the files to a local directory.
Install the dependencies specified in the requirements file.
Run the provided notebook to train the models using TensorFlow and BigDL.
Evaluate the trained models.

## Contributors
Alejandro Bernabeu Durandez
Alberto González Calatayud
Enrique Solera Navarro
