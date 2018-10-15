# multi-task-HAR
A multi-task convolutional neural network for humen activity recognition. 

Sensor readings from a smartphone can indicate the type of activity performed by the humen carying it. Usually, inertial sensors such as accelerometers and gyroscops are used. 
This subject is typicly refered to as Humen Activity Recognition (HAR).

Possible applications for this type of information includes:

* Fitness monitoring.
* Elder and youth care.
* GPS aiding in denied envaiorments.
* Personal Biometric Signature.

Different types of Machine learning techniques were performed to enable activity recognition from sensor readings. Ranging from basic ML algorithms that relay on extensive feature engineering to advance deep learning techniques.

One of the challenges in HAR is that even if the same activity is performed, sensor readings may difffer according on the smartphone body position. For example, a person riding a bike: accelerometer readings looks totaly diffrent if the smartphone is loacted in the pocket or on the upper arm. Even the orientation of a smartphone may differ for a specific position (For example, a smartphone in a backpack may have diffrent orientations).

In this work, we will develope a multi-task CNN that outputs both the activity performed and the smartphone position. The basic assumption is that buth tasks can benefit from having shared lower level features, especially because of the limited amount of training data.

The dataset used can be found in the folowing link under "Sensors activity dataset":

https://www.utwente.nl/en/eemcs/ps/research/dataset/

Full information regrarding this dataset can be found in:

Shoaib, M. and Bosch, S. and Incel, O.D. and Scholten, H. and Havinga, P.J.M. (2014) Fusion of Smartphone Motion Sensors for Physical Activity Recognition. Sensors, 14, 10146-10176
