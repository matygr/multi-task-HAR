# multi-task-HAR
A multi-task convolutional neural network for human activity recognition. 

Sensor readings from a smartphone can indicate the type of activity performed by the human carrying it.
Usually, inertial sensors such as accelerometers and gyroscopes are used.
This subject is typically referred to as __Human Activity Recognition (HAR)__.

Possible applications for this type of information includes:
* Fitness monitoring. 
* Elder and youth care.
* GPS aiding in denied environments.
* Personal Biometric Signature.

Different types of Machine learning techniques were performed to enable activity recognition from sensor readings. Ranging from basic ML algorithms that relay on extensive feature engineering to advance deep learning techniques. 

One of the challenges in HAR is that even if the same activity is performed, sensor readings may differ according on the smartphone body position. For example, a person riding a bike: accelerometer readings looks totally different if the smartphone is located in the pocket or on the upper arm.

In this work, we will develop a multi-task CNN that outputs both the activity performed and the smartphone position.
The basic assumption is that both tasks can benefit from having shared lower level features, especially because of the limited amount of training data. 

__Due to the size of the file, Github doesn't always open the Deep-HAR.ipynb notebook.__ 
<br>
__Please download the file or use the following nbviewer link:__
<br>
https://nbviewer.jupyter.org/github/matygr/multi-task-HAR/blob/master/notebooks/Deep-HAR.ipynb#Refs

The dataset used can be found in the following link under "Sensors activity dataset":

https://www.utwente.nl/en/eemcs/ps/research/dataset/

Full information regarding this dataset can be found in:

Shoaib, M. and Bosch, S. and Incel, O.D. and Scholten, H. and Havinga, P.J.M. (2014) Fusion of Smartphone Motion Sensors for Physical Activity Recognition. Sensors, 14, 10146-10176
