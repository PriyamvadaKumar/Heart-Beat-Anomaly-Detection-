# Heart-Beat-Anomaly-Detection-using-Semi-Supervised-Learning 



Time series data including 420 timesteps, 61 sensors, and ~200 training samples for each outcome (normal and abnormal).
Detected Outliers(abnormals) using IsolationForest, OneClassSVM and LocalOutlierFactor(sklearn)     

<img width="630" alt="image1" src="https://user-images.githubusercontent.com/77410526/108445206-fb48a600-7229-11eb-8615-a6d156b6d9b6.png">


<img width="636" alt="image2" src="https://user-images.githubusercontent.com/77410526/108445891-339cb400-722b-11eb-91fb-a71887b34847.png">


Input: Samples X Dimensions*Features [Features = 420 ,Data points=204, Dimensions=61]
             

#Data Pre-processing:

load the train data through arff  under scipy

Put the array in dataframe format with help of pandas

Extract attributes/features and output

Extract output and encode it - 1 for normal and 0 for abnormal/outlier

Pick all rows other than outlier rows so training data has no outliers

Tested on mixture of normal and abnormal data ,output metrics for model performance (Accuracy, Precisiosn , Recall and AUC ROC) and compared 
