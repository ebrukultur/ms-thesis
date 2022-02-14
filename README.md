# Network Intrusion Detection with a Deep Learning Approach

This repository contains the source code used for my master's thesis at METU, Graduate Program of the Cyber Security Department in Informatics Institute. The research is about _"Network Intrusion Detection with a Deep Learning Approach"_.

In this thesis work, it is aimed to increase the performance of the network intrusion detection by using deep learning algorithms. For this purpose, CSE-CICIDS2018 dataset including 83 network flow extracted features is used. These features are extracted from the virtual environment in Amazon Cloud including 50 machines for the attacking organization, 420 machines and 30 servers for the victim organization with different types and versions of OS, applications, services etc.

For more detailed information, see: https://www.unb.ca/cic/datasets/ids-2018.html

After pre-processing the dataset, LSTM is used as a deep learning algorithm. In addition, to overcome the class imbalance problem in the dataset, SMOTE with custom class weights are applied with the multi-class classification.

