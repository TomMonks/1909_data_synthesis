# 1909_data_synthesis

This repository is being updated as research is performed. The experiments (and required data) are available as Jupyter Notebooks and are also recorded as PDFs.

For any queries on this work contact m.allen@exeter.ac.uk

## Aim

To test the utility of a range of data synthesis techniques for use in machine learning.

## Problem

Patient-level health data is sensitive information and is often not suitable to be shared with machine learning models trained using that data. How can we share patient-level data so that machine learning models may be tested/improved?

## Suggested solution

Use data synthesis techniques to create a synthetic data set that behaves like real patient data, and an be used to train and test machine learning models.

## Techniques to test:

* Statistical sampling techniques based on known variance/covariance
* SMOTE (Synthetic Minority Oversampling Technique)
* VAEs (Variational AutoEncoders)
* GANs (Generative Adversarial Networks)

## Health data sets to test

https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

https://www.kaggle.com/ronitf/heart-disease-uci

https://www.kaggle.com/uciml/pima-indians-diabetes-database

https://www.kaggle.com/joniarroba/noshowappointments

https://www.kaggle.com/loveall/cervical-cancer-risk-classification

https://www.kaggle.com/sammy123/lower-back-pain-symptoms-dataset

https://www.kaggle.com/uciml/indian-liver-patient-records


