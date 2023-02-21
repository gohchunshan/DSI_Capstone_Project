# Early Sepsis Prediction
For the fulfillment of requirements of Data Science Immersive Flex Course.


# Problem Statement:
To identify whether a person has sepsis based on early physiological factors provided such as vital signs (pulse oximetry, systolic/ diastolic blood pressure), lab values and demographics provided

The goal of the analysis is the early detection of sepsis using physiological data. The early prediction of sepsis is potentially life-saving, and we aim to predict sepsis n hours before the clinical prediction. Late prediction of sepsis is potentially life-threatening, and also consumes heavy hospital resources. By predicting sepsis in non-sepsis patients or predicting sepsis very early in sepsis patients consumes limited resources and we can assume the risk of prediction to be minimal.

Secondarily, we also wish to find the optimal window (number of hours in advcance) to predict sepsis based on the dataset.

# EDA and Observations:

- Only about 1.8% of raw records indicate sepsis [27916 / 1524294]
- Out of 40,336 unique patients, only about 7.3% patients have onset of sepsis [2932/40336]
![image](https://user-images.githubusercontent.com/110540717/220344215-fe2eb842-d7f2-4aa8-a249-e68871e7bd03.png)


# Preliminary Modelling:

