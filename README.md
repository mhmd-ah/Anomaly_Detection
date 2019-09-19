# Anomaly_Detection

## 1- Autoencoder Neural Network
In this projec, an autoencoder neural network is built using *Keras* to forecast failure in a four bearing system using [NASA Acoustics and Vibration Database](http://data-acoustics.com/measurements/bearing-faults/bearing-4/) that contains three sets of data. Each data is consisting of four bearings which had been run under constant running condition to failure. Here in this project, second test's data is used to train the autoencoder NN model. Once you download the [database](http://ti.arc.nasa.gov/c/3/), you can get more details on the conducted vibration experiments and the structure of data through reading the *Readme* file attached to it. 

To run this code in __jupyter notebook__, you need to change the directory of data, *data_dir*, to what it is on your hard drive. The general idea of using autoencoder NN is to train the NN model using the normal running condition data, so any deviation from it might result in failure.


## 1-1 Install
This project requires Python 2.7 or higher with the following libraries installed:
  * [numpy](https://numpy.org/)
  * [pandas](https://pandas.pydata.org/)
  * [tensorflow (r2.0)](https://www.tensorflow.org/versions/r2.0/api_docs/python/tf)
  * [keras](https://www.tensorflow.org/versions/r2.0/api_docs/python/tf)
  * [scikit-learn](https://scikit-learn.org/stable/)
  * [matplotlib](https://matplotlib.org/)
  * [seaborn](https://seaborn.pydata.org/)
  
## 1-2 Files:
For this project, you need to download the database using this link:
  * [NASA Acoustics and Vibration Database](http://ti.arc.nasa.gov/c/3/) 
  
## 1-3 Run:
In the terminal or command window, navigate to the directory of this project *AutoEncoderNN* and then run the code using either of the following commands:

`jupyter notebook Anomaly_Detection.ipynb`

or 

`ipython notebook Anomaly_Detection.ipynb`


## 2- LSTM






