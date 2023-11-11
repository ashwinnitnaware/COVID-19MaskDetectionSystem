# COVID-19MaskDetectionSystem
COVID-19 Mask Detection System uses machine learning for real-time mask detection via live video. It identifies mask usage, monitors crowd sizes in public areas, and ensures adherence to safety protocols, helping control virus spread in busy locations.

Clone the repository, save it to google colab or local machine jupyter notebook
Open MyMask.ipynbg file and run it. 

Here is full documentation of COVID-19 Mask Detection System.

# Problem statement:-
First, we explore the problem of Mask detection using machine learning and signal processing techniques, and then we apply the messages for wearing a mask. We propose a Mask-detection method. As the count of the patients are increasing The World Health Organization (WHO) as well as the Centers for Disease Control and Prevention (CDC) has suggested the use of face masks for decreasing the spread of the virus. Therefore we are developing a system which will detect the mask is wired or not. Before special one person was required for checking if the mask is wired or not so for avoiding that we are developing this system.

# Objectives:-
-To avoid spreading of corona virus
-To maintain the count of people in the mall as per the
government rules

# Algorithm:
Haar cascade Algorithm:- 
Haar Cascade is a machine learning object detection algorithm used to identify objects in an image or video. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images and videos. It is then used to detect objects in other images and videos.
The algorithm has four stages: 
1. Haar Feature Selection 
2. Creating Integral Images 
3. Adaboost Training 
4. Cascading Classifiers 
5. It is well known for being able to detect faces and body parts in an image, but can be trained to identify almost any object.
Let’s take mask detection as an example. Initially, the algorithm needs a lot of positive videos of faces wearing mask and negative images without mask to train the classifier. Then we need to extract features from it.

# Proposed System:-
We will be developing a system that work with a live video stream. Cases in which if the mask is worn the message will be displayed that please sanitize your hands. And in the case when the mask is not worn then the message will be displayed that please wear a mask and also the system will check the number of person in a mall if the number of person are more then the system will display a message reached maximum person limit, Please wait.

# Hardware required:(NO REQUIREMENT)
• R-pi 3B
• Pi_camera
• 8GB SD card
• LCD
• Servo motor
• Ultra sonic sensor
# Technologies used:-
  Python
# Advantages:-
• Detect mask is worned or not.
• Reduce the increasing count of covid-19
patients.
• Maintain count of people allowed in mall at
a time by government.

# Applications:-
• railway stations
• bus stops
• markets
• streets
• mall entrances
• schools and colleges

# Conclusion:-
These project can be useful for detecting mask in public place through live feed and by implementating proposed system it will help heathcare workers , doctors and goverment officials to take precautionary measures.

# Note: This project should be on local machine or colab notebook
# Author Reserves All Rights
