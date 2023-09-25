# MLEndLS ( MLEnd London Sound)

This project(ECS7020P_miniproject_basic) uses the [MLEndLS](https://www.kaggle.com/datasets/jesusrequena/mlend-london-sounds) audio dataset to predict whether an audio is recorded indoors or outdoors, by extracting audio features and passing through a Machine Learning Pipeline which includes normalisation,feature extraction,model selection using GridSearchCV and 10-fold Cross Validation techniques.
Creating the required labels for a dataset that does not have the required labels for solving classification problem is a challenge. Hence the next part of this project (ECS7020P_miniproject_advanced) involves grouping audio data using audio features and creating new cluster labels using K-Means Clustering and solving a multiclass problem using the optimized Machine Learning Model based on the Cluster Labels obtained.

Models implemented: KNN, Logistic Regression, SVM

The MLEndLS.csv file contains all the required additional information about the MLEndLS dataset. The ECS7020P_miniproject_basic.ipynb file predicts whether audio was recorded indoors or outdoors whereas the ECS7020P_miniproject_advanced.ipynb file classifies the new labels created using K-Means Clustering technique. 



