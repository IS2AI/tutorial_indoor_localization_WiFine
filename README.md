# A Tutorial on WiFi-based Indoor Localization 

The task of localization aims to determine a user’s (or an object’s) position in space. It is essential for a variety of applications (i.e emergency response, health care and public safety). While the outdoor localization problem was solved by the global navigation satellite systems (GPS, GLONASS and GALILEO), the indoor localization still remains an open problem.

In this tutorial, we will use the simplified version of the [WiFine dataset](https://github.com/IS2AI/WiFine) to train a location prediction model. 

The following video provides an introduction to the problem of indoor localization, our solution and the WiFine dataset.
    
The video is followed up by the programming part, which is divided into two Jupyter Notebooks:
1. *indoor_localization_parts_1_2.ipynb*. 
    - Loading and preprocessing the dataset. 
    - Predicting of a user's coordinates using randrom forest regression.
3. *indoor_localization_parts_3.ipynb*. 
    - Loading and preprocessing the dataset. 
    - Predicting of a user's coordinates using a simple multi layer perceptron.

While we provide you all of the Machine Learning code, we ask you to implement a few tasks focused on preprocessing the dataset and evaluating the models.
If you are interested in the solutions, please contact us (<font color=blue>issai@nu.edu.kz</font>). 

Note, the target values for the test set are withheld. Instead, you are given the validation set to verify your best estimator.

Feel free to experiment with the code we provided or come up with a different approach. If you want to know how well you did on the test set, email us (<font color=blue>issai@nu.edu.kz</font>) your code and the predictions of your best estimator on the test features! 

The best mean error distance we got so far is 1.44, we hope you can beat this record!
