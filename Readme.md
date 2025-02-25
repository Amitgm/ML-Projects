Projects of all ML supervised and unsupervised learning

#### EMOTION CLASSFICATION USING SPEECH

The following project involves a supervised learning algorithm which involves classifying speeches based on 7 emotions happy,sad,suprised,disgust,angry,fear and neutral. The features are extracted from speech using the Librosa package and a single data instance is represented by 180 different features of floating point datatype. Different ML algorithms are used and their corresponding metrics are calculated. The following ML algorithms used are :

Random Forest Classifer  
XGBoost Classifer  
Linear SVC  
Logistic Regression  
Stochastic Gradient Descent Classifier  

The below image is of a single data instance which is converted to voice.

<div align="center">
    <img src="./images/Screenshot 2025-02-25 172805.png" alt="Sound wave" width="1200">
    <p><em>A sound wave</em></p>
</div>


A voting-based ensemble method is employed, utilizing soft voting to average the predicted probabilities of each class from multiple machine learning algorithms. This approach achieved an accuracy of 80.5% in the Kaggle Competetion

Below shows the confusion matrix of the voting based classifier

<div align="center">
    <img src="./images/Screenshot 2025-02-25 172805.png" alt="Sound wave" width="1200">
    <p><em>A sound wave</em></p>
</div>
