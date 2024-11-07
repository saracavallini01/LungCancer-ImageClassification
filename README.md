CT Scan Image Classification for Malignancy Detection
Project Overview
This project aims to develop a machine learning model for classifying CT scan images based on malignancy scores. The dataset includes images from 2,300 patients, with each patient providing two types of CT scan slices: a full slice and a zoomed slice focusing on the largest nodule. These images are labeled with malignancy scores ranging from 1 to 5, which are used as the target labels for classification.

Objectives
The model will perform two key classification tasks:

Benign vs. Malignant Classification: Classifying images into two categories based on malignancy scores (1-2-3 = Benign, 4-5 = Malignant).
Five-Class Malignancy Classification: Classifying images into one of five categories based on the malignancy score (1-5).
In addition to classification, the model will also provide an estimate of confidence for each prediction to help assess the reliability of the output.

Dataset
Full slice images: pat1_fullslice.nrrd
Zoomed slice images: pat1_nodule.nrrd
Malignancy scores: Provided in the dataset_lung.xlsx file, which includes the malignancy scores corresponding to each patient.
Approach
The project will use deep learning techniques, specifically Convolutional Neural Networks (CNNs), to analyze the CT scan images. The CNN model will learn to extract relevant features from the images to accurately predict malignancy scores. The model will be evaluated based on accuracy, precision, and confidence scores.

Goals
Develop a robust model for classifying CT scans.
Provide accurate binary and multi-class classification.
Generate confidence estimates for each prediction.
Explore the potential application of the model in clinical decision-making.
