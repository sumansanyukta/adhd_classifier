# Designing a Binary Classification Model to Differentiate Between ADHD and Healthy Subjects Using Resting State Electroencephalograpgy (EEG)

Authors: Amir Jahanian Najafabadi; Sanyukta Suman; Professor Dr. Benjamin Godde 

Email: a.jahaniannajafabadi@jacobs-university.de ; amirjahanian.neuro@gmail.com
Email: sanyuktasuman28@gmail.com


# ABSTRACT

Background: Attention-Deficit/Hyperactivity Disorder (ADHD) is a chronic behavioraldisorder, diagnosed in both adult and children.  Subjects with ADHD face difficulties inmaintaining concentration in prolonged windows of time. The main problem with ADHDis the tendency of patients to show symptoms after the disorder has been developed, oftenpast infancy. Therefore, an automated diagnosis pipeline for diagnosing ADHD can be oftremendous value to modern medical science.

Objective:The objective of this thesis is to develop a tool for physicians to recognize ADHDsubjects from healthy subjects using a neural network for classifying electroencephalography(EEG) data.

Method:The dataset for this investigation consists of 200 subjects taken from the HealthyBrain Network (HBN) dataset and 100 subjects taken from the 19-Channel dataset. TheHBN data is recorded using the GSN Hydrocel 128-Channel sensor. The 19-Channel datais recorded using a 19-Channel electrodes by Mitsar Ltd. The data set was normalized byclustering down to 10 channels, corresponding to the 10 spatial lobes of the brain. Relevantfrequency bands were extracted for recording features. The features were used to fit a deep-learning model with the intention of producing a classifier, capable of providing a diagnosisbased on relevant frequency bands.

Results:The proposed model was evaluated by using the 5-fold cross validation technique.The CNN and LSTM models achieved 86% and 75% accuracy on the HBN dataset whichincluded 100 healthy subjects and 100 ADHD subjects from the HBN dataset. The samemodels achieved accuracies of 90% and 93% on the Combined dataset, which included 100healthy subjects from the HBN dataset and 100 ADHD subjects from the 19-Channel dataset.
**Kezwords:** ADHD, Healthy, EEG, CNN, LSTM 

# LEGAL NOTICE
This manuscript was prepared using a limited access dataset obtained from the Child Mind
Institute Bio bank, Healthy Brain Network. This manuscript reflects the views of the authors
and does not necessarily reflect the opinions or views of the Child Mind Institute. Research
reported in this publication was supported by Jacobs University and exposes the results of the
master thesis for the Data Engineering program. The 19-channels’ dataset from both ADHD
children and adults were also provided for research purposes by Amir Jahanian Najafabadi
and Dr. Farid Tofighnia, and this dataset was recorded from ADHD patients approached
psychiatric clinic in Iran.

