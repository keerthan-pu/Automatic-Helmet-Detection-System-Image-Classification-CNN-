# Automatic-Helmet-Detection-System-Image-Classification-CNN-

![bki](https://github.com/keerthan-pu/Automatic-Helmet-Detection-System-Image-Classification-CNN-/assets/114256472/189a3431-d4f4-45be-a834-a146ca86de65)

# Implementation
The proposed system is very much capable for detecting helmet in all certain situations with 
high level of accuracy. Here the system has been tested with various frames and result is 
effectively obtained with minimal error rate. 

Tensorflow and Keras are two main packages that allow to train a system with certain 
circumstances that affect the accuracy at good extents. A system is proposed for careless 
identification of traffic rule violators who ride motorbikes without using helmets. A PC 
vision framework that is isolated into modules like moving items division, moving articles 
arrangement and helmet use identification will help the traffic specialists to require activity 
contrary to managing violators. This framework is regularly stretched out to recognize and 
report number plates of violators by consolidating this method with programmed vehicle 
place acknowledgment frameworks by synchronizing various view cameras.  

The captured images are given as input to the CNN model to train for the custom classes. 
Theyclassify the captured image and extract the image without helmet. Once this is done, an 
image is given as input. The model detects all the images using ROI. From this we obtain the 
information regarding the person riding the motorbike. If the person is not wearing a helmet, 
then we can easily extract the information of the rider. This can further be used to extract the 
number plate. This may include detection of license plates which will help the traffic police 
to automatically detect the defaulters thus sending an Penalty message to those who violate 
traffic rules. This will not just ease the workload of the traffic police but also be more 
convenient in all aspects. 

# Architecture

![bk1](https://github.com/keerthan-pu/Automatic-Helmet-Detection-System-Image-Classification-CNN-/assets/114256472/b32b82b1-ffef-4a4f-aeb7-74910b2cd681)

Architecture diagram for helmet detection is the system that is used to abstract the overall 
outline of the system and the relationship, constraints and boundaries between components. 
Classification of detection of helmet use by motorcyclists was divided into three main stages 
determining the ROI, extraction of the attributes and image classification.

The ROI is a region of the captured image in the vehicle segmentation stage. As the proposed system is 
interested in the detection of motorcyclists without helmets, the head region of the 
motorcyclist must be located completely inside the ROI. The upper part of the image was 
employed for the definition of the ROI. This part is as same as second as we use same tensor 
flow to detect number plate using the same ROI. This is implied using python code which 
gets true or false byte code from tensor flow  which is used in condition statement and then  
calculate the penalty .The penalty amount is sent to owner of vehicle involved in the incident 
or occurred using their number plate. 


