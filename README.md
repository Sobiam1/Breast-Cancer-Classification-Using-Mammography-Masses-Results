# Breast-Cancer-Classification-Using-Mammography-Masses-Results

This project is about helping detecting the severity of breast cancer based on the state of their mammographic 
masses results (Benign or Malignant). I used different machine learning algorithm to deeply analyse these results 
including SVM, Logistic Regression, Random Forest, Naive Bayes, Artificial Neural Network ...

In order to identify the best algorithm for this problem, ROC curves are being plotted.

## Problematic

Mammography is the most effective method for breast cancer screening available today. However, the low positive predictive value of breast
biopsy resulting from mammogram interpretation leads to approximately 70% unnecessary biopsies with benign outcomes. To reduce the high
number of unnecessary breast biopsies, several computer-aided diagnosis (CAD) systems have been proposed in the last years.These systems
help physicians in their decision to perform a breast biopsy on a suspicious lesion seen in a mammogram or to perform a short term follow-up
examination instead.

## Getting started

You can follow these steps to reproduce the same output:

  1. Clone the repository or download the Ipyn file and run each cell to get each output
  and don't forget to include your dataset.
  2. The repo contains the IPython Notebook for classification task and the dataset as txt file.
   Another file is included to describe the dataset attributes as well as a Readme file.
  3. Run the ipynb to see the results.

## Prerequisites

  1. Python
  2. Pandas
  3. matplotlib
  4. numpy
  5. scikit-learn
  6. Tensorflow
  7. Keras

## Dataset

The dataset used here is a public dataset from UCI Machine Learning Repository. 
The csv file needed "mammographic_masses.data.txt" is already attached in the repository (source: https://archive.ics.uci.edu/ml/datasets/Mammographic+Mass)
This data set can be used to predict the severity (benign or malignant) of a mammographic mass lesion from BI-RADS attributes and the patient's age.

There are 6 Attributes in total (1 goal field, 1 non-predictive, 4 predictive attributes).

Attribute description:

1. BI-RADS assessment: 1 to 5 (ordinal, non-predictive!)
2. Age: patient's age in years (integer)
3. Shape: mass shape: round=1 oval=2 lobular=3 irregular=4 (nominal)
4. Margin: mass margin: circumscribed=1 microlobulated=2 obscured=3 ill-defined=4 spiculated=5 (nominal)
5. Density: mass density high=1 iso=2 low=3 fat-containing=4 (ordinal)
6. Severity: benign=0 or malignant=1 (binominal, goal field!)

The file mammographic_masses.data.txt contains the attributes data.
The file mammographic_masses.names.txt gives the description of the attributes.
