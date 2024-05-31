# Kidney Failure Prediction Using a DNN

This is a project with Professor [Feng-Tsun Chien](https://sites.google.com/nycu.edu.tw/ftchien/home?authuser=0) with the Institute of Electronics and the Institute of Artificial Intelligence Innovation, National Yang Ming Chiao Tung University (NYCU), his two affiliated research assistants [Ethan Lai](https://github.com/LaiEthanLai) and [Sam Wang](https://github.com/SamWang0807), and the Department of Internal Medicine -- Nephrology at National Taiwan University Hospital. 

The goal is to build a powerful artificial intelligence-assisted diagnosis system. Specifically, we train deep neural networks (DNNs) to predict whether a patient will experience kidney failure and, if so, when it will occur.

## What is in this repository?
We thank patients willing to participate in this project and generously share their data. We genuinely respect their privacy, so we will not release our dataset or the weights of our DNN. 

In `utils`, we implement three imputation methods to mitigate the missing data problem. The missing data arises because patients require various medical tests. We may not be able to collect all the above-mentioned metrics from every patient.

The DNN we adopt is in `model/net.py`.

## Methods
We use various biometrics as inputs for prediction: 

B_CRE, B_K, B_NA, B_UN, Hemoglobin, MCHC, PLT, WBC, Albumin, B_P, B_UA, Calcium, Triglyceride, DL, UPCR. 

These are common metrics a doctor will refer to when diagonizing a patient.

We elaborate on the three imputation methods as follows:

TBD
