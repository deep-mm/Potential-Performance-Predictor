# Potential-Performance-Predictor

This project aims to build a machine-learning model/s that can predict employee performance during the hiring process. The model will consider existing employees in the company and utilizing their performance over the last years, evaluate how a new employee with similar attributes will fit into the work environment at that company. This approach is unique in the sense that each person responds differently to various aspects of a work environment, and if we utilize the fact that an existing employee in that particular role has been performing well in that work environment, then it would be more accurate rather than just comparing skills or education. A major ethical issue that we will be addressing as part of this project is to look into attributes that may lead to bias and make decisions to remove any sort of bias during the hiring process.

This project contains following 3 jupyter notebooks:

1. FeatureSelection - This contains data analysis and feature selection techniques which then stores the selected feature data in a different csv file under data folder.
2. Ensemble - This runs multiple ML models based on concept of Adaboost to train and predict data objects.
3. Clustering - This contains code to create clusters based on KMeans and Hierarchical. It also contains graphs for identifying bias.