# Network Intrusion Detection with a Deep Learning Approach

This repository contains all the files for my master's thesis at METU, Graduate Program of the Cyber Security Department in Informatics Institute. The research is about _"Network Intrusion Detection with a Deep Learning Approach"_.

In this thesis work, it is aimed to increase the performance of the network intrusion detection by using deep learning algorithms. For this purpose, CSE-CICIDS2018 dataset including 83 network flow extracted features was used. These features were extracted from the virtual environment in Amazon Cloud including 50 machines for the attacking organization, 420 machines and 30 servers for the victim organization with different types and versions of OS, applications, services etc.

After pre-processing the dataset, LSTM was used as a deep learning algorithm. In addition, to overcome the class imbalance problem in the dataset, SMOTE with custom class weights were applied with the multi-class classification.

