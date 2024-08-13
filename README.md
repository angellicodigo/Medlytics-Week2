# Medlytics 2 Challenge Project

## Background
This challenge requires students to work with segments of signals from electroencephalography, electrooculography, electromyography, respiratory airflow, and electrocardiography. From these segments they must predict whether the patient was in an aroused (awake), in non-REM1, non-REM2, non-REM3, or REM state. Created by Brian Xia

## Dataset
Time series data of 7 physioloigcal singals. https://www.physionet.org/physiobank/database/challenge/2018/

## Presentation
We tested a MLP neural network and RNN neural network that produced similar results. We can improve our results by using models like LSTM layer, which literature reviews suggest accurate for predicitng sleep stages. We also could simplify the training data using normalization or feature selection. 

| Performance of MLP  |  | Performance of RNN |
| ------------- | ------------- |
|  Test Accuracy: 0.522 | Test Accuracy: 0.5415  |
| ROC Curve area under curve (AUC): 0.805 | ROC Curve area under curve (AUC): 0.806  |
|  Multi-class ROC Curve area under curve (AUC):  0.233 | Multi-class ROC Curve area under curve (AUC): 0.278  |

# What else does Medlytics Week 2 contain?
This is the repository for all lectures, assignments, and datasets for Week 2 of the BeaverWorks Medlytics course for 2022. The slides are provided here for easy reference, but will be presented in lecture format. You should fork this repository at the beginning of the week and work on your own copy when completing notebooks and challenge projects.

Datasets Used in this Repo:

Human Recognition Using Smartphone Software Dataset from UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones

## Notebooks
* Contains Jupyter Notebook lessons where students will need to write their own code
* Contains Jupyter Notebook Solutions (will be uploaded after lesson notebooks are completed by students)
* Contains lesson notebooks (and solutions) on the SIR model, Time Series Exercises 1 and 2, Signal Processing, Fourier Transformations, Signal Cleanup, ML on Signals, ANNs on Signal Data Using Keras, Introduction to CNNs, and 1D Convolutional Nets on Signal Data.
