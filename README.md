# Blood-Cell-Images

* Created a tool to detect images of blood cells using tensorflow 2.3.0
* Engineered images for better fit.
* Used Pre-trained model (ReNet50) for predictions.
* Built a client facing API using Flask, HTML and Javascript.

# Codes and Resources Used


* Python Version: 3.8.5
* Tensorflow Version : 2.3.0
* Packages: numpy, matplotlib, flask, tensorflow-2.0
* For Web Framework Requirements: pip install -r requirements.txt
* This Dataset is taken from the official NIH Website: https://www.kaggle.com/paultimothymooney/blood-cells
* Productionization: https://www.youtube.com/watch?v=BUh76-xD5qU

# Motivation

The diagnosis of blood-based diseases often involves identifying and characterizing patient blood samples.
Automated methods to detect and classify blood cell subtypes have important medical applications.


# Project Overview

* This dataset contains 12,500 augmented images of blood cells (JPEG) with accompanying cell type labels (CSV).
* There are approximately 3,000 images for each of 4 different cell types grouped into 4 different folders (according to cell type).
* The cell types are **Eosinophil**, **Lymphocyte**, **Monocyte**, and **Neutrophil**.


# Model Building

The model was build using Pre-Trained model ResNet50
https://keras.io/api/applications/resnet/#resnet50-function


# Productionization

In this step, I built a flask API endpoint with GUI that was hosted on a local webserver. The API endpoint takes in a request as image and returns a prediction.


![alt text](https://github.com/rishabdhar12/blood-cell-images/blob/main/screenshots/1.jpg)

![alt text](https://github.com/rishabdhar12/blood-cell-images/blob/main/screenshots/2.jpg)























